<script lang="ts" setup>
import { useRouter } from "vue-router";
import { onMounted, ref } from "vue";
import { enterpriseInfoAPI } from "@/apis/enterprise/info";
import { agencyInfoAPI } from "@/apis/agency/info";
import { adminInfoAPI } from "@/apis/admin/info";
import { useClientStore } from "@/stores";
const clientStore = useClientStore();
const router = useRouter();
const loginIn = () => {
  router.push("/login");
};
const loginOut = () => {
  clientStore.clearToken();
  clientStore.clearIdentity();
  clientStore.clearType();
  router.push("/login");
};
const clientInfo = ref();
const getInfo = async () => {
  if (clientStore.identity === "企业") {
    const res = await enterpriseInfoAPI();
    clientInfo.value = res.data;
  }else if(clientStore.identity === "政府"){
    const res = await agencyInfoAPI();
    clientInfo.value = res.data;
  }else if(clientStore.identity === "管理员"){
    const res = await adminInfoAPI();
    clientInfo.value = res.data;
  }
};

onMounted(() => {
  getInfo();
});
</script>

<template>
  
  <el-container
    style="position: relative; top: 0; left: 0; width: 100%; height: 100%"
  >
    <!-- header布局 -->
    <el-header class="header" style="background-color: #181f2e" height="5rem">
      <div
        class="text-red-700 text-3xl italic font-black antialiased font-sans pt-5 pl-3"
      >
        碳交易平台
      </div>
      <el-button
        style="
          position: absolute;
          top: 25px;
          left: 300px;
          width: 120px;
          color: black;
        "
        type="primary"
        disabled
        >企业数据总览</el-button
      >
      <el-button
        @click="router.push('/view')"
        style="
          position: absolute;
          top: 25px;
          left: 420px;
          width: 120px;
          color: black;
        "
        type="danger"
        >区块链数据总览</el-button
      >
      <div class="header-user">
        <div class="text">身份: {{ clientStore.identity }}</div>
        <div class="text">用户名: {{ clientInfo?.name }}</div>
        <div>
          <el-button type="primary" @click="loginIn">登录</el-button>
          <el-button type="danger" @click="loginOut">注销</el-button>
        </div>
      </div>
    </el-header>

    <el-container>
      <!-- aside布局 -->
      <el-aside width="12.5rem" class="aside">
        <el-menu
          active-text-color="#ffd04b"
          background-color="#0C1220"
          text-color="#fff"
          router
          style="height: 100%; padding-top: 0.625rem"
        >
          <el-menu-item class="aside-item" index="/info_view" v-if="false">
            <span>信息总览</span>
          </el-menu-item>
          <el-menu-item
            class="aside-item"
            index="/data_submit"
            v-if="clientStore.identity === '企业'"
          >
            <span>数据提交</span>
          </el-menu-item>
          <el-menu-item
            class="aside-item"
            index="/data_history"
            v-if="clientStore.identity === '企业'"
          >
            <span>数据记录</span>
          </el-menu-item>
          <el-menu-item
            class="aside-item"
            index="/trade_apply"
            v-if="clientStore.identity === '企业'"
          >
            <span>交易申请</span>
          </el-menu-item>
          <el-menu-item
            class="aside-item"
            index="/trade_history"
            v-if="clientStore.identity === '企业'"
          >
            <span>交易记录</span>
          </el-menu-item>
          <el-menu-item
            class="aside-item"
            index="/enterprise_list"
            v-if="clientStore.identity !== '企业'"
          >
            <span>企业总览</span>
          </el-menu-item>
          <el-menu-item
            class="aside-item"
            index="/trade_list"
            v-if="clientStore.identity !== '企业'"
          >
            <span>交易总览</span>
          </el-menu-item>
          <el-sub-menu class="aside-item" v-if="clientStore.identity !== '企业'">
            <template #title>
              <span style="margin-left: 2.6875rem;">数据总览</span>
            </template>
            <el-menu-item style="padding-left: 4.375rem;" index="/data_list/generateElectricity">发电企业</el-menu-item>
            <el-menu-item style="padding-left: 4.375rem;" index="/data_list/electricGrid">电网企业</el-menu-item>
          </el-sub-menu>
        </el-menu></el-aside
      >
      <!-- main布局 -->
      <el-main>
        <RouterView />
      </el-main>
    </el-container>
  </el-container>
</template>

<style lang="scss" scoped>
.header {
  display: grid;
  grid-template-columns: minmax(15rem, auto) 1fr auto;
  grid-template-rows: 1fr;
  .header-user {
    grid-area: 1 / 3 / span 1 / span 1;
    display: grid;
    grid-template-columns: auto auto auto;
    grid-template-rows: 1fr;
    align-items: center;
    justify-items: center;
    column-gap: 1rem;
    .text {
      color: white;
    }
    div:nth-child(-n + 2) {
      padding-right: 1rem;
      border-right: 0.0625rem solid hsl(0, 0%, 45%);
    }
  }
}

.aside {
  height: 100%;
  .aside-item {
    height: 3.75rem;
    display: grid;
    grid-template: 1fr, 1fr;
    span {
      align-items: center;
      justify-items: center;
      text-align: center;
      font-size: large;
    }
  }
  .aside-item:not(:last-child) {
    span {
      border-bottom: 0.0625rem solid hsl(0, 0%, 45%);
    }
  }
}
</style>

<template>
  <div class="bg">
    <div class="title">智能大屏数据中心</div>
    <div class="leftMain">
      <div class="leftMain_top">
        <div class="leftMain_topIn">
          <ul>
            <li>
              <div class="liIn">
                <h3>这里是标题1</h3>
                <p class="shu"><span class="shu1">6890.69</span><i>元</i></p>
                <div class="zi">
                  <span class="span1">小标题：文字</span
                  ><span>小标题：文字</span>
                </div>
                <span class="border_bg_leftTop"></span>
                <span class="border_bg_rightTop"></span>
                <span class="border_bg_leftBottom"></span>
                <span class="border_bg_rightBottom"></span>
              </div>
            </li>
            <li>
              <div class="liIn">
                <h3>这里是标题2</h3>
                <p class="shu"><span class="shu2">6090.99</span><i>元</i></p>
                <div class="zi">
                  <span class="span1">小标题：文字</span
                  ><span>小标题：文字</span>
                </div>
                <span class="border_bg_leftTop"></span>
                <span class="border_bg_rightTop"></span>
                <span class="border_bg_leftBottom"></span>
                <span class="border_bg_rightBottom"></span>
              </div>
            </li>
            <li>
              <div class="liIn">
                <h3>这里是标题3</h3>
                <p class="shu"><span class="shu3">2890.39</span><i>元</i></p>
                <div class="zi">
                  <span class="span1">小标题：文字</span
                  ><span>小标题：文字</span>
                </div>
                <span class="border_bg_leftTop"></span>
                <span class="border_bg_rightTop"></span>
                <span class="border_bg_leftBottom"></span>
                <span class="border_bg_rightBottom"></span>
              </div>
            </li>
            <li>
              <div class="liIn">
                <h3>这里是标题4</h3>
                <p class="shu"><span class="shu4">7590.15</span><i>元</i></p>
                <div class="zi">
                  <span class="span1">小标题：文字</span
                  ><span>小标题：文字</span>
                </div>
                <span class="border_bg_leftTop"></span>
                <span class="border_bg_rightTop"></span>
                <span class="border_bg_leftBottom"></span>
                <span class="border_bg_rightBottom"></span>
              </div>
            </li>
          </ul>
        </div>
      </div>
      <div class="leftMain_middle">
        <div class="leftMain_middle_left">
          <div class="leftMain_middle_leftIn">
            <h3>这里是标题</h3>
            <!-- 为ECharts准备一个具备大小（宽高）的Dom -->
            <div
              class="biaoge"
              style="width: 100%; height: 25vh"
              id="chartmain"
            ></div>

            <span class="border_bg_leftTop"></span>
            <span class="border_bg_rightTop"></span>
            <span class="border_bg_leftBottom"></span>
            <span class="border_bg_rightBottom"></span>
          </div>
        </div>
        <div class="leftMain_middle_right">
          <div class="leftMain_middle_rightIn">
            <h3>这里是标题</h3>
            <div class="biaoge biaoge_pai" style="width: 100%; height: 25vh">
              <div class="biaoge_paiIn">
                <ul>
                  <li>
                    <div class="liIn">
                      <div class="liIn_left">
                        <span class="bot"></span><span class="zi">第一名</span>
                      </div>
                      <div class="liIn_line">
                        <div class="line_lineIn" style="width: 98.5%"></div>
                      </div>
                      <p class="num">98.5%</p>
                    </div>
                  </li>
                  <li>
                    <div class="liIn liIn2">
                      <div class="liIn_left">
                        <span class="bot"></span><span class="zi">第二名</span>
                      </div>
                      <div class="liIn_line">
                        <div class="line_lineIn" style="width: 88.5%"></div>
                      </div>
                      <p class="num">88.5%</p>
                    </div>
                  </li>
                  <li>
                    <div class="liIn liIn3">
                      <div class="liIn_left">
                        <span class="bot"></span><span class="zi">第三名</span>
                      </div>
                      <div class="liIn_line">
                        <div class="line_lineIn" style="width: 68.5%"></div>
                      </div>
                      <p class="num">68.5%</p>
                    </div>
                  </li>
                  <li>
                    <div class="liIn liIn4">
                      <div class="liIn_left">
                        <span class="bot"></span><span class="zi">第四名</span>
                      </div>
                      <div class="liIn_line">
                        <div class="line_lineIn" style="width: 40.5%"></div>
                      </div>
                      <p class="num">40.5%</p>
                    </div>
                  </li>
                  <li>
                    <div class="liIn liIn5">
                      <div class="liIn_left">
                        <span class="bot"></span><span class="zi">第五名</span>
                      </div>
                      <div class="liIn_line">
                        <div class="line_lineIn" style="width: 22.5%"></div>
                      </div>
                      <p class="num">22.5%</p>
                    </div>
                  </li>
                  <li>
                    <div class="liIn liIn6">
                      <div class="liIn_left">
                        <span class="bot"></span><span class="zi">第六名</span>
                      </div>
                      <div class="liIn_line">
                        <div class="line_lineIn" style="width: 10.5%"></div>
                      </div>
                      <p class="num">10.5%</p>
                    </div>
                  </li>
                </ul>
              </div>
            </div>
            <span class="border_bg_leftTop"></span>
            <span class="border_bg_rightTop"></span>
            <span class="border_bg_leftBottom"></span>
            <span class="border_bg_rightBottom"></span>
          </div>
        </div>
      </div>
      <div class="leftMain_middle">
        <div class="leftMain_middle_left">
          <div class="leftMain_middle_leftIn">
            <h3>这里是标题</h3>
            <div
              class="biaoge"
              style="width: 100%; height: 25vh"
              id="chartmain_zhe"
            ></div>

            <span class="border_bg_leftTop"></span>
            <span class="border_bg_rightTop"></span>
            <span class="border_bg_leftBottom"></span>
            <span class="border_bg_rightBottom"></span>
          </div>
        </div>
        <div class="leftMain_middle_right">
          <div class="leftMain_middle_rightIn">
            <h3>这里是标题</h3>
            <div class="biaoge biaoge_bi" style="width: 100%; height: 25vh">
              <ul>
                <li>
                  <div class="liIn">
                    <p class="shu shu1">23</p>
                    <p class="zi">今日收益比例</p>
                  </div>
                </li>
                <li>
                  <div class="liIn">
                    <p class="shu shu2">107</p>
                    <p class="zi">本月收益比例</p>
                  </div>
                </li>
                <li>
                  <div class="liIn">
                    <p class="shu shu3">107</p>
                    <p class="zi">历史收益比例</p>
                  </div>
                </li>
                <li>
                  <div class="liIn">
                    <p class="shu shu4">23</p>
                    <p class="zi">今日收益比例</p>
                  </div>
                </li>
                <li>
                  <div class="liIn">
                    <p class="shu shu5">23</p>
                    <p class="zi">本月收益比例</p>
                  </div>
                </li>
                <li>
                  <div class="liIn">
                    <p class="shu shu6">23</p>
                    <p class="zi">历史收益比例</p>
                  </div>
                </li>
              </ul>
            </div>
            <span class="border_bg_leftTop"></span>
            <span class="border_bg_rightTop"></span>
            <span class="border_bg_leftBottom"></span>
            <span class="border_bg_rightBottom"></span>
          </div>
        </div>
      </div>
    </div>
    <div class="rightMain">
      <div class="rightMain_top">
        <div class="rightMain_topIn">
          <h3>这里是标题</h3>
          <div
            class="biaoge"
            style="width: 100%; height: 30vh"
            id="chartmain_bing"
          ></div>

          <span class="border_bg_leftTop"></span>
          <span class="border_bg_rightTop"></span>
          <span class="border_bg_leftBottom"></span>
          <span class="border_bg_rightBottom"></span>
        </div>
      </div>
      <div class="rightMain_bottom">
        <div class="rightMain_bottomIn">
          <h3>这里是标题</h3>
          <div class="biaoge biaoge_list" style="width: 100%; height: 36vh">
            <div class="biaoge_listIn">
              <ul class="ul_title">
                <li>用户</li>
                <li>类型号</li>
                <li>类别一</li>
                <li>类别二</li>
                <li>类别三</li>
              </ul>
              <div class="ul_list">
                <div class="ul_listIn">
                  <ul class="ul_con">
                    <li>张三</li>
                    <li>11</li>
                    <li>类别一</li>
                    <li>类别二</li>
                    <li>类别三</li>
                  </ul>
                  <ul class="ul_con">
                    <li>张三</li>
                    <li>12</li>
                    <li>类别一</li>
                    <li>类别二</li>
                    <li>类别三</li>
                  </ul>
                  <ul class="ul_con">
                    <li>张三</li>
                    <li>13</li>
                    <li>类别一</li>
                    <li>类别二</li>
                    <li>类别三</li>
                  </ul>
                  <ul class="ul_con">
                    <li>更多</li>
                    <li>精美大屏</li>
                    <li>关注</li>
                    <li>公众号</li>
                    <li>DreamCoders</li>
                  </ul>
                  <ul class="ul_con">
                    <li>张三</li>
                    <li>15</li>
                    <li>类别一</li>
                    <li>类别二</li>
                    <li>类别三</li>
                  </ul>
                  <ul class="ul_con">
                    <li>张三</li>
                    <li>16</li>
                    <li>类别一</li>
                    <li>类别二</li>
                    <li>类别三</li>
                  </ul>
                  <ul class="ul_con">
                    <li>张三</li>
                    <li>11</li>
                    <li>类别一</li>
                    <li>类别二</li>
                    <li>类别三</li>
                  </ul>
                  <ul class="ul_con">
                    <li>张三</li>
                    <li>12</li>
                    <li>类别一</li>
                    <li>类别二</li>
                    <li>类别三</li>
                  </ul>
                  <ul class="ul_con">
                    <li>张三</li>
                    <li>13</li>
                    <li>类别一</li>
                    <li>类别二</li>
                    <li>类别三</li>
                  </ul>
                  <ul class="ul_con">
                    <li>张三</li>
                    <li>14</li>
                    <li>类别一</li>
                    <li>类别二</li>
                    <li>类别三</li>
                  </ul>
                  <ul class="ul_con">
                    <li>张三</li>
                    <li>15</li>
                    <li>类别一</li>
                    <li>类别二</li>
                    <li>类别三</li>
                  </ul>
                  <ul class="ul_con">
                    <li>张三</li>
                    <li>16</li>
                    <li>类别一</li>
                    <li>类别二</li>
                    <li>类别三</li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <span class="border_bg_leftTop"></span>
          <span class="border_bg_rightTop"></span>
          <span class="border_bg_leftBottom"></span>
          <span class="border_bg_rightBottom"></span>
        </div>
      </div>
    </div>
    <div style="clear: both"></div>
  </div>
</template>

<style>
@keyframes cuIcon-spin {
  0% {
    -webkit-transform: rotate(0);
    transform: rotate(0);
  }

  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}

.iconfont-spin {
  -webkit-animation: cuIcon-spin 2s infinite linear;
  animation: cuIcon-spin 2s infinite linear;
  display: inline-block;
}

.iconfont-pulse {
  -webkit-animation: cuIcon-spin 1s infinite steps(8);
  animation: cuIcon-spin 1s infinite steps(8);
  display: inline-block;
}

[class*="cuIcon-"] {
  font-family: "cuIcon";
  font-size: inherit;
  font-style: normal;
}

.cuIcon-appreciate:before {
  content: "\e644";
}

.cuIcon-check:before {
  content: "\e645";
}

.cuIcon-close:before {
  content: "\e646";
}

.cuIcon-edit:before {
  content: "\e649";
}

.cuIcon-emoji:before {
  content: "\e64a";
}

.cuIcon-favorfill:before {
  content: "\e64b";
}

.cuIcon-favor:before {
  content: "\e64c";
}

.cuIcon-loading:before {
  content: "\e64f";
}

.cuIcon-locationfill:before {
  content: "\e650";
}

.cuIcon-location:before {
  content: "\e651";
}

.cuIcon-phone:before {
  content: "\e652";
}

.cuIcon-roundcheckfill:before {
  content: "\e656";
}

.cuIcon-roundcheck:before {
  content: "\e657";
}

.cuIcon-roundclosefill:before {
  content: "\e658";
}

.cuIcon-roundclose:before {
  content: "\e659";
}

.cuIcon-roundrightfill:before {
  content: "\e65a";
}

.cuIcon-roundright:before {
  content: "\e65b";
}

.cuIcon-search:before {
  content: "\e65c";
}

.cuIcon-taxi:before {
  content: "\e65d";
}

.cuIcon-timefill:before {
  content: "\e65e";
}

.cuIcon-time:before {
  content: "\e65f";
}

.cuIcon-unfold:before {
  content: "\e661";
}

.cuIcon-warnfill:before {
  content: "\e662";
}

.cuIcon-warn:before {
  content: "\e663";
}

.cuIcon-camerafill:before {
  content: "\e664";
}

.cuIcon-camera:before {
  content: "\e665";
}

.cuIcon-commentfill:before {
  content: "\e666";
}

.cuIcon-comment:before {
  content: "\e667";
}

.cuIcon-likefill:before {
  content: "\e668";
}

.cuIcon-like:before {
  content: "\e669";
}

.cuIcon-notificationfill:before {
  content: "\e66a";
}

.cuIcon-notification:before {
  content: "\e66b";
}

.cuIcon-order:before {
  content: "\e66c";
}

.cuIcon-samefill:before {
  content: "\e66d";
}

.cuIcon-same:before {
  content: "\e66e";
}

.cuIcon-deliver:before {
  content: "\e671";
}

.cuIcon-evaluate:before {
  content: "\e672";
}

.cuIcon-pay:before {
  content: "\e673";
}

.cuIcon-send:before {
  content: "\e675";
}

.cuIcon-shop:before {
  content: "\e676";
}

.cuIcon-ticket:before {
  content: "\e677";
}

.cuIcon-back:before {
  content: "\e679";
}

.cuIcon-cascades:before {
  content: "\e67c";
}

.cuIcon-discover:before {
  content: "\e67e";
}

.cuIcon-list:before {
  content: "\e682";
}

.cuIcon-more:before {
  content: "\e684";
}

.cuIcon-scan:before {
  content: "\e689";
}

.cuIcon-settings:before {
  content: "\e68a";
}

.cuIcon-questionfill:before {
  content: "\e690";
}

.cuIcon-question:before {
  content: "\e691";
}

.cuIcon-shopfill:before {
  content: "\e697";
}

.cuIcon-form:before {
  content: "\e699";
}

.cuIcon-pic:before {
  content: "\e69b";
}

.cuIcon-filter:before {
  content: "\e69c";
}

.cuIcon-footprint:before {
  content: "\e69d";
}

.cuIcon-top:before {
  content: "\e69e";
}

.cuIcon-pulldown:before {
  content: "\e69f";
}

.cuIcon-pullup:before {
  content: "\e6a0";
}

.cuIcon-right:before {
  content: "\e6a3";
}

.cuIcon-refresh:before {
  content: "\e6a4";
}

.cuIcon-moreandroid:before {
  content: "\e6a5";
}

.cuIcon-deletefill:before {
  content: "\e6a6";
}

.cuIcon-refund:before {
  content: "\e6ac";
}

.cuIcon-cart:before {
  content: "\e6af";
}

.cuIcon-qrcode:before {
  content: "\e6b0";
}

.cuIcon-remind:before {
  content: "\e6b2";
}

.cuIcon-delete:before {
  content: "\e6b4";
}

.cuIcon-profile:before {
  content: "\e6b7";
}

.cuIcon-home:before {
  content: "\e6b8";
}

.cuIcon-cartfill:before {
  content: "\e6b9";
}

.cuIcon-discoverfill:before {
  content: "\e6ba";
}

.cuIcon-homefill:before {
  content: "\e6bb";
}

.cuIcon-message:before {
  content: "\e6bc";
}

.cuIcon-addressbook:before {
  content: "\e6bd";
}

.cuIcon-link:before {
  content: "\e6bf";
}

.cuIcon-lock:before {
  content: "\e6c0";
}

.cuIcon-unlock:before {
  content: "\e6c2";
}

.cuIcon-vip:before {
  content: "\e6c3";
}

.cuIcon-weibo:before {
  content: "\e6c4";
}

.cuIcon-activity:before {
  content: "\e6c5";
}

.cuIcon-friendaddfill:before {
  content: "\e6c9";
}

.cuIcon-friendadd:before {
  content: "\e6ca";
}

.cuIcon-friendfamous:before {
  content: "\e6cb";
}

.cuIcon-friend:before {
  content: "\e6cc";
}

.cuIcon-goods:before {
  content: "\e6cd";
}

.cuIcon-selection:before {
  content: "\e6ce";
}

.cuIcon-explore:before {
  content: "\e6d2";
}

.cuIcon-present:before {
  content: "\e6d3";
}

.cuIcon-squarecheckfill:before {
  content: "\e6d4";
}

.cuIcon-square:before {
  content: "\e6d5";
}

.cuIcon-squarecheck:before {
  content: "\e6d6";
}

.cuIcon-round:before {
  content: "\e6d7";
}

.cuIcon-roundaddfill:before {
  content: "\e6d8";
}

.cuIcon-roundadd:before {
  content: "\e6d9";
}

.cuIcon-add:before {
  content: "\e6da";
}

.cuIcon-notificationforbidfill:before {
  content: "\e6db";
}

.cuIcon-explorefill:before {
  content: "\e6dd";
}

.cuIcon-fold:before {
  content: "\e6de";
}

.cuIcon-game:before {
  content: "\e6df";
}

.cuIcon-redpacket:before {
  content: "\e6e0";
}

.cuIcon-selectionfill:before {
  content: "\e6e1";
}

.cuIcon-similar:before {
  content: "\e6e2";
}

.cuIcon-appreciatefill:before {
  content: "\e6e3";
}

.cuIcon-infofill:before {
  content: "\e6e4";
}

.cuIcon-info:before {
  content: "\e6e5";
}

.cuIcon-forwardfill:before {
  content: "\e6ea";
}

.cuIcon-forward:before {
  content: "\e6eb";
}

.cuIcon-rechargefill:before {
  content: "\e6ec";
}

.cuIcon-recharge:before {
  content: "\e6ed";
}

.cuIcon-vipcard:before {
  content: "\e6ee";
}

.cuIcon-voice:before {
  content: "\e6ef";
}

.cuIcon-voicefill:before {
  content: "\e6f0";
}

.cuIcon-friendfavor:before {
  content: "\e6f1";
}

.cuIcon-wifi:before {
  content: "\e6f2";
}

.cuIcon-share:before {
  content: "\e6f3";
}

.cuIcon-wefill:before {
  content: "\e6f4";
}

.cuIcon-we:before {
  content: "\e6f5";
}

.cuIcon-lightauto:before {
  content: "\e6f6";
}

.cuIcon-lightforbid:before {
  content: "\e6f7";
}

.cuIcon-lightfill:before {
  content: "\e6f8";
}

.cuIcon-camerarotate:before {
  content: "\e6f9";
}

.cuIcon-light:before {
  content: "\e6fa";
}

.cuIcon-barcode:before {
  content: "\e6fb";
}

.cuIcon-flashlightclose:before {
  content: "\e6fc";
}

.cuIcon-flashlightopen:before {
  content: "\e6fd";
}

.cuIcon-searchlist:before {
  content: "\e6fe";
}

.cuIcon-service:before {
  content: "\e6ff";
}

.cuIcon-sort:before {
  content: "\e700";
}

.cuIcon-down:before {
  content: "\e703";
}

.cuIcon-mobile:before {
  content: "\e704";
}

.cuIcon-mobilefill:before {
  content: "\e705";
}

.cuIcon-copy:before {
  content: "\e706";
}

.cuIcon-countdownfill:before {
  content: "\e707";
}

.cuIcon-countdown:before {
  content: "\e708";
}

.cuIcon-noticefill:before {
  content: "\e709";
}

.cuIcon-notice:before {
  content: "\e70a";
}

.cuIcon-upstagefill:before {
  content: "\e70e";
}

.cuIcon-upstage:before {
  content: "\e70f";
}

.cuIcon-babyfill:before {
  content: "\e710";
}

.cuIcon-baby:before {
  content: "\e711";
}

.cuIcon-brandfill:before {
  content: "\e712";
}

.cuIcon-brand:before {
  content: "\e713";
}

.cuIcon-choicenessfill:before {
  content: "\e714";
}

.cuIcon-choiceness:before {
  content: "\e715";
}

.cuIcon-clothesfill:before {
  content: "\e716";
}

.cuIcon-clothes:before {
  content: "\e717";
}

.cuIcon-creativefill:before {
  content: "\e718";
}

.cuIcon-creative:before {
  content: "\e719";
}

.cuIcon-female:before {
  content: "\e71a";
}

.cuIcon-keyboard:before {
  content: "\e71b";
}

.cuIcon-male:before {
  content: "\e71c";
}

.cuIcon-newfill:before {
  content: "\e71d";
}

.cuIcon-new:before {
  content: "\e71e";
}

.cuIcon-pullleft:before {
  content: "\e71f";
}

.cuIcon-pullright:before {
  content: "\e720";
}

.cuIcon-rankfill:before {
  content: "\e721";
}

.cuIcon-rank:before {
  content: "\e722";
}

.cuIcon-bad:before {
  content: "\e723";
}

.cuIcon-cameraadd:before {
  content: "\e724";
}

.cuIcon-focus:before {
  content: "\e725";
}

.cuIcon-friendfill:before {
  content: "\e726";
}

.cuIcon-cameraaddfill:before {
  content: "\e727";
}

.cuIcon-apps:before {
  content: "\e729";
}

.cuIcon-paintfill:before {
  content: "\e72a";
}

.cuIcon-paint:before {
  content: "\e72b";
}

.cuIcon-picfill:before {
  content: "\e72c";
}

.cuIcon-refresharrow:before {
  content: "\e72d";
}

.cuIcon-colorlens:before {
  content: "\e6e6";
}

.cuIcon-markfill:before {
  content: "\e730";
}

.cuIcon-mark:before {
  content: "\e731";
}

.cuIcon-presentfill:before {
  content: "\e732";
}

.cuIcon-repeal:before {
  content: "\e733";
}

.cuIcon-album:before {
  content: "\e734";
}

.cuIcon-peoplefill:before {
  content: "\e735";
}

.cuIcon-people:before {
  content: "\e736";
}

.cuIcon-servicefill:before {
  content: "\e737";
}

.cuIcon-repair:before {
  content: "\e738";
}

.cuIcon-file:before {
  content: "\e739";
}

.cuIcon-repairfill:before {
  content: "\e73a";
}

.cuIcon-taoxiaopu:before {
  content: "\e73b";
}

.cuIcon-weixin:before {
  content: "\e612";
}

.cuIcon-attentionfill:before {
  content: "\e73c";
}

.cuIcon-attention:before {
  content: "\e73d";
}

.cuIcon-commandfill:before {
  content: "\e73e";
}

.cuIcon-command:before {
  content: "\e73f";
}

.cuIcon-communityfill:before {
  content: "\e740";
}

.cuIcon-community:before {
  content: "\e741";
}

.cuIcon-read:before {
  content: "\e742";
}

.cuIcon-calendar:before {
  content: "\e74a";
}

.cuIcon-cut:before {
  content: "\e74b";
}

.cuIcon-magic:before {
  content: "\e74c";
}

.cuIcon-backwardfill:before {
  content: "\e74d";
}

.cuIcon-playfill:before {
  content: "\e74f";
}

.cuIcon-stop:before {
  content: "\e750";
}

.cuIcon-tagfill:before {
  content: "\e751";
}

.cuIcon-tag:before {
  content: "\e752";
}

.cuIcon-group:before {
  content: "\e753";
}

.cuIcon-all:before {
  content: "\e755";
}

.cuIcon-backdelete:before {
  content: "\e756";
}

.cuIcon-hotfill:before {
  content: "\e757";
}

.cuIcon-hot:before {
  content: "\e758";
}

.cuIcon-post:before {
  content: "\e759";
}

.cuIcon-radiobox:before {
  content: "\e75b";
}

.cuIcon-rounddown:before {
  content: "\e75c";
}

.cuIcon-upload:before {
  content: "\e75d";
}

.cuIcon-writefill:before {
  content: "\e760";
}

.cuIcon-write:before {
  content: "\e761";
}

.cuIcon-radioboxfill:before {
  content: "\e763";
}

.cuIcon-punch:before {
  content: "\e764";
}

.cuIcon-shake:before {
  content: "\e765";
}

.cuIcon-move:before {
  content: "\e768";
}

.cuIcon-safe:before {
  content: "\e769";
}

.cuIcon-activityfill:before {
  content: "\e775";
}

.cuIcon-crownfill:before {
  content: "\e776";
}

.cuIcon-crown:before {
  content: "\e777";
}

.cuIcon-goodsfill:before {
  content: "\e778";
}

.cuIcon-messagefill:before {
  content: "\e779";
}

.cuIcon-profilefill:before {
  content: "\e77a";
}

.cuIcon-sound:before {
  content: "\e77b";
}

.cuIcon-sponsorfill:before {
  content: "\e77c";
}

.cuIcon-sponsor:before {
  content: "\e77d";
}

.cuIcon-upblock:before {
  content: "\e77e";
}

.cuIcon-weblock:before {
  content: "\e77f";
}

.cuIcon-weunblock:before {
  content: "\e780";
}

.cuIcon-my:before {
  content: "\e78b";
}

.cuIcon-myfill:before {
  content: "\e78c";
}

.cuIcon-emojifill:before {
  content: "\e78d";
}

.cuIcon-emojiflashfill:before {
  content: "\e78e";
}

.cuIcon-flashbuyfill:before {
  content: "\e78f";
}

.cuIcon-text:before {
  content: "\e791";
}

.cuIcon-goodsfavor:before {
  content: "\e794";
}

.cuIcon-musicfill:before {
  content: "\e795";
}

.cuIcon-musicforbidfill:before {
  content: "\e796";
}

.cuIcon-card:before {
  content: "\e624";
}

.cuIcon-triangledownfill:before {
  content: "\e79b";
}

.cuIcon-triangleupfill:before {
  content: "\e79c";
}

.cuIcon-roundleftfill-copy:before {
  content: "\e79e";
}

.cuIcon-font:before {
  content: "\e76a";
}

.cuIcon-title:before {
  content: "\e82f";
}

.cuIcon-recordfill:before {
  content: "\e7a4";
}

.cuIcon-record:before {
  content: "\e7a6";
}

.cuIcon-cardboardfill:before {
  content: "\e7a9";
}
.cuIcon-cardboard:before {
  content: "\e7aa";
}

.cuIcon-formfill:before {
  content: "\e7ab";
}

.cuIcon-coin:before {
  content: "\e7ac";
}

.cuIcon-cardboardforbid:before {
  content: "\e7af";
}

.cuIcon-circlefill:before {
  content: "\e7b0";
}

.cuIcon-circle:before {
  content: "\e7b1";
}

.cuIcon-attentionforbid:before {
  content: "\e7b2";
}

.cuIcon-attentionforbidfill:before {
  content: "\e7b3";
}

.cuIcon-attentionfavorfill:before {
  content: "\e7b4";
}

.cuIcon-attentionfavor:before {
  content: "\e7b5";
}

.cuIcon-titles:before {
  content: "\e701";
}

.cuIcon-icloading:before {
  content: "\e67a";
}

.cuIcon-full:before {
  content: "\e7bc";
}

.cuIcon-mail:before {
  content: "\e7bd";
}

.cuIcon-peoplelist:before {
  content: "\e7be";
}

.cuIcon-goodsnewfill:before {
  content: "\e7bf";
}

.cuIcon-goodsnew:before {
  content: "\e7c0";
}

.cuIcon-medalfill:before {
  content: "\e7c1";
}

.cuIcon-medal:before {
  content: "\e7c2";
}

.cuIcon-newsfill:before {
  content: "\e7c3";
}

.cuIcon-newshotfill:before {
  content: "\e7c4";
}

.cuIcon-newshot:before {
  content: "\e7c5";
}

.cuIcon-news:before {
  content: "\e7c6";
}

.cuIcon-videofill:before {
  content: "\e7c7";
}

.cuIcon-video:before {
  content: "\e7c8";
}

.cuIcon-exit:before {
  content: "\e7cb";
}

.cuIcon-skinfill:before {
  content: "\e7cc";
}

.cuIcon-skin:before {
  content: "\e7cd";
}

.cuIcon-moneybagfill:before {
  content: "\e7ce";
}

.cuIcon-usefullfill:before {
  content: "\e7cf";
}

.cuIcon-usefull:before {
  content: "\e7d0";
}

.cuIcon-moneybag:before {
  content: "\e7d1";
}

.cuIcon-redpacket_fill:before {
  content: "\e7d3";
}

.cuIcon-subscription:before {
  content: "\e7d4";
}

.cuIcon-loading1:before {
  content: "\e633";
}

.cuIcon-github:before {
  content: "\e692";
}

.cuIcon-global:before {
  content: "\e7eb";
}

.cuIcon-settingsfill:before {
  content: "\e6ab";
}

.cuIcon-back_android:before {
  content: "\e7ed";
}

.cuIcon-expressman:before {
  content: "\e7ef";
}

.cuIcon-evaluate_fill:before {
  content: "\e7f0";
}

.cuIcon-group_fill:before {
  content: "\e7f5";
}

.cuIcon-play_forward_fill:before {
  content: "\e7f6";
}

.cuIcon-deliver_fill:before {
  content: "\e7f7";
}

.cuIcon-notice_forbid_fill:before {
  content: "\e7f8";
}

.cuIcon-fork:before {
  content: "\e60c";
}

.cuIcon-pick:before {
  content: "\e7fa";
}

.cuIcon-wenzi:before {
  content: "\e6a7";
}

.cuIcon-ellipse:before {
  content: "\e600";
}

.cuIcon-qr_code:before {
  content: "\e61b";
}

.cuIcon-dianhua:before {
  content: "\e64d";
}

.cuIcon-icon:before {
  content: "\e602";
}

.cuIcon-loading2:before {
  content: "\e7f1";
}

.cuIcon-btn:before {
  content: "\e601";
}

/* CSS Document */
.bg {
  margin: 0 auto;
  width: 100%;
  min-height: 100vh;
  background: url(../images/bg2.jpg) no-repeat;
  background-size: cover;
  padding-top: 0rem;
  padding: 0rem 0.2rem;
}
/*.conIn{
	display:flex;
	display: -webkit-flex;}*/
.title {
  width: 100%;
  font-size: 0.12rem;
  line-height: 0.3rem;
  color: rgba(14, 253, 255, 1);
  text-align: center;
  font-weight: bold;
}

.border_bg_leftTop {
  position: absolute;
  left: -0.008rem;
  top: -0.04rem;
  width: 0.37rem;
  height: 0.05rem;
  display: block;
  background: #01279d url(../images/title_left_bg.png) no-repeat;
  background-size: cover;
}
.border_bg_rightTop {
  position: absolute;
  right: -0.01rem;
  top: -0.01rem;
  width: 0.1rem;
  height: 0.1rem;
  display: block;
  background: url(../images/border_bg.jpg) no-repeat;
  background-size: cover;
}
.border_bg_leftBottom {
  position: absolute;
  left: -0.008rem;
  bottom: -0.008rem;
  width: 0.1rem;
  height: 0.1rem;
  display: block;
  background: url(../images/border_bg.jpg) no-repeat;
  background-size: cover;
}
.border_bg_rightBottom {
  position: absolute;
  right: -0.01rem;
  bottom: -0.01rem;
  width: 0.08rem;
  height: 0.08rem;
  display: block;
  background: url(../images/title_right_bg.png) no-repeat;
  background-size: cover;
}

.leftMain {
  width: 75%;
  float: left;
  padding-right: 0.1rem;
  padding-top: 0.1rem;
}

.rightMain {
  width: 25%;
  float: left;
  padding-top: 0.1rem;
}

.leftMain_top {
  width: 100%;
  padding-bottom: 0.1rem;
}
.leftMain_top ul {
  display: flex;
  display: -webkit-flex;
}
.leftMain_top ul li {
  float: left;
  width: 25%;
  padding-right: 0.1rem;
}
.leftMain_top ul li:last-child {
  padding: 0;
}
.leftMain_top ul li .liIn {
  border: 0.008rem solid rgba(14, 253, 255, 0.5);
  width: 100%;
  min-height: 60px;
  position: relative;
  padding: 0.08rem 0.05rem;
}
.leftMain_top ul li .liIn h3 {
  font-size: 0.08rem;
  color: #fff;
  margin-bottom: 0.05rem;
}

.leftMain_top ul li .liIn .shu {
  font-size: 0.12rem;
  color: rgba(14, 253, 255, 1);
  font-family: dig;
  margin-bottom: 0.02rem;
}
.leftMain_top ul li .liIn .shu i {
  font-size: 0.04rem;
  margin-left: 0.06rem;
  font-style: normal;
}
.leftMain_top ul li .liIn .zi {
  font-size: 0.04rem;
  color: #fff;
  position: relative;
  z-index: 10;
}
.leftMain_top ul li .liIn .zi .span1 {
  margin-right: 0.1rem;
}

.leftMain_middle {
  width: 100%;
  padding-bottom: 0.1rem;
  display: flex;
  display: -webkit-flex;
}

.leftMain_middle .leftMain_middle_left {
  width: 60%;
  padding-right: 0.1rem;
}
.leftMain_middle .leftMain_middle_left .leftMain_middle_leftIn {
  border: 0.008rem solid rgba(14, 253, 255, 0.5);
  width: 100%;
  min-height: 60px;
  position: relative;
  padding: 0.08rem 0.05rem;
}
.leftMain_middle .leftMain_middle_left .leftMain_middle_leftIn h3 {
  font-size: 0.08rem;
  color: #fff;
  margin-bottom: 0.05rem;
}
.leftMain_middle .leftMain_middle_left .leftMain_middle_leftIn .biaoge {
  min-height: 200px;
}

.leftMain_middle .leftMain_middle_right {
  width: 40%;
}
.leftMain_middle .leftMain_middle_right .leftMain_middle_rightIn {
  border: 0.008rem solid rgba(14, 253, 255, 0.5);
  width: 100%;
  min-height: 60px;
  position: relative;
  padding: 0.08rem 0.05rem;
}
.leftMain_middle .leftMain_middle_right .leftMain_middle_rightIn h3 {
  font-size: 0.08rem;
  color: #fff;
  margin-bottom: 0.05rem;
}
.leftMain_middle .leftMain_middle_right .leftMain_middle_rightIn .biaoge {
  min-height: 200px;
}
/*左边中间部分排行榜*/
.leftMain_middle .leftMain_middle_right .leftMain_middle_rightIn .biaoge_pai {
  width: 100%;
  overflow: hidden;
}
.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_pai
  ul
  li
  .liIn {
  display: flex;
  display: -webkit-flex;
  align-items: center;
  color: #fff;
  font-size: 0.06rem;
  height: 0.18rem;
}
.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_pai
  ul
  li
  .liIn
  .liIn_left {
  width: 25%;
  position: relative;
  padding-left: 0.14rem;
}
.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_pai
  ul
  li
  .liIn
  .liIn_left
  .bot {
  width: 0.08rem;
  height: 0.08rem;
  background: #f78cf3;
  border-radius: 1000px;
  display: block;
  position: absolute;
  left: 0.02rem;
  top: 0;
  bottom: 0;
  margin: auto 0;
}
.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_pai
  ul
  li
  .liIn2
  .liIn_left
  .bot {
  background: #e7feb8;
}
.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_pai
  ul
  li
  .liIn3
  .liIn_left
  .bot {
  background: #fdea8a;
}
.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_pai
  ul
  li
  .liIn4
  .liIn_left
  .bot {
  background: #8ff9f8;
}
.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_pai
  ul
  li
  .liIn5
  .liIn_left
  .bot {
  background: #d890fa;
}
.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_pai
  ul
  li
  .liIn6
  .liIn_left
  .bot {
  background: #05d1fc;
}
.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_pai
  ul
  li
  .liIn
  .liIn_left
  zi {
}
.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_pai
  ul
  li
  .liIn
  .liIn_line {
  width: 58%;
  height: 0.08rem;
  background: rgba(255, 255, 255, 0.5);
  border-radius: 2000px;
}
.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_pai
  ul
  li
  .liIn
  .liIn_line
  .line_lineIn {
  width: 100%;
  height: 0.08rem;
  background: #f78cf3;
  border-radius: 100px;
  -webkit-animation: widthMove1 2s ease-in-out;
}
.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_pai
  ul
  li
  .liIn2
  .liIn_line
  .line_lineIn {
  background: #e7feb8;
  -webkit-animation: widthMove2 2s ease-in-out;
}
.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_pai
  ul
  li
  .liIn3
  .liIn_line
  .line_lineIn {
  background: #fdea8a;
  -webkit-animation: widthMove3 2s ease-in-out;
}
.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_pai
  ul
  li
  .liIn4
  .liIn_line
  .line_lineIn {
  background: #8ff9f8;
  -webkit-animation: widthMove4 2s ease-in-out;
}
.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_pai
  ul
  li
  .liIn5
  .liIn_line
  .line_lineIn {
  background: #d890fa;
  -webkit-animation: widthMove5 2s ease-in-out;
}
.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_pai
  ul
  li
  .liIn6
  .liIn_line
  .line_lineIn {
  background: #05d1fc;
  -webkit-animation: widthMove6 2s ease-in-out;
}

.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_pai
  ul
  li
  .liIn
  .num {
  width: 17%;
  font-family: dig;
  padding-left: 0.02rem;
}
/*左边底部*/
.leftMain_middle .leftMain_middle_right .leftMain_middle_rightIn .biaoge_bi ul {
  display: flex;
  display: -webkit-flex;
  flex-wrap: wrap;
  width: 100%;
}
.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_bi
  ul
  li {
  width: 33.3%;
  text-align: center;
  margin-bottom: 0.05rem;
}
.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_bi
  ul
  li
  .shu {
  font-size: 0.14rem;
  color: rgba(14, 253, 255, 1);
  font-family: dig;
  padding: 0.12rem 0 0.02rem;
  font-weight: normal;
}
.leftMain_middle
  .leftMain_middle_right
  .leftMain_middle_rightIn
  .biaoge_bi
  ul
  li
  .zi {
  font-size: 0.06rem;
  color: #fff;
}
/*右边部分*/
.rightMain .rightMain_top {
  width: 100%;
  padding-bottom: 0.1rem;
}
.rightMain .rightMain_topIn {
  border: 0.008rem solid rgba(14, 253, 255, 0.5);
  width: 100%;
  min-height: 60px;
  position: relative;
  padding: 0.08rem 0.05rem;
}
.rightMain .rightMain_topIn h3 {
  font-size: 0.08rem;
  color: #fff;
  margin-bottom: 0.05rem;
}
.rightMain .rightMain_topIn .biaoge {
  min-height: 200px;
}

.rightMain .rightMain_bottom {
  width: 100%;
}
.rightMain .rightMain_bottomIn {
  border: 0.008rem solid rgba(14, 253, 255, 0.5);
  width: 100%;
  min-height: 60px;
  position: relative;
  padding: 0.08rem 0.05rem;
}
.rightMain .rightMain_bottomIn h3 {
  font-size: 0.08rem;
  color: #fff;
  margin-bottom: 0.05rem;
}
/*右下角表格*/
.rightMain .rightMain_bottomIn .biaoge {
  min-height: 200px;
}
.rightMain .rightMain_bottomIn .biaoge_list {
  overflow: hidden;
  position: relative;
}
.rightMain .rightMain_bottomIn .biaoge_list .biaoge_listIn .ul_list {
  overflow: hidden;
  position: relative;
}
.rightMain .rightMain_bottomIn .biaoge_list .biaoge_listIn .ul_listIn {
  -webkit-animation: 14s gundong linear infinite normal;
  animation: 14s gundong linear infinite normal;
  position: relative;
}
@keyframes gundong {
  0% {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
  }
  100% {
    -webkit-transform: translate3d(0, -30vh, 0);
    transform: translate3d(0, -30vh, 0);
  }
}

.rightMain .rightMain_bottomIn .biaoge_list ul {
  display: flex;
  display: -webkit-flex;
  width: 100%;
}
.rightMain .rightMain_bottomIn .biaoge_list .ul_title {
  background: linear-gradient(
    left,
    rgba(255, 255, 255, 0.1),
    rgba(255, 255, 255, 0.5),
    rgba(255, 255, 255, 0.1)
  );
  background: -ms-linear-gradient(
    left,
    rgba(255, 255, 255, 0.1),
    rgba(255, 255, 255, 0.5),
    rgba(255, 255, 255, 0.1)
  );
  background: -webkit-linear-gradient(
    left,
    rgba(255, 255, 255, 0.1),
    rgba(255, 255, 255, 0.5),
    rgba(255, 255, 255, 0.1)
  );
  background: -moz-linear-gradient(
    left,
    rgba(255, 255, 255, 0.1),
    rgba(255, 255, 255, 0.5),
    rgba(255, 255, 255, 0.1)
  );
}
.rightMain .rightMain_bottomIn .biaoge_list .ul_con {
  border-bottom: 0.008rem solid rgba(14, 253, 255, 0.5);
}
.rightMain .rightMain_bottomIn .biaoge_list ul li {
  width: 20%;
  text-align: center;
  color: #fff;
  font-size: 0.06rem;
  height: 0.2rem;
  line-height: 0.2rem;
}
.rightMain .rightMain_bottomIn .biaoge_list ul li:frist-child {
  text-align: left;
}

/* CSS Document */
@font-face {
  font-family: "dig";
  src: url("../fonts/DIN-Light"), url("../fonts/DIN-Medium"),
    url("../fonts/DIN-Bold.otf");
}
body,
p,
div,
h1,
h2,
h3,
h4,
h5,
h6,
button,
input,
ol,
li,
ul,
dl,
dt,
dd,
img,
table,
tr,
td,
th,
select {
  margin: 0;
  padding: 0;
  border: 0;
  list-style: none;
  box-sizing: border-box;
}
a,
img,
button,
input,
textarea {
  -webkit-tap-highlight-color: rgba(255, 255, 255, 0);
  outline-color: #0081ff;
  background: none;
}
button {
  outline: none;
}
input::-webkit-input-placeholder {
  color: #aaa;
}
input::-webkit-outer-spin-button,
input::-webkit-inner-spin-button {
  -webkit-appearance: none !important;
  margin: 0;
}
input[type="number"] {
  -moz-appearance: textfield;
}
body {
  margin: 0 auto;
  font-size: 16px;
  color: #121212;
  font-family: "Helvetica Neue", Helvetica, "PingFang SC", "Hiragino Sans GB",
    "Microsoft YaHei", "微软雅黑", Arial, sans-serif;
  position: relative;
}
a {
  text-decoration: none;
  color: #f06000;
}

.noborder {
  border: 0;
}

#header {
  height: 0.5rem;
  width: 100%;
  position: fixed;
  top: 0;
  left: 0;
  z-index: 1000;
}
.header {
  height: 0.5rem;
  width: 100%;
  position: fixed;
  top: 0;
  left: 0;
  z-index: 1000;
}
.headerIn {
  width: 100%;
  height: 100%;
  position: relative;
  background: #0081ff;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.headerIn .back {
  display: flex;
  height: 100%;
  align-items: center;
  padding-left: 0.2rem;
  font-size: 0.14rem;
  color: #fff;
  width: 20%;
}
.headerIn .save {
  display: flex;
  height: 65%;
  align-items: center;
  font-size: 0.14rem;
  color: #fff;
  padding: 0 0.2rem;
  text-align: right;
  justify-content: center;
  margin-right: 0.1rem;
  border-radius: 3px;
  border: 1px solid #fff;
}

.cuIcon-back:before {
  margin-right: 3px;
  font-size: 0.16rem;
}
.headerIn h2 {
  width: 50%;
  font-size: 0.18rem;
  color: #fff;
  font-weight: normal;
  text-align: center;
  margin: 0 auto;
  padding: 0;
  font-family: "微软雅黑";
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  margin: auto;
  height: 100%;
  line-height: 0.5rem;
}
.headerIn .sel {
  position: absolute;
  top: 0;
  right: 0;
  display: block;
  width: 30%;
  height: 100%;
  background: url(../images/icon_sel.png) no-repeat 90% center;
  background-size: 20px auto;
  padding-right: 25px;
  color: #fff;
  line-height: 45px;
}
.headerIn .share {
  position: absolute;
  top: 0;
  right: 10px;
  display: block;
  width: 60px;
  height: 100%;
  background: url(../images/icon_share.png) no-repeat 5px center;
  background-size: 20px auto;
  padding-left: 25px;
  color: #fff;
  line-height: 45px;
  text-align: right;
  font-size: 14px;
}

.zhezhao_new {
  position: fixed;
  z-index: 100000;
  background: rgba(0, 0, 0, 0.5);
  width: 100%;
  height: 20000px;
  top: 0;
  left: 0;
}

.nodate {
  background: url(../images/nodate.png) no-repeat top center;
  background-size: 65px auto;
  padding-top: 75px;
  text-align: center;
  font-size: 14px;
  color: #888;
  line-height: 24px;
  width: 90%;
  margin: 0 auto;
}
.nodate2 {
  background: url(../images/nodate8.png) no-repeat top center;
  background-size: 160px auto;
  padding-top: 150px;
  text-align: center;
  font-size: 14px;
  color: #888;
  line-height: 24px;
  width: 90%;
  margin: 150px auto 0;
}
.nodate3 {
  background: url(../images/nodate10.png) no-repeat top center;
  background-size: 160px auto;
  padding-top: 150px;
  text-align: center;
  font-size: 14px;
  color: #888;
  line-height: 24px;
  width: 90%;
  margin: 150px auto 0;
}
.nodate3 .goto {
  display: block;
  width: 120px;
  height: 40px;
  background: none;
  border: 1px solid #f06000;
  border-radius: 5px;
  color: #f06000;
  font-size: 16px;
  font-family: "微软雅黑";
  text-align: center;
  margin: 20px auto;
  line-height: 38px;
}
.eggloading {
  background: url(../images/loading2.gif) no-repeat top center;
  background-size: 60px auto;
  padding-top: 60px;
  text-align: center;
  font-size: 14px;
  color: #888;
  line-height: 24px;
  width: 90%;
  margin: 200px auto 0;
}
.articleDel {
  background: url(../images/nodate9.png) no-repeat top center;
  background-size: 160px auto;
  padding-top: 150px;
  text-align: center;
  font-size: 14px;
  color: #888;
  line-height: 24px;
  width: 90%;
  margin: 150px auto 0;
}

body .spinner-android {
  display: none;
}
body .loading {
  background: url(../images/loading2.gif) no-repeat center center;
  background-size: 60px auto;
  width: 80px;
  height: 80px;
  padding: 10px;
}

/*资讯白色头部*/
.headerIn2 {
  width: 100%;
  height: 100%;
  position: relative;
  background: #fff;
  max-width: 640px;
  margin: 0 auto;
  box-shadow: 1px 0 3px #aaa;
  -webkit-box-shadow: 1px 0 3px #aaa;
  -moz-box-shadow: 1px 0 3px #aaa;
}
.headerIn2 .back {
  position: absolute;
  top: 0;
  left: 0;
  display: block;
  width: 20%;
  height: 100%;
  background: url(../images/back4.png) no-repeat 10px center;
  background-size: 12px auto;
  padding-left: 25px;
  color: #555;
  line-height: 45px;
}
.headerIn2 h2 {
  width: 80%;
  height: 100%;
  line-height: 45px;
  font-size: 16px;
  color: #555;
  font-weight: normal;
  text-align: center;
  margin: 0 auto;
  padding: 0;
  font-family: "微软雅黑";
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
  font-weight: bold;
}
.headerIn2 h2 img {
  height: 100%;
}
.headerIn2 .share {
  position: absolute;
  top: 0;
  right: 10px;
  display: block;
  width: 60px;
  height: 100%;
  background: url(../images/zixun_icon_share.png) no-repeat right center;
  background-size: 20px auto;
  padding-left: 25px;
  color: #fff;
  line-height: 45px;
  text-align: right;
  font-size: 15px;
}
.headerIn2 .fabu {
  position: absolute;
  top: 7px;
  right: 10px;
  height: 30px;
  line-height: 30px;
  padding: 0 8px;
  font-size: 15px;
  background: #f06000;
  color: #fff;
  border-radius: 3px;
}

body {
  /* Color 可以自定义相关配色 */
  /* var属性兼容性 --> https://www.caniuse.com/#feat=css-variables */
  /* 标准色 */
  --red: #e54d42;
  --orange: #f37b1d;
  --yellow: #fbbd08;
  --olive: #8dc63f;
  --green: #39b54a;
  --cyan: #1cbbb4;
  --blue: #0081ff;
  --purple: #6739b6;
  --mauve: #9c26b0;
  --pink: #e03997;
  --brown: #a5673f;
  --grey: #8799a3;
  --black: #333333;
  --darkGray: #666666;
  --gray: #aaaaaa;
  --ghostWhite: #f1f1f1;
  --white: #ffffff;
  /* 浅色 */
  --redLight: #fadbd9;
  --orangeLight: #fde6d2;
  --yellowLight: #fef2ce;
  --oliveLight: #e8f4d9;
  --greenLight: #d7f0db;
  --cyanLight: #d2f1f0;
  --blueLight: #cce6ff;
  --purpleLight: #e1d7f0;
  --mauveLight: #ebd4ef;
  --pinkLight: #f9d7ea;
  --brownLight: #ede1d9;
  --greyLight: #e7ebed;
  /* 渐变色 */
  --gradualRed: linear-gradient(45deg, #f43f3b, #ec008c);
  --gradualOrange: linear-gradient(45deg, #ff9700, #ed1c24);
  --gradualGreen: linear-gradient(45deg, #39b54a, #8dc63f);
  --gradualPurple: linear-gradient(45deg, #9000ff, #5e00ff);
  --gradualPink: linear-gradient(45deg, #ec008c, #6739b6);
  --gradualBlue: linear-gradient(45deg, #0081ff, #1cbbb4);
  /* 阴影透明色 */
  --ShadowSize: 6px 6px 8px;
  --redShadow: rgba(204, 69, 59, 0.2);
  --orangeShadow: rgba(217, 109, 26, 0.2);
  --yellowShadow: rgba(224, 170, 7, 0.2);
  --oliveShadow: rgba(124, 173, 55, 0.2);
  --greenShadow: rgba(48, 156, 63, 0.2);
  --cyanShadow: rgba(28, 187, 180, 0.2);
  --blueShadow: rgba(0, 102, 204, 0.2);
  --purpleShadow: rgba(88, 48, 156, 0.2);
  --mauveShadow: rgba(133, 33, 150, 0.2);
  --pinkShadow: rgba(199, 50, 134, 0.2);
  --brownShadow: rgba(140, 88, 53, 0.2);
  --greyShadow: rgba(114, 130, 138, 0.2);
  --grayShadow: rgba(114, 130, 138, 0.2);
  --blackShadow: rgba(26, 26, 26, 0.2);

  background-color: var(--ghostWhite);
  color: var(--black);
  font-family:
    Helvetica Neue,
    Helvetica,
    sans-serif;
}

/* -- 阴影 -- */

.shadow[class*="white"] {
  --ShadowSize: 0 1px 6px;
}

.shadow-lg {
  --ShadowSize: 0px 0.4rem 1rem 0px;
}

.shadow-warp {
  position: relative;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.shadow-warp:before,
.shadow-warp:after {
  position: absolute;
  content: "";
  top: 20px;
  bottom: 30px;
  left: 20px;
  width: 50%;
  box-shadow: 0 30px 20px rgba(0, 0, 0, 0.2);
  transform: rotate(-3deg);
  z-index: -1;
}

.shadow-warp:after {
  right: 20px;
  left: auto;
  transform: rotate(3deg);
}

.shadow-blur {
  position: relative;
}

.shadow-blur::before {
  content: "";
  display: block;
  background: inherit;
  filter: blur(0.1rem);
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0.05rem;
  left: 0.05rem;
  z-index: -1;
  opacity: 0.4;
  transform-origin: 0 0;
  border-radius: inherit;
  transform: scale(1, 1);
}
/* ==================
          背景
 ==================== */

.line-red::after,
.lines-red::after {
  border-color: var(--red);
}

.line-orange::after,
.lines-orange::after {
  border-color: var(--orange);
}

.line-yellow::after,
.lines-yellow::after {
  border-color: var(--yellow);
}

.line-olive::after,
.lines-olive::after {
  border-color: var(--olive);
}

.line-green::after,
.lines-green::after {
  border-color: var(--green);
}

.line-cyan::after,
.lines-cyan::after {
  border-color: var(--cyan);
}

.line-blue::after,
.lines-blue::after {
  border-color: var(--blue);
}

.line-purple::after,
.lines-purple::after {
  border-color: var(--purple);
}

.line-mauve::after,
.lines-mauve::after {
  border-color: var(--mauve);
}

.line-pink::after,
.lines-pink::after {
  border-color: var(--pink);
}

.line-brown::after,
.lines-brown::after {
  border-color: var(--brown);
}

.line-grey::after,
.lines-grey::after {
  border-color: var(--grey);
}

.line-gray::after,
.lines-gray::after {
  border-color: var(--gray);
}

.line-black::after,
.lines-black::after {
  border-color: var(--black);
}

.line-white::after,
.lines-white::after {
  border-color: var(--white);
}

.bg-red {
  background-color: var(--red);
  color: var(--white);
}

.bg-orange {
  background-color: var(--orange);
  color: var(--white);
}

.bg-yellow {
  background-color: var(--yellow);
  color: var(--black);
}

.bg-olive {
  background-color: var(--olive);
  color: var(--white);
}

.bg-green {
  background-color: var(--green);
  color: var(--white);
}

.bg-cyan {
  background-color: var(--cyan);
  color: var(--white);
}

.bg-blue {
  background-color: var(--blue);
  color: var(--white);
}

.bg-purple {
  background-color: var(--purple);
  color: var(--white);
}

.bg-mauve {
  background-color: var(--mauve);
  color: var(--white);
}

.bg-pink {
  background-color: var(--pink);
  color: var(--white);
}

.bg-brown {
  background-color: var(--brown);
  color: var(--white);
}

.bg-grey {
  background-color: var(--grey);
  color: var(--white);
}

.bg-gray {
  background-color: #f0f0f0;
  color: var(--black);
}

.bg-black {
  background-color: var(--black);
  color: var(--white);
}

.bg-white {
  background-color: var(--white);
  color: var(--darkGray);
}

.bg-shadeTop {
  background-image: linear-gradient(rgba(0, 0, 0, 1), rgba(0, 0, 0, 0.01));
  color: var(--white);
}

.bg-shadeBottom {
  background-image: linear-gradient(rgba(0, 0, 0, 0.01), rgba(0, 0, 0, 1));
  color: var(--white);
}

.bg-red.light {
  color: var(--red);
  background-color: var(--redLight);
}

.bg-orange.light {
  color: var(--orange);
  background-color: var(--orangeLight);
}

.bg-yellow.light {
  color: var(--yellow);
  background-color: var(--yellowLight);
}

.bg-olive.light {
  color: var(--olive);
  background-color: var(--oliveLight);
}

.bg-green.light {
  color: var(--green);
  background-color: var(--greenLight);
}

.bg-cyan.light {
  color: var(--cyan);
  background-color: var(--cyanLight);
}

.bg-blue.light {
  color: var(--blue);
  background-color: var(--blueLight);
}

.bg-purple.light {
  color: var(--purple);
  background-color: var(--purpleLight);
}

.bg-mauve.light {
  color: var(--mauve);
  background-color: var(--mauveLight);
}

.bg-pink.light {
  color: var(--pink);
  background-color: var(--pinkLight);
}

.bg-brown.light {
  color: var(--brown);
  background-color: var(--brownLight);
}

.bg-grey.light {
  color: var(--grey);
  background-color: var(--greyLight);
}

.bg-gradual-red {
  background-image: var(--gradualRed);
  color: var(--white);
}

.bg-gradual-orange {
  background-image: var(--gradualOrange);
  color: var(--white);
}

.bg-gradual-green {
  background-image: var(--gradualGreen);
  color: var(--white);
}

.bg-gradual-purple {
  background-image: var(--gradualPurple);
  color: var(--white);
}

.bg-gradual-pink {
  background-image: var(--gradualPink);
  color: var(--white);
}

.bg-gradual-blue {
  background-image: var(--gradualBlue);
  color: var(--white);
}

.shadow[class*="-red"] {
  box-shadow: var(--ShadowSize) var(--redShadow);
}

.shadow[class*="-orange"] {
  box-shadow: var(--ShadowSize) var(--orangeShadow);
}

.shadow[class*="-yellow"] {
  box-shadow: var(--ShadowSize) var(--yellowShadow);
}

.shadow[class*="-olive"] {
  box-shadow: var(--ShadowSize) var(--oliveShadow);
}

.shadow[class*="-green"] {
  box-shadow: var(--ShadowSize) var(--greenShadow);
}

.shadow[class*="-cyan"] {
  box-shadow: var(--ShadowSize) var(--cyanShadow);
}

.shadow[class*="-blue"] {
  box-shadow: var(--ShadowSize) var(--blueShadow);
}

.shadow[class*="-purple"] {
  box-shadow: var(--ShadowSize) var(--purpleShadow);
}

.shadow[class*="-mauve"] {
  box-shadow: var(--ShadowSize) var(--mauveShadow);
}

.shadow[class*="-pink"] {
  box-shadow: var(--ShadowSize) var(--pinkShadow);
}

.shadow[class*="-brown"] {
  box-shadow: var(--ShadowSize) var(--brownShadow);
}

.shadow[class*="-grey"] {
  box-shadow: var(--ShadowSize) var(--greyShadow);
}

.shadow[class*="-gray"] {
  box-shadow: var(--ShadowSize) var(--grayShadow);
}

.shadow[class*="-black"] {
  box-shadow: var(--ShadowSize) var(--blackShadow);
}

.shadow[class*="-white"] {
  box-shadow: var(--ShadowSize) var(--blackShadow);
}

.text-shadow[class*="-red"] {
  text-shadow: var(--ShadowSize) var(--redShadow);
}

.text-shadow[class*="-orange"] {
  text-shadow: var(--ShadowSize) var(--orangeShadow);
}

.text-shadow[class*="-yellow"] {
  text-shadow: var(--ShadowSize) var(--yellowShadow);
}

.text-shadow[class*="-olive"] {
  text-shadow: var(--ShadowSize) var(--oliveShadow);
}

.text-shadow[class*="-green"] {
  text-shadow: var(--ShadowSize) var(--greenShadow);
}

.text-shadow[class*="-cyan"] {
  text-shadow: var(--ShadowSize) var(--cyanShadow);
}

.text-shadow[class*="-blue"] {
  text-shadow: var(--ShadowSize) var(--blueShadow);
}

.text-shadow[class*="-purple"] {
  text-shadow: var(--ShadowSize) var(--purpleShadow);
}

.text-shadow[class*="-mauve"] {
  text-shadow: var(--ShadowSize) var(--mauveShadow);
}

.text-shadow[class*="-pink"] {
  text-shadow: var(--ShadowSize) var(--pinkShadow);
}

.text-shadow[class*="-brown"] {
  text-shadow: var(--ShadowSize) var(--brownShadow);
}

.text-shadow[class*="-grey"] {
  text-shadow: var(--ShadowSize) var(--greyShadow);
}

.text-shadow[class*="-gray"] {
  text-shadow: var(--ShadowSize) var(--grayShadow);
}

.text-shadow[class*="-black"] {
  text-shadow: var(--ShadowSize) var(--blackShadow);
}

.bg-img {
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

.bg-mask {
  background-color: var(--black);
  position: relative;
}

.bg-mask::after {
  content: "";
  border-radius: inherit;
  width: 100%;
  height: 100%;
  display: block;
  background-color: rgba(0, 0, 0, 0.4);
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
}

.bg-mask div,
.bg-mask cover-div {
  z-index: 5;
  position: relative;
}

.bg-video {
  position: relative;
}

.bg-video video {
  display: block;
  height: 100%;
  width: 100%;
  -o-object-fit: cover;
  object-fit: cover;
  position: absolute;
  top: 0;
  z-index: 0;
  pointer-events: none;
}

/* ==================
          文本
 ==================== */

.text-Abc {
  text-transform: Capitalize;
}

.text-ABC {
  text-transform: Uppercase;
}

.text-abc {
  text-transform: Lowercase;
}

.text-price::before {
  content: "¥";
  font-size: 80%;
  margin-right: 4px;
}

.text-cut {
  text-overflow: ellipsis;
  white-space: nowrap;
  overflow: hidden;
}

.text-bold {
  font-weight: bold;
}

.text-center {
  text-align: center;
}

.text-content {
  line-height: 1.6;
}

.text-left {
  text-align: left;
}

.text-right {
  text-align: right;
}

.text-red,
.line-red,
.lines-red {
  color: var(--red);
}

.text-orange,
.line-orange,
.lines-orange {
  color: var(--orange);
}

.text-yellow,
.line-yellow,
.lines-yellow {
  color: var(--yellow);
}

.text-olive,
.line-olive,
.lines-olive {
  color: var(--olive);
}

.text-green,
.line-green,
.lines-green {
  color: var(--green);
}

.text-cyan,
.line-cyan,
.lines-cyan {
  color: var(--cyan);
}

.text-blue,
.line-blue,
.lines-blue {
  color: var(--blue);
}

.text-purple,
.line-purple,
.lines-purple {
  color: var(--purple);
}

.text-mauve,
.line-mauve,
.lines-mauve {
  color: var(--mauve);
}

.text-pink,
.line-pink,
.lines-pink {
  color: var(--pink);
}

.text-brown,
.line-brown,
.lines-brown {
  color: var(--brown);
}

.text-grey,
.line-grey,
.lines-grey {
  color: var(--grey);
}

.text-gray,
.line-gray,
.lines-gray {
  color: var(--gray);
}

.text-black,
.line-black,
.lines-black {
  color: var(--black);
}

.text-white,
.line-white,
.lines-white {
  color: var(--white);
}
.bdCon {
  margin-top: 0.5rem;
}
.anniu_btn {
  width: 100%;
  padding: 0.2rem;
}
.anniu_btn button {
  background: #0081ff;
  height: 0.4rem;
  border-radius: 5px;
  color: #fff;
  width: 50%;
  margin: 0 auto;
  display: block;
  font-size: 0.12rem;
  max-width: 200px;
}
@media only screen and (min-width: 1400px) {
  #header {
    height: 0.3rem;
  }
  .header {
    height: 0.3rem;
  }
  .headerIn .back {
    font-size: 0.08rem;
  }
  .headerIn .save {
    font-size: 0.08rem;
  }

  .cuIcon-back:before {
    margin-right: 3px;
    font-size: 0.1rem;
  }
  .headerIn h2 {
    font-size: 0.1rem;
    line-height: 0.3rem;
  }
  .bdCon {
    margin-top: 0.3rem;
  }
  .anniu_btn button {
    height: 0.26rem;
    font-size: 0.08rem;
    max-width: 400px;
  }
}
@media screen and (max-width: 641px) {
  #header {
    height: 1rem;
  }
  .header {
    height: 1rem;
  }
  .headerIn .back {
    font-size: 0.3rem;
  }
  .headerIn .save {
    font-size: 0.3rem;
  }
  .cuIcon-back:before {
    margin-right: 3px;
    font-size: 0.3rem;
  }
  .headerIn h2 {
    font-size: 0.32rem;
    line-height: 1rem;
  }
  .bdCon {
    margin-top: 1rem;
  }
  .anniu_btn {
    padding: 0.2rem 5%;
  }
  .anniu_btn button {
    height: 1rem;
    font-size: 0.3rem;
    max-width: 100%;
    width: 100%;
  }
}
</style>

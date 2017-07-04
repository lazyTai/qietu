<template>
  <footer class="footer">
    <div class="foot-con">
      <dl>
        <dt class="foot-ico">
          广州总公司
        </dt>
        <dd class="big-p">
          广州正在互联网有限公司
        </dd>
        <dd>
          广州市天河区沙太路银利街12号E座4008-4012
        </dd>
        <dd>
          售前热线：020-87723646
        </dd>
        <dd>
          售后服务：020-87723377
        </dd>
      </dl>
      <dl>
        <dt class="foot-ico">
          惠州公司
        </dt>
        <dd class="big-p">
          惠州正在互联网有限公司
        </dd>
        <dd>
          惠州仲恺高新区惠风七路7号公园壹号广场1206至1207
        </dd>
      </dl>
      <dl>
        <dt class="foot-ico2">
          正在企业成员
        </dt>
        <dd>
          广州给米科技有限公司
        </dd>
        <dd>
          广州正在互联网有限公司
        </dd>
        <dd>
          广州正在广告传媒有限公司
        </dd>
        <dd>
          广州空杯子信息科技有限公司
        </dd>
        <dd>
          广州正在购物电子商务有限公司
        </dd>
      </dl>
    </div>
    <div class="copy">
      COPYRIGHT : ISTO.NET.CN 粤ICP备11040633号-1
    </div>
  </footer>
</template>
<script>
  export default{
    components: {}
  }
</script>
<style scoped>
  .footer{
    margin-bottom: calc(55 * 2 / 100)rem;
    background: #0e0d10 !important;
    padding: 5% 3% 20% !important;
  }
  .foot-ico {
    background: url(http://www.isto.net.cn/JGsat/Tpl/Mobile/Default/Public/images/foot_1.png) no-repeat left center;
    background-size: contain;
    padding-left: 15px;
  }
  .foot-ico2 {
    background: url(http://www.isto.net.cn/JGsat/Tpl/Mobile/Default/Public/images/foot_2.png) no-repeat left center;
    background-size: contain;
    padding-left: 15px;
  }
  .foot-con dl {
    margin: 0;padding: 0;
    margin-bottom: 20px;
    color: #999;
    line-height: 18px;
  }
  .foot-con dl dt {
    margin: 0;
    font-size: 16px;
    margin-bottom: 10px;
    color: #fff;
  }
  .foot-con dl dd.big-p {
    font-weight: bold;
    font-size: 14px;
  }
  .foot-con dl dd {
    font-size: 12px;
  }

  .copy {
    padding-top: 10px;
    color: #eee;
    border-top: 1px solid #242326;
  }
</style>

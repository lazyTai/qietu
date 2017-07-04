<template>
    <div class="Body33">
      <div class="title">微信开发</div>

      <div class="row">
       <b>微信开发基于微信服务号进行功能开发，</b>
        与常规的H5网页对比它拥有微信5亿用户做数据导向，与APP对比它相当是轻应用，无需安装。基于微信的发展方向，微平台能应用的面及开放的端口尤为广，我们能为企业定制实现更多特属您需要的平台功能。
      </div>

      <div class="bigImage">
        <img src="http://www.isto.net.cn/Uploads/201609/57c7c10a26f81.png" alt="">
      </div>
    </div>
</template>
<script>
    export default{
        components: {}
    }
</script>
<style scoped>
  .Body33{color: #fff}
  .title{
    width: calc(200*2/100)rem;
    height: calc(65*2/100)rem;;
    line-height: calc(65*2/100)rem;
    text-align: center;
  @mixin font-size 20;
    background: url("http://www.isto.net.cn/JGsat/Tpl/Mobile/Default/Public/images/pr.png");
    background-size: 100%;
    background-repeat:no-repeat;
    margin: 0 auto;
  }

  .row{
    margin-top: 20px;
    display: flex;
    justify-content: space-around;
  }
  .row img{size: calc(60*2/100)rem;}
  .row p{
  @mixin font-size 15;
    text-align: center;padding: 0;margin: 0}

  .bigImage{width:  calc(300*2/100)rem;margin-top: 50px;}
  .bigImage img{size: 100%}
</style>

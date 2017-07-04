<template>
    <div class="Body31">
      <div class="title">网站定制</div>

      <div class="row">
        <div class="img">
          <img src="http://www.isto.net.cn/JGsat/Tpl/Mobile/Default/Public/img/yw1.png" alt="">
          <div>
            <p>专属的</p>
            <p>页面风格</p>
          </div>
        </div>
        <div class="img">
          <img src="http://www.isto.net.cn/JGsat/Tpl/Mobile/Default/Public/img/yw2.png" alt="">
          <div>
            <p>特定的</p>
            <p>用户体验</p>
          </div>
        </div>
        <div class="img">
          <img src="http://www.isto.net.cn/JGsat/Tpl/Mobile/Default/Public/img/yw3.png" alt="">
          <div>
            <p>个性的</p>
            <p>前端效果</p>
          </div>
        </div>
        <div class="img">
          <img src="http://www.isto.net.cn/JGsat/Tpl/Mobile/Default/Public/img/yw4.png" alt="">
          <div>
            <p>人性化</p>
            <p>后台管理</p>
          </div>
        </div>
      </div>

      <div class="bigImage">
        <img src="http://www.isto.net.cn/Uploads/201609/57c7c0cea361f.png" alt="">
      </div>
    </div>
</template>
<script>
    export default{
        components: {}
    }
</script>
<style scoped>
  .Body31{color: #fff}
  .title{
    width: 200px;
    height: 65px;
    line-height: 65px;
    text-align: center;font-size: 24px;
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
  .row p{font-size: 15px;text-align: center;padding: 0;margin: 0}

  .bigImage{width: 400px;margin-top: 50px}
  .bigImage img{size: 100%}
</style>

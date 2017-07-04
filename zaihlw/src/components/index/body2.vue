<template>
  <div class="body2">
    <div class="row row1">
      <div class="q q1">
        <div class="img">
          <img src="http://www.isto.net.cn/Uploads/201609/57c7a263c9601.png" alt="">
        </div>
        <span class="font">网站建设</span>
      </div>

      <div class="q q2">
        <div class="img">
          <img src="http://www.isto.net.cn/Uploads/201609/57cfacab5b575.png" alt="">
        </div>
        <span>微信开发</span>
      </div>
      <div class="q q3">
        <div class="img">
          <img src="http://www.isto.net.cn/Uploads/201609/57cfacbd3d087.png" alt="">
        </div>
        <span>app开发</span>
      </div>
      <div class="q q4">
        <div class="img">
          <img src="http://www.isto.net.cn/Uploads/201609/57cfaccb733f2.png" alt="">
        </div>
        <span>销售推广</span>
      </div>
    </div>

    <div class="row2">
      <div class="font">成功的平台</div>
      <div class="font">一定是精确定位结合有效的品牌销售，</div>
      <div class="font">这就是我们的信条</div>
    </div>
  </div>
</template>
<script>
  export default{
    components: {}
  }
</script>
<style scoped>
  .body2 {
    margin-top: calc(20 * 2 / 100)rem;
  }

  .row1 {
    margin-bottom: calc(20 * 2 / 100)rem;
  }

  .row1 .q .img{
    size: calc(48 * 2 / 100)rem;
  }

  .row1 .q img {
    size: 100%
  }

  .row1 {
    display: flex;
    justify-content: space-around
  }

  .row2{height: calc(100*2/100)rem;background: #eee;
    padding-top: calc(23*2/100)rem;box-sizing: border-box;
  }
  .font{text-align: center;font-size: 18px}
</style>

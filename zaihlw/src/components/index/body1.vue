<template>
  <div class="body1">
    <div class="swiper-container swiper-container1 ">
      <div class="swiper-wrapper">
        <div class="swiper-slide blue-slide">
          <img src="http://www.isto.net.cn/Uploads/201609/57c79f837f20e.jpg" alt="">
        </div>
        <div class="swiper-slide red-slide">
          <img src="http://www.isto.net.cn/Uploads/201609/57d13de8b8aea.jpg" alt="">
        </div>
        <div class="swiper-slide orange-slide">
          <img src="http://www.isto.net.cn/Uploads/201609/57d13df8ce154.jpg" alt="">
        </div>
        <div class="swiper-slide orange-slide">
          <img src="http://www.isto.net.cn/Uploads/201609/57d13e0894f9b.jpg" alt="">
        </div>
      </div>


      <!-- 如果需要分页器 -->
      <div class="swiper-pagination swiper-pagination1"></div>
    </div>
  </div>
</template>
<script>
  export default{
    components: {},
    mounted: function () {
      var mySwiper = new Swiper('.swiper-container1', {
          pagination:'.swiper-pagination1'
      });
    }
  }
</script>
<style scoped>
  .body1 {
    width: 100%;
    height: 100%;
  }

  .swiper-container {
    width: 100%;
    height: 100%;
  }

  .swiper-wrapper {
    size: 100%;
  }

  .swiper-slide {
    width: 100%;
    height: 100%;
  }

  .swiper-slide img {
    size: 100%
  }
</style>

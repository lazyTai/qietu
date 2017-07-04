<template>
  <div class="body3">
    <div class="bg bg-blur"></div>
    <div class="content">
      <div class="swiper-container swiper-container2">
        <div class="swiper-wrapper">
          <div class="swiper-slide">
            <Body31></Body31>
          </div>
          <div class="swiper-slide">
            <Body32></Body32>
          </div>
          <div class="swiper-slide">
            <Body33></Body33>
          </div>
        </div>
        <!-- Add Navigation -->
        <div class="swiper-button-prev swiper-button-white"></div>
        <div class="swiper-button-next swiper-button-white"></div>
      </div>
    </div>

    <div class="clear"></div>
  </div>
</template>
<script>
  import Body31 from './body3-1.vue'
  import Body32 from './body3-2.vue'
  import Body33 from './body3-3.vue'
  export default{
    components: {Body31,Body32,Body33},
    mounted:function () {
      var swiper = new Swiper('.swiper-container2', {
        pagination: '.swiper-pagination2',
        effect: 'cube',
        grabCursor: true,
        cube: {
//          shadow: true,
//          slideShadows: true,
//          shadowOffset: 20,
//          shadowScale: 0.94
        },
        nextButton: '.swiper-button-next',
        prevButton: '.swiper-button-prev',
      });
    }
  }
</script>
<style scoped>
  .clear{ clear:both}
  .body3{
    width: 100%;
  }
  .bg {
    background: url("http://www.isto.net.cn/JGsat/Tpl/Mobile/Default/Public/images/bg1.jpg")  no-repeat #eee;;
    height:600px;
    text-align: center;
    line-height: 600px;
  }
  .bg-blur {
    float: left;
    width: 100%;
    background-repeat: no-repeat;
    background-size: 100%;
  }
  .content{position: absolute;width: 100%}


  .swiper-container {
    width: 100%;
    height: calc(420*2/100)rem;

  }
  .swiper-slide {

  }
  .swiper-button-white{

  }
</style>

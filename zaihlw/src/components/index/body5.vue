<template>
    <div class="body5">
      <div class="title">
        <p>互联网改变了世界，</p>
        <p>企业的互联网改革势在必行！</p>
      </div>

      <ul>
        <li class="bg-g">
          <div class="img">
            <img src="http://www.isto.net.cn/Uploads/201607/5799db9695f4b.png" alt="">
          </div>
          <div>
            <p>企业网站</p>
            <p>解决方案</p>
          </div>
        </li>

        <li class="bg-b">
          <div class="img">
            <img src="http://www.isto.net.cn/Uploads/201607/578da369c2391.png" alt="">
          </div>
          <div>
            <p>品牌网站</p>
            <p>解决方案</p>
          </div>
        </li>


        <li class="bg-b">
          <div class="img">
            <img src="http://www.isto.net.cn/Uploads/201607/5799dbd018907.png" alt="">
          </div>
          <div>
            <p>企业网站</p>
            <p>解决方案</p>
          </div>
        </li>

        <li class="bg-o">
          <div class="img">
            <img src="http://www.isto.net.cn/Uploads/201607/5799dc01bbebe.png" alt="">
          </div>
          <div>
            <p>品牌网站</p>
            <p>解决方案</p>
          </div>
        </li>


        <li class="bg-grey">
          <div class="img">
            <img src="http://www.isto.net.cn/Uploads/201607/5799dc2cc41fc.png" alt="">
          </div>
          <div>
            <p>企业网站</p>
            <p>解决方案</p>
          </div>
        </li>

        <li class="bg-g">
          <div class="img">
            <img src="http://www.isto.net.cn/Uploads/201607/5799dc602efb3.png" alt="">
          </div>
          <div>
            <p>品牌网站</p>
            <p>解决方案</p>
          </div>
        </li>
      </ul>
    </div>
</template>
<script>
    export default{
        components: {}
    }
</script>
<style scoped>
    .body5{ background: #eee;
      padding-top: calc(40 * 2 / 100)rem;
    }
    .title{
      @mixin font-size 20;
      padding-bottom:40px;text-align: center;
      p{padding: 0;margin: 0}
    }
    .clear:after{
      content: "";height:1px;clear: both;width: 100%;
    }
    ul{
      box-sizing: border-box;
      justify-content: space-around;padding: 0;
      width: 100%;list-style: none;height: auto;display: flex;
      margin: 0;flex-wrap: wrap}
    ul li{
      padding: 10px;
      box-sizing: border-box;
      color: #eee;display: flex;
      width:  calc(144 * 2 / 100)rem;
      margin-bottom: 20px;
    }

    ul li .img{margin: 10px;size:calc(32 * 2 / 100)rem;
      img{size:100%}}
    ul li p{
      @mixin font-size 15;
      margin: 7px}

    .bg-g{background: lightskyblue}
    .bg-b{background: #2FDB25}
    .bg-o{background: orange}
    .bg-grey{background: #A2A2BA}
</style>

<template>
  <div class="body4">
    <div class="row-title">
      <div class="title">正在案例</div>
      <p class="miaoshu1">文化传承源动力、市场传播影响力、品牌传递思想力</p>
    </div>



    <div class="content">
      <div class="row">
        <div class="row1">
          <img src="http://www.isto.net.cn/Uploads/201608/57abd63dac41e.jpg" alt="">
          <div class="row-title1">
            <div class="title">创维</div>
            <div class="miaoshu">具有创新\"硅谷\"之称的深圳高新...</div>
          </div>
        </div>
        <div class="row1">
          <img src="http://www.isto.net.cn/Uploads/201608/57abd5930f3ec.jpg" alt="">
          <div class="row-title1">
            <div class="title">慧投广告</div>
            <div class="miaoshu">致力于中国最专业的效果类互联网...</div>
          </div>
        </div>
      </div>

      <div class="row">
        <div class="row1">
          <img src="http://www.isto.net.cn/Uploads/201608/57abd5815849c.jpg" alt="">
          <div class="row-title1">
            <div class="title">俏妃</div>
            <div class="miaoshu">致力于科学与美丽结合的研究事业</div>
          </div>
        </div>
        <div class="row1">
          <img src="http://www.isto.net.cn/Uploads/201608/57abd55a9880b.jpg" alt="">
          <div class="row-title1">
            <div class="title">广州体育局</div>
            <div class="miaoshu">实现建设“幸福广州 健康广州”...</div>
          </div>
        </div>
      </div>

      <div class="row">
        <div class="row1">
          <img src="http://www.isto.net.cn/Uploads/201608/57abd53aa6ee7.jpg" alt="">
          <div class="row-title1">
            <div class="title">友基</div>
            <div class="miaoshu">研究与开发新高技术产品</div>
          </div>
        </div>
        <div class="row1">
          <img src="http://www.isto.net.cn/Uploads/201608/57abd56b0b072.jpg" alt="">
          <div class="row-title1">
            <div class="title">索尼</div>
            <div class="miaoshu">结合了待机设计技术与超强的娱乐...</div>
          </div>
        </div>
      </div>


      <div class="row">
        <div class="row1">
          <img src="http://www.isto.net.cn/Uploads/201608/57abd4e4897ef.jpg" alt="">
          <div class="row-title1">
            <div class="title">沙巴哇</div>
            <div class="miaoshu">沙巴哇 SABAVA致力于果蔬干制作</div>
          </div>
        </div>
        <div class="row1">
          <img src="http://www.isto.net.cn/Uploads/201608/57abd547ebf61.jpg" alt="">
          <div class="row-title1">
            <div class="title">中国南方电网</div>
            <div class="miaoshu">广东电网有限责任公司电力科学研...</div>
          </div>
        </div>
      </div>
    </div>


    <a href="readmore" class="readmore"></a>
  </div>
</template>
<script>
  export default{
    components: {}
  }
</script>
<style scoped>
  .readmore{
    width: calc(135 * 2 / 100)rem;
    height:  calc(30 * 2 / 100)rem;;;
    display: block;
    margin: 10px auto;
    background: url(http://www.isto.net.cn/JGsat/Tpl/Mobile/Default/Public/images/more.png) no-repeat;
    background-size: contain;
  }
  .row-title1 .miaoshu{color: #d3d3d3;font-size: 13px;
    width: calc(144 * 2 / 100)rem;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }
  .row-title1 .title{font-size: 15px}
  .row-title1{padding: 5px;}
  .row .row1 img{width: calc(144 * 2 / 100)rem;height: calc(91 * 2 / 100)rem;}
  .content .row{display: flex;justify-content: space-between;
    padding-left:calc(13 * 2 / 100)rem;
  }
  .body4 {
    background: #fff;
    padding-top: calc(40 * 2 / 100)rem;
  }
  .row-title{margin-bottom:  calc(20 * 2 / 100)rem;}
  .row-title .title{
    font-size: 20px;text-align: center;
  }
  .row-title .miaoshu1{text-align: center;font-size: 15px;padding: 0;margin: 0}
</style>

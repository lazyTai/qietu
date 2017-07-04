<template>
  <div class="tab">
    <img class="logo" src="http://www.isto.net.cn/Uploads/201612/58478c835cb1c.png">
    <div class="q2">
      <img src="http://www.isto.net.cn//JGsat/Tpl/Mobile/Default/Public/images/tel.png" alt="">
    </div>
    <div class="q3">
      <img src="../../../static/1.png" alt="">
    </div>
  </div>
</template>
<script>
  export default{
    components: {}
  }
</script>
<style scoped>
  .tab {
    z-index: 100;
    background: #fff;
    position: fixed;
    top:0;
    width: 100%;
    padding: calc(11*2/100)rem calc(20*2/100)rem calc(15*2/100)rem calc(15*2/100)rem;;
    height: calc(55*2/100)rem;
    box-sizing: border-box;
    display: flex;
    border: 1px solid #eee;
  }

  .logo {
    width: calc(212*2/100)rem;
    height: calc(33*2/100)rem;
    margin-right:  calc(15*2/100)rem;
  }
  .q2,.q3{
    position: relative;
    size: calc(30*2/100)rem;
    img{
      position: absolute;
      size: 100%;
    }
  }
  /*.q3{margin-left: calc(30*2/100)rem;}*/
</style>

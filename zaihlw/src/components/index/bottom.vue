<template>
  <div class="buttom">
    <div class="q1 font">在线服务</div>
    <div class="q2 font">案例</div>
    <div class="q3 font">项目孵化</div>
    <div class="q4 font">正在互联</div>
  </div>
</template>
<script>
  export default{
    components: {}
  }
</script>
<style scoped>
  .buttom {
    width: 100%;
    position: fixed;
    bottom: 0;
    z-index: 200;
    height: calc(40*2/100)rem;
    background: #EF3333;
    display: flex;
  }
  .buttom .font{
    font-size: calc(15*2/100)rem;flex: 1;color: #fff;
    align-self: center;
    text-align: center}
</style>

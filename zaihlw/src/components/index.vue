<template>
  <div class="index">
    <Tab></Tab>
    <Body1></Body1>
    <Body2></Body2>
    <Body3></Body3>
    <Body4></Body4>
    <Body5></Body5>
    <Footer1></Footer1>
    <Bottom></Bottom>
  </div>
</template>
<script>
  import Tab from './index/tab.vue'
  import Body1 from './index/body1.vue'
  import Body2 from './index/body2.vue'
  import Body3 from './index/body3.vue'
  import Body4 from './index/body4.vue'
  import Body5 from './index/body5.vue'
  import Footer1 from './index/footer.vue'
  import Bottom from './index/bottom.vue'
  export default{
    components: {Tab, Body1,Bottom,Body2,Body3,Body4,Body5,Footer1}
  }
</script>
<style scoped>
</style>

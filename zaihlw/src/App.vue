<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
  function viewport() {
    const win = window;
    let dpr = win.devicePixelRatio || 1;
    document.documentElement.setAttribute('data-dpr',Math.round(dpr))
  }
  viewport()
  export default {
    name: 'app'
  }
</script>

<style>
  html, body {
    padding: 0;
    margin: 0;
    width: 100%;
    height: 100%;
  }
  @define-mixin font-size $px{
    font-size: calc($px)px;
    [data-dpr='2'] & {font-size: calc($px*2)px}
    [data-dpr='3'] & {font-size: calc($px*3)px}
  }
  div{@mixin font-size 12}

</style>

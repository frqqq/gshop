<template>
  <div id="app">
      <router-view></router-view>
      <footerGuide v-show="$route.meta.showFooter"></footerGuide>
  </div>
</template>

<script>
 import FooterGuide from './components/FooterGuide/FooterGuide.vue'
  export default {
    components:{
      FooterGuide
    }
  }
</script>

<style lang="stylus" rel="stylesheet/stylus">
  #app
    width 100%
    height 100%
    background #f5f5f5

</style>



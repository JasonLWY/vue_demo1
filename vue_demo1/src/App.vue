<template>
  <div id="app">
    <m-header></m-header>
    <tap></tap>
    <keep-alive>
      <router-view></router-view>
    </keep-alive>
  </div>
</template>

<script type="text/ecmascript-6">
  import MHeader from 'components/m-header/m-header'
  import Tap from 'components/tap/tap'
export default {
  components:{
      MHeader,
      Tap
  }
}
</script>
<style scoped lang="stylus" ref="stylesheet/stylus">

</style>

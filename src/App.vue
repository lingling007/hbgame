<template>
  <div id="app">
    <Tabbar></Tabbar>
    <router-view></router-view>
  </div>
</template>

<script type="text/ecmascript-6">
import Tabbar from '@/components/Tabbar/Tabbar.vue';
export default {
  components : {
    Tabbar
  }
};
</script>

<style lang="stylus" rel="stylesheet/stylus">

</style>

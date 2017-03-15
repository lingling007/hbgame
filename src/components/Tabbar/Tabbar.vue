<template>
 <div class="Tabbar">
   <mt-tabbar v-model="selected">
     <mt-tab-item id="tab1">
       <img slot="icon" src="homepage-2.png">
       tab1
     </mt-tab-item>
     <mt-tab-item id="tab2">
       <img slot="icon" src="categorypage-1.png">
       tab2
     </mt-tab-item>
     <mt-tab-item id="tab3">
       <img slot="icon" src="gamedispage-1.png">
       tab3
     </mt-tab-item>
     <mt-tab-item id="tab4">
       <img slot="icon" src="userpage-1.png">
       tab4
     </mt-tab-item>
   </mt-tabbar>
   <img src="img/userpage-1.png" alt="">
   <img src="../../assets/logo.png" alt="">
 </div>
</template>
<script type="text/ecmascript-6">
  import Vue from 'vue';
  import { Tabbar, TabItem } from 'mint-ui';
  Vue.component(Tabbar.name, Tabbar);
  Vue.component(TabItem.name, TabItem);
  export default {

  };
</script>
<style lang="stylus" rel="stylesheet/stylus">

</style>

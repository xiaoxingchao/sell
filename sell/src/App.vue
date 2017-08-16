<template>
  <div id="app">
    <Header></Header>
    <!-- <div class="header">
      i am header;
    </div> -->
    <div class="tab">
      i am tab;
    </div>
    <div class="content">
      i am content;

    </div>

    <router-view></router-view>
  </div>
</template>

<script>
  import Header from './components/header/header.vue'
  export default {
    components:{
      Header
    }
  }
</script>

<style>

</style>

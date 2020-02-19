<template>
  <div id="app">
    <NavBar />  
    <div class="container">
      <router-view />
    </div>
  </div>
</template>
<script>
import NavBar from "@/components/NavBar.vue"
import Vue from 'vue'
export default Vue.extend({
  components:{
    NavBar
  }  
  
})
</script>
<style lang="scss">
/* ~ - означает путь до директории node_modules */
@import "~materialize-css/dist/css/materialize.min.css";
</style>

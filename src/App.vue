<template>
  <div id="app" class="#fffde7 yellow lighten-5" style="height: 100vh">
    <Navbar />
    <div class="container">
      <router-view />
    </div>
  </div>
</template>

<script>
  import Navbar from "./components/Navbar";
  
  export default {
    components: {Navbar}
  }
</script>

<style lang="scss">
  @import "~materialize-css/dist/css/materialize.min.css";
</style>

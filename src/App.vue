<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>

import CommonData from "@/tools/common-data";

export default {
  created() {
    CommonData.root_vue = this
  }
}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>

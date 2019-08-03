<template>
  <div id="app" class="app">
    <img src="./assets/logo.png">
    <span class= "text">abfw</span>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="scss" scoped>
.app {
  color: red;
  .text {
    font-size: 40px;
  }
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  // color: #2c3e50;
  margin-top: 60px;
}
</style>

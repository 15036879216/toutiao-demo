<template>
  <div id="app">
    <h1>黑马头条</h1>
    <router-view />
  </div>
</template>
<script>
export default {
  name: 'App',
  data() {}
}
</script>

<style lang="less">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>

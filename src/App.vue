<template>
  <div id="app">
<!--    <img src="./assets/logo.png">-->
    <img src="http://bpic.588ku.com/element_origin_min_pic/16/10/30/6c2faa2154975a988d58dde09ebfe141.jpg" style="width: 200px;
    height: 200px;
    margin-bottom: 10px;">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

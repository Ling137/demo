<template>
  <div id="app">
    <img alt="Vue logo" src="http://p9.qhimg.com/bdm/340_210_0/t01feb5393e822c1fca.jpg">
    <!-- <img alt="Vue logo" src="http://p5.qhimg.com/bdm/340_210_0/t013c1ac7dd36a3e750.jpg"> -->
    <HelloWorld msg="Welcome to 2020 Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
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

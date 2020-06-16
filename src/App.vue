<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <h1>csvfilereader</h1>
    <!--<HelloWorld msg="vueの世界にようこそ！"> -->
    <csvfilereader></csvfilereader>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import csvfilereader from './components/csvfilereader.vue'

export default {
  name: 'App',
  components: {
    //HelloWorld,
    csvfilereader
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
  margin-top: 60px;
}
</style>

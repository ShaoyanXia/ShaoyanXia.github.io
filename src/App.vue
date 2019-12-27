<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <mainpage msg="欢迎来到夏绍炎的个人Blog"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import mainpage from './components/main_page.vue'
export default {
  name: 'app',
  components: {
    HelloWorld,
	mainpage
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

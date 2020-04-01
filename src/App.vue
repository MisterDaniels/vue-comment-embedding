<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Link :data="{ url: 'https://www.youtube.com/embed/AroqCD2Kpls' }" :type="'video'" />
    <Link :data="{ url: 'https://bobo.muzli.space/1559546512834-1558440610748-800x600.gif', alt:'Imagem legal' }" :type="'image'" />
  </div>
</template>

<script>
import HelloWorld from './components/hello-world/HelloWorld.vue'
import Link from './components/link';

export default {
  name: 'App',
  components: {
    HelloWorld,
    Link
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

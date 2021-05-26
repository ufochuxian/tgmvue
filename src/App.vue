<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>

    <my-component>这是自定义组件</my-component>

    <HoverComp message="这是一个hover的组件"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HoverComp from "./components/HoverComp.vue"
export default {
  name: 'App',
  components: {
    HoverComp,
    HelloWorld,
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

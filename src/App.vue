<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <van-button type="success">按钮</van-button>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
// import
// { Button } from 'vant-green'


export default {
  name: 'App',
  components: {
    HelloWorld,
    // [Button.name]: Button
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

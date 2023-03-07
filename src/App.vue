<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App" />
  <PrivateKeyConverter />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import PrivateKeyConverter from './components/PrivateKeyConverter.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    PrivateKeyConverter
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

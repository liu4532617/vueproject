<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <main msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import main from './components/main.vue'

export default {
  name: 'App',
  components: {
    main
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

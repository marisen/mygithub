<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
    <TestVue/>
  </div>
</template>



<script>
import TestVue from './components/Test.vue'

export default {
  name: 'App',
  components: {
    TestVue
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

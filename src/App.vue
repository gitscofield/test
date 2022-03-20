<template>
  <div id="app">
    <img src="./assets/logo.png">
    <Tinder/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import Tinder  from './components/vue-tinder/Tinder.vue'

export default {
  name: 'App',
  components: {
    Tinder
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

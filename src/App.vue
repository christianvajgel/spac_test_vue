<template>
  <div id="app">
<!--    <img alt="Vue logo" src="./assets/logo.png">-->
    <Home/>
  </div>
</template>

<script>
import Home from './components/Home.vue'

export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>
    #app {
      /*font-family: Cabin, Helvetica, Arial, sans-serif;*/
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
      text-align: center;
      color: #E2E2E2;
      /*margin-top: 40px;*/
      background-color: #181818;
    }
</style>

<template>
  <div id="app">
      <Home/>
      <CometSearch/>
<!--    <img alt="Vue logo" src="./assets/logo.png">-->

  </div>
</template>

<script>
import Home from './components/Home.vue'
import CometSearch from "@/components/CometSearch";

export default {
  name: 'App',
  components: {
      CometSearch,
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
      /*background-color: #0e0e0e;*/
    }
</style>

<template>
  <img class="m-auto" alt="Vue logo" src="./assets/demtrodev-logo.png">
  <HelloWorld class="container" msg="Welcome to Your Vue.js App"/>
</template>

<script>

import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@500;700&display=swap');

*{
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

#app {
  
  font-family: 'Plus Jakarta Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
</style>

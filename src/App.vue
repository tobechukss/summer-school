<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>


  </div>
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

@import url('https://fonts.googleapis.com/css2?family=Noto+Sans&display=swap');

#app {
  font-family: 'Noto Sans', sans-serif;
  /* -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0;
  padding: 0; */
}
html, body {
  margin: 0;
  padding: 0;
  width: 100%;
  overflow-x: none;
}


</style>

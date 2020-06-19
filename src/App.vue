<template>
  <div id="app">
    <HelloWorld msg="Coming soon..."/>
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
html, body {
  background-color: #333;
  box-shadow: inset 0 0 5rem rgba(0, 0, 0, .5);
  color: white;
}
h1 {
  background-color: #333;
}
#app {
  margin-top: 35%;
  height: 100%;
}
</style>
<template>
  <div id="app" class="d-flex flex-column">
    <Home msg="Coming soon..."/>
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
body {
  text-align: center!important;
}
#app {
  max-width: 42em;
  margin-left: auto!important;
  margin-right: auto!important;
  padding: 1rem!important;
  height: 100%!important;
  background-color: black;
}
</style>
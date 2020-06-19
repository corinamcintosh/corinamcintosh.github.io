<template>
  <v-app>
    <v-content>
      <Home msg="Coming soon..." />
    </v-content>
  </v-app>
</template>

<script>
import Home from './components/Home';

export default {
  name: 'App',

  components: {
    Home,
  },

  data: () => ({
    //
  }),
};
</script>

<style>
body {
  text-align: center!important;
  display: flex;
  -webkit-box-pack: center;
  justify-content: center;
  color: #fff!important;
  text-shadow: 0 0.05rem 0.1rem rgba(0, 0, 0, .5);
  box-shadow: inset 0 0 5rem rgba(0, 0, 0, .5);
  height: 100%;
  background-color: #333!important;
}
#app {
  background-color: transparent!important;
}
</style>
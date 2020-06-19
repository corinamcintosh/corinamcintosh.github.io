<template>
  <div class="temporary d-flex flex-column">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<style>
.temporary {
  background-color: transparent!important;
  max-width: 42em;
  margin-left: auto!important;
  margin-right: auto!important;
  padding: 1rem!important;
  color: #fff!important;
  height: 100%!important;
  padding-top:55%!important;
}
</style>
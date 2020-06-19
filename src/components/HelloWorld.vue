<template>
  <div class="hello text-center align-middle">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style>
.hello {
  padding: 0px 1.5rem;
}
</style>
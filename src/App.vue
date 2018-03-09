<template>
  <div id="app">
    <p>{{ message }}</p>
    <input v-model="message">
  </div>
</template>

<script>
  new Vue {
    el: '#app',
    data () {
      return {
        message: 'Hello!'
      }
    }
  }
</script>

<style>

</style>

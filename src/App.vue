<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Giphy />
  </div>
</template>

<script>
import Giphy from './components/Giphy.vue'

export default {
  name: 'App',
  components: {
    Giphy
  }
}
</script>

<style>
</style>

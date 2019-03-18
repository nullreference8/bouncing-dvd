<template>
  <div id="app">
    <Dvd/>
  </div>
</template>

<script>
import Dvd from './components/Dvd.vue'

export default {
  name: 'app',
  components: {
    Dvd
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #2c3e50;
  min-height: 100vh;
  width: 100%
}
</style>

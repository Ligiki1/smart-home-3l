<template>
  <div id="app">
   <webcam />
   <span>Door Detection 3ML {{ msg }}</span>
  </div>
</template>

<script>
import webcam from './components/webcam.vue'

export default {
  name: 'App',
  components: {
    webcam
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

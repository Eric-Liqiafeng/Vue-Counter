<template>
  <div id="app">
    <Father msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import Father from './components/Father.vue'

export default {
  name: 'app',
  components: {
    Father
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

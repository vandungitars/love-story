<template>
  <div id="app">
    <LoveStory msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import LoveStory from './components/LoveStory.vue'

export default {
  name: 'app',
  components: {
      LoveStory
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

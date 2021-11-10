<template>
  <div id="app">
    <h1>La mia prima app con Vue CLI!</h1>
    
    <jumbotron/>
  </div>
</template>

<script>
import jumbotron from"./components/jumbotron.vue"

export default {
  name: 'App',
  components: {
    jumbotron
  }
}
</script>





<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

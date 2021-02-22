<template>
  <div id="app">
    <Exemplo></Exemplo>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Exemplo from './components/Exemplo.vue'

export default {
  name: 'App',
  components: {
    Exemplo
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

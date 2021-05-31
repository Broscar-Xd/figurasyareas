<template>

  <div id="app" class="card">
    <Cabecera></Cabecera>
    <div class="card-body">
    <Figuras></Figuras>
    </div>

  </div>
</template>

<script>

import Cabecera from './components/Cabecera.vue'
import Figuras from './components/Figuras.vue'

export default {
  name: 'App',
  components: {
    Cabecera,
    Figuras
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

<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <EjercicioUno />
  <EjercicioDos />
  <EjercicioTres />
</template>

<script>

import EjercicioUno from "./components/ejercicio-1.vue";
import EjercicioDos from "./components/ejercicioDos.vue";
import EjercicioTres from "./components/ejercicioTres.vue";


export default {
  name: 'App',
  components: {
    EjercicioUno,
    EjercicioDos,
    EjercicioTres
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

<template>
  <h1>Input</h1>
  <label>Ingresa tu nombre: </label>
  <input type="text" v-model="name" />
  <p>Mi nombre es: {{ name }}</p>
</template>

<script>
export default {
  name: "myComponent",
  data() {
    return {
      name: "",
    };
  },
};
</script>

<style></style>

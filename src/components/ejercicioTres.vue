<template>
  <label v-bind:style="styleObject">Escribe el color al cual me quieres cambiar: </label>
  <input type="text" v-model="styleObject.color" />
  <p>El color que seleccionaste es: {{ styleObject.color }}</p>
</template>

<script>
export default {
  name: "myComponent",
  data() {
    return {
      styleObject: {
        color: "red",
        fontSize: "25px",
      },
    };
  },
};
</script>

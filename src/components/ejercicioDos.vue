<template>
  <h1>Suma de dos números:</h1>
  <label>Ingresa el primer número: </label>
  <input type="number" v-model.number="numberOne" />
  <label> Ingresa el segundo número: </label>
  <input type="number" v-model.number="numberTwo" />
  <h2>El resultado de los dos números es:</h2>
  <h1>{{ numberOne + numberTwo }}</h1>
</template>

<script>
export default {
  name: "sumNumbers",
  data() {
    return {
      numberOne: 0,
      numberTwo: 0,
      sum: 0,
    };
  },
};
</script>

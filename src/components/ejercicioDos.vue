<template>
  <h1>Suma de dos números:</h1>
  <label>Ingresa el primer número: </label>
  <input type="number" v-model="numberOne" />
  <label> Ingresa el segundo número: </label>
  <input type="number" v-model="numberTwo" />
  <h2>El resultado de los dos números es:</h2>
  <h1>{{ parseInt(numberOne) + parseInt(numberTwo) }}</h1>
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

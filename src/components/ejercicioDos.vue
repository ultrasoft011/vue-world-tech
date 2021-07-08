<template>
    <h1>Suma de dos números: </h1>
    <label>Ingresa el primer número: </label>
    <input type="number" v-model='a'>   
    <label> Ingresa el segundo número: </label> 
    <input type="number" v-model='b'>
    <h2>El resultado de los dos números es: </h2>
    <h1>{{parseInt(a) + parseInt(b)}}</h1>

</template>


<script>
export default {
    name: 'sumNumbers',
    data() {
        return {
            a: 0,
            b: 0,
            c: 0,
        }
    }
}
</script>

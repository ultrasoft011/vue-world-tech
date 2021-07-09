<!-- Crear un componente donde vamos a recorrer un arreglo este debe tener Array
[] con el siguiente objeto este debe tener este objeto { nombre: “”, Apellido:
“”, Activo: (True/False) } 10 veces , dentro de este componente se debe mostrar
solo las personas que están activas. -->

<template>
  <h1>Lista de personas activas:</h1>
  <ul id="example-1">
    <li v-for="item in items" :key="item.nombre">
        {{ console.log (items.activo)}}
      <div v-if="items.activo === 'true'">
        {{ console.log (items.activo)}}
        {{ item.nombre }}
        {{ item.apellido }}
      </div>
    </li>
  </ul>
</template>

<script>
export default {
  name: "persons",
  data() {
    return {
      items: [
        {
          nombre: "Andres",
          apellido: "Ballesteros",
          activo: 'true',
        },
        {
          nombre: "Mabel",
          apellido: "Villada",
          activo: true,
        },
        {
          nombre: "Yuli",
          apellido: "Henao",
          activo: true,
        },
        {
          nombre: "Carlos",
          apellido: "Grisales",
          activo: true,
        },
        {
          nombre: "Miguel Angel",
          apellido: "RC",
          activo: true,
        },
        {
          nombre: "Rafael",
          apellido: "Arango",
          activo: true,
        },
        {
          nombre: "Ana",
          apellido: "Fernandez",
          activo: true,
        },
        {
          nombre: "Julia",
          apellido: "Camacho",
          activo: true,
        },
        {
          nombre: "Lady",
          apellido: "Red",
          activo: true,
        },
        {
          nombre: "Pablo",
          apellido: "Karmon",
          activo: true,
        },
      ],
    };
  },
};
</script>

<style></style>

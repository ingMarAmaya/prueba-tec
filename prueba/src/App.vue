<script setup>
  import encabezado from './components/header.vue';
  import buscador from './components/buscador.vue';
  import tarjetas from './components/tarjetas.vue';
</script>

<template>
  <div>
    <encabezado></encabezado>
    <buscador></buscador>
  </div>
  <div class="clearFix"></div>
  <div class="tarjetas">
    <tarjeta></tarjeta>
  </div>
</template>

<style>
  *{
    margin: 0px;
    padding: 0px;
  }
</style>

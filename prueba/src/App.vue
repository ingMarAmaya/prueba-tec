<script setup>
  import encabezado from './components/header.vue';
  import buscador from './components/buscador.vue';
  import tarjetas from './components/tarjetas.vue';
import Header from './components/header.vue';
</script>

<template>
  <div>
    <Header></Header>
    <buscador></buscador>
    <tarjetas></tarjetas>
    <tarjetas></tarjetas>
    <tarjetas></tarjetas>
  </div>
  <div class="clearFix"></div>
</template>

<style>
  *{
    margin: 0px;
    padding: 0px;
    text-decoration: none;
  }
  body{
    background: url(./img/fondo.jpg);
    background-size: cover;
  }
</style>

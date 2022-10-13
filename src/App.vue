<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <h4 class="text-center">Julia Rodrigues</h4>
    <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/sobre">Sobre</RouterLink>
      <RouterLink to="/contato">Contato</RouterLink>
    </nav>
  </header>

  <main>
    <RouterView />
  </main>
</template>

<style>
    a{
      color: black
    }

</style>
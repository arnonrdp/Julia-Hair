<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <h1 class="text-center">Salão da Júlia</h1>
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

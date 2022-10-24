<template>
  <TheHeader />

  <main>
    <RouterView />
  </main>
</template>

<script setup>
import { RouterView } from 'vue-router'
import TheHeader from './components/TheHeader.vue'
</script>

<style>
a {
  color: black;
  font-size: 2rem;
  text-decoration: none;
}
</style>

<template>
  <header class="flex justify-evenly">
    <RouterLink to="/">
      <h4 class="text-center">JR</h4>
    </RouterLink>
    <nav class="q-gutter-x-md">
      <RouterLink to="/sobre">
        <q-icon name="person">
          <q-tooltip>Sobre</q-tooltip>
        </q-icon>
      </RouterLink>
      <RouterLink to="/contato">
        <q-icon name="call">
          <q-tooltip>Contato</q-tooltip>
        </q-icon>
      </RouterLink>
    </nav>
  </header>
</template>

<script setup>
import { RouterLink } from 'vue-router'
</script>

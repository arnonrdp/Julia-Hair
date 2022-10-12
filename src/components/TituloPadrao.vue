<template>
  <h3>Página: {{ nome }}</h3>
</template>

<script setup>
defineProps({
  nome: { type: String }
})
</script>

<style lang="scss" scoped>
h3 {
  color: $primary;
}
</style>

<template>
  <div class="card q-ma-sm q-pa-sm">
    <q-img :src="`src/assets/${imgName}.webp`" width="50%" />
    <p>{{ label }}</p>
  </div>
</template>

<script setup>
defineProps({
  imgName: { type: String, required: true },
  label: { type: String, required: true }
})
</script>

<style lang="scss" scoped>
.card {
  border: 1px solid $primary;
  border-radius: 24px;
  max-width: 240px;
}
</style>

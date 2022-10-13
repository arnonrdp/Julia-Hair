<template>
  <TituloPadrao nome="Sobre" />
  <h4>{{ contador }}</h4>
  <q-btn class="q-ml-xl" rounded @click="somar()">+</q-btn>
</template>

<script setup>
import TituloPadrao from '@/components/TituloPadrao.vue'
import { ref } from 'vue'

let contador = ref(0)

function somar(){
  contador.value++
}
</script>
 

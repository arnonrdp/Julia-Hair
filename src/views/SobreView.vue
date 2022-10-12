<template>
  <TituloPadrao nome="Sobre" />
  <h4>{{ contador }}</h4>
  <q-btn class="q-ml-xl" rounded @click="somar()">+</q-btn>
  <q-btn size="lg" @click="diminuir()">-</q-btn>
  <q-btn icon="question_answer" label="Whatsapp"></q-btn>
</template>

<script setup>
import TituloPadrao from '@/components/TituloPadrao.vue'
import { ref } from 'vue'

let contador = ref(0)

function somar(){
  contador.value++
}

function diminuir(){
  contador.value--
}
</script>

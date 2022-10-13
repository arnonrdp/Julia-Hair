<template>
  <TituloPadrao nome="Contato" />
  <p>Rota: contato</p>
  <div>
    <q-btn icon="question_answer" label="Whatsapp"></q-btn>
    <a href="https://www.instagram.com/fjurodrigues/" target="_blank"><q-btn icon="person_pin" label="Instagram"></q-btn></a>
  </div>

  <footer>
    <p>© 2021 Julia Rodrigues. Todos os direitos reservados.</p>
  </footer>
</template>

<script setup>
import TituloPadrao from '@/components/TituloPadrao.vue'
</script>

<style>
a {
  text-decoration: none;
}
footer {
  position: fixed;
  width: 100%;
  bottom: 0;
  background-color: #bdc3c7;
  text-align: center;
  height: 6%;
}
</style>

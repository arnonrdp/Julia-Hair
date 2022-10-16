<template>
  <TituloPadrao nome="Contato" />
  <nav>
    <a class="button" href="https://wa.me/5521973666897" target="_blank"><q-btn icon="question_answer" label="Whatsapp"></q-btn></a>
    <a class="button" href="https://www.instagram.com/fjurodrigues/" target="_blank"><q-btn icon="person_pin" label="Instagram"></q-btn></a>
  </nav>

  <iframe
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3675.2854430393013!2d-43.109142985410834!3d-22.90284018501375!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x9983e534f35a03%3A0x618cde7ed094c742!2sAv.%20Roberto%20Silveira%2C%20215%20-%20Icara%C3%AD%2C%20Niter%C3%B3i%20-%20RJ%2C%2024230-151!5e0!3m2!1spt-BR!2sbr!4v1665930973060!5m2!1spt-BR!2sbr"
    width="600"
    height="450"
    style="border: 0"
    allowfullscreen=""
    loading="lazy"
    referrerpolicy="no-referrer-when-downgrade"
  ></iframe>
  
</template>

<script setup>
import TituloPadrao from '@/components/TituloPadrao.vue'
</script>

<style>
.button {
  text-decoration: none;
}
</style>

<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <q-img class="photo" src="./assets/main.jpeg" style="height: 270px; max-width: 210px" alt="Julia Rodrigues" />
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

  <footer>
    <p>© 2021 Julia Rodrigues.</p>
  </footer>
</template>

<style>
.photo {
  margin: 20px;
  border-radius: 35px 8px;
}
h4 {
  display: inline;
}

nav {
  font-size: 2rem;
}

a {
  color: black;
}
footer {
  position: fixed;
  width: 100vw;
  height: 70px;
  text-align: center;
  background-color: bisque;
  bottom: 0;
}
</style>

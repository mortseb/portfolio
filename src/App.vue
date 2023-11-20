<script setup>
import NavBar from './components/NavBar.vue'
import FooterBar from './components/FooterBar.vue'



</script>

<template class="dark">
  <header>
    <NavBar></NavBar>
  </header>
  <main><RouterView></RouterView></main>
    <FooterBar></FooterBar>
</template>





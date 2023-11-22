<script setup>
import NavBar from './components/NavBar.vue'
import FooterBar from './components/FooterBar.vue'



</script>

<template class="dark">
  <header>
    <NavBar />
  </header>
  <main>
    <RouterView />
  </main>
  <FooterBar />
</template>





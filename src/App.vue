<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <Navbar />

  <div class="container">
    <RouterView />
  </div>

  <Footer />
</template>

<style scoped></style>

<script setup lang="ts">
import './assets/main.css'
import LandingPage from './components/LandingPage/LandingPage.vue'
</script>

<template>
  <main class="px-4 container">
    <LandingPage />
  </main>
</template>

<style scoped>
main {
  margin: 0 auto;
  max-width: 710px;
  scroll-margin-top: 100vh;
  scroll-margin-bottom: 100vh;
}
</style>

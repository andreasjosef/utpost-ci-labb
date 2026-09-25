<script setup>
import { RouterLink, RouterView } from 'vue-router'
import { funny } from 'funny';
</script>

<template>
  <header>
    <RouterLink to="/guider">Utpost</RouterLink>
  </header>
  <main>
    <RouterView />
  </main>
</template>

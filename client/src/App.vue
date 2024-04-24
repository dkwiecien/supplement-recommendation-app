<script setup lang="ts">
import { RouterView } from 'vue-router'
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
</script>

<template>
  <Header />
  <RouterView class="container-sm" />
  <Footer />
</template>

<style scoped></style>

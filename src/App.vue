<script setup>
import { RouterView } from 'vue-router'
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
import KonstantinSavusiaLogoSVG from './assets/konstantinsavusia.svg?component'
</script>

<template>
  <Header />
  <RouterView />
  <Footer />
</template>

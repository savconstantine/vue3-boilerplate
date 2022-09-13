<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
import KonstantinSavusiaLogoSVG from './assets/konstantinsavusia.svg?component'
</script>

<template>
  <Header />
  <header>
    <KonstantinSavusiaLogoSVG alt="Konstantin Savusia" class="logo" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
  <Footer />
</template>

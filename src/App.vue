<template>
  <header>
    <Header />
  </header>
  <main>
    <RouterView />
  </main>
  <footer>
    <Footer />
  </footer>
  <BottomBar />
</template>

<script setup>
import { RouterView } from "vue-router";
import BottomBar from "./components/BottomBar.vue";
import Footer from "./components/Footer.vue";
import Header from "./components/Header.vue";


</script>

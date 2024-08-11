<script setup>
import { RouterLink, RouterView } from "vue-router";
import WelcomeItem from "./components/WelcomeItem.vue";
import Home from "./components/Home.vue";
import "./assets/global.css";
</script>

<template>
  <main>
    <!-- <WelcomeItem /> -->
    <Home />
  </main>

  <RouterView />
</template>

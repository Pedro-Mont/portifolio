<script setup>
import Navbar from "./components/NavbarComponent.vue";
import FooterPagina from "./components/FooterComponent.vue";
</script>

<template>
  <div class="min-h-screen bg-zinc-300">
    <Navbar />
    <div class="container mx-auto px-4 py-6">
      <router-view></router-view>
    </div>
  </div>
  <FooterPagina />
</template>

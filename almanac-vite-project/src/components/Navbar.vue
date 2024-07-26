<script setup>
import { RouterLink } from "vue-router";
// if using default options
import { vScrollReveal } from 'vue-scroll-reveal';
</script>

<template>
  <div class="flex flex-col justify-center align-middle gap-5 border">
    <RouterLink v-scroll-reveal.reset="{delay: 2000}"
      to="/about"
      >About</RouterLink>
    <RouterLink
      to="/about"
      >About</RouterLink>
    <RouterLink
      to="/"
      >Contact</RouterLink>
    <RouterLink v-scroll-reveal.reset
      to="/about"
      >About</RouterLink>
  </div>
</template>

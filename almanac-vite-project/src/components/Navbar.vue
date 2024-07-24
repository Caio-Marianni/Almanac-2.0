<script setup>
import { ref } from "vue";
import { RouterLink } from "vue-router";
</script>

<template>
  <div class="flex justify-center align-middle w-full gap-5 h-16 fixed border">
    <RouterLink
      to="/about"
      >About</RouterLink>
    <RouterLink
      to="/"
      >Contact</RouterLink>
    <RouterLink
      to="/about"
      >About</RouterLink>
  </div>
</template>

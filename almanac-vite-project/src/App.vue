<script setup>
import Navbar from './components/Navbar.vue'
import FixedSideNavigation from './components/FixedSideNavigation.vue';
import { RouterView } from 'vue-router';
</script>

<template>
  
<div class="h-96 w-screen grid grid-cols-12 grid-rows-5 gap-0">
    <Navbar class="col-span-2 row-span-5" />
</div>
    
<RouterView />
<FixedSideNavigation />
</template>

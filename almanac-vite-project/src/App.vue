<script setup>
import Navbar from './components/Navbar.vue'
import FixedSideNavigation from './components/FixedSideNavigation.vue';
import { RouterView } from 'vue-router';
</script>

<template>
<Navbar />
<RouterView />
<FixedSideNavigation />
</template>

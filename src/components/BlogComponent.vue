<script setup>
import PostComponent from './PostComponent.vue'
import FooterComponent from './FooterComponent.vue'
import NavbarComponent from './NavbarComponent.vue';
import HeroComponent from './HeroComponent.vue';
</script>

<template>
<NavbarComponent/>
<div class="container mx-auto mt-4">
 <HeroComponent/>
 <post-component/>
</div>
<FooterComponent/>
</template>

<style scoped>

</style>

<template>
<div class="container mx-auto  px-40 w-full bg-white text-semibold py-4 text-blue-800 shadow h-14 text-center  space-x-12">
   <nuxt-link to="/">Home</nuxt-link>
   <nuxt-link to="/portfolio">Portfolio</nuxt-link>
   <nuxt-link to="/blog">Blog</nuxt-link>
   <nuxt-link to="/resume">Resume</nuxt-link>
  <div class="hidden"></div>

</div>
</template>

<script setup>

</script>

<style>
body {
  background-color: #fff;
  color: rgba(0,0,0,0.8);
}
.dark-mode body {
  background-color: #091a28;
  color: #ebf4f1;
}
.sepia-mode body {
  background-color: #f1e7d0;
  color: #433422;
}
</style>

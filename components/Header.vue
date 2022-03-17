<template>
<div>
  <div class="sm:container sm:mx-auto invisible sm:visible
  sm:px-40 w-full bg-yellow-100
  text-semibold sm:py-4 text-blue-800
  shadow sm:h-14 sm:text-center
    space-x-12">
    <nuxt-link to="/">Home</nuxt-link>
    <nuxt-link to="/portfolio">Portfolio</nuxt-link>
    <nuxt-link to="/blog">Blog</nuxt-link>
    <nuxt-link to="/resume">Resume</nuxt-link>
  </div>
  <div class="visible shadow text-blue-900 flex items-center -mt-4 pb-4 space-x-4 justify-center sm:hidden ">
    <nuxt-link to="/">Home</nuxt-link>
    <nuxt-link to="/portfolio">Portfolio</nuxt-link>
    <nuxt-link to="/blog">Blog</nuxt-link>
    <nuxt-link to="/resume">Resume</nuxt-link>
  </div>

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

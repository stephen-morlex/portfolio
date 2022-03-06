<template>
<div class="container w-full bg-white text-semibold py-4 text-blue-800 shadow h-14 text-center  space-x-12">

   <nuxt-link to="/">Home</nuxt-link>
   <nuxt-link to="/portfolio">Portfolio</nuxt-link>
   <nuxt-link to="/blog">Blog</nuxt-link>
   <nuxt-link to="/resume">Resume</nuxt-link>
  <div class="hidden"></div>

</div>
</template>

<script>
export default {
  name: "Header",

}
</script>

<style scoped>

</style>

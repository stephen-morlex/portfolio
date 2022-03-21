<template >
  <!--   Portfolio section-->
  <section class="mt-12 p-6">
    <div class="flex items-center mb-8 ">
      <svg class="w-8 h-8 fill-current text-blue-900" height="24" viewBox="0 0 24 24" width="24">
        <path d="M0 0h24v24H0V0z" fill="none"></path>
        <path d="M20.54 5.23l-1.39-1.68C18.88 3.21 18.47 3 18 3H6c-.47 0-.88.21-1.16.55L3.46 5.23C3.17 5.57 3 6.02 3 6.5V19c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V6.5c0-.48-.17-.93-.46-1.27zm-8.89 11.92L6.5 12H10v-2h4v2h3.5l-5.15 5.15c-.19.19-.51.19-.7 0zM5.12 5l.81-1h12l.94 1H5.12z"></path>
      </svg>
      <h1 class=" font-bold text-4xl ml-2  text-blue-900">Portfolio</h1>
    </div>
    <article class="space-y-8">
      <div class="grid sm:grid-cols-2 grid-cols-1 sm:gap-4 gap-2">
        <img class="h-44 object-cover w-full rounded" src="https://images.unsplash.com/photo-1605379399642-870262d3d051?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1506&q=80" alt="">
        <div class="text-gray-600">
          <h1 class="font-semibold sm:text-2xl text-xl  mb-4">lorem ipsum dolor sit ametr</h1>
          <p class="tracking-wider  text-justify leading-loose">I'm familiar with though, and I'm always happy to learn new skill to find the best solutions for a problem. </p>
        </div>
      </div>
      <div class="grid sm:grid-cols-2 grid-cols-1 sm:gap-4 gap-2">
        <img class="h-44 object-cover w-full rounded" src="https://images.unsplash.com/photo-1640622308238-70e5f22fe0be?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxleHBsb3JlLWZlZWR8NXx8fGVufDB8fHx8&auto=format&fit=crop&w=800&q=60" alt="">
        <div class="text-gray-600">
          <h1 class="font-semibold sm:text-2xl text-xl  mb-4">lorem ipsum dolor sit ametr</h1>
          <p class="tracking-wider  text-justify leading-loose">I'm familiar with though, and I'm always happy to learn new skill to find the best solutions for a problem. </p>
        </div>
      </div>
      <div class="grid sm:grid-cols-2 grid-cols-1 sm:gap-4 gap-2">
        <img class="h-44 object-cover w-full rounded" src="https://images.unsplash.com/photo-1647296020397-8ef9f36afe99?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxleHBsb3JlLWZlZWR8MXx8fGVufDB8fHx8&auto=format&fit=crop&w=800&q=60" alt="">
        <div class="text-gray-600">
          <h1 class="font-semibold sm:text-2xl text-xl mb-4">lorem ipsum dolor sit ametr</h1>
          <p class="tracking-wider text-justify leading-loose">I'm familiar with though, and I'm always happy to learn new skill to find the best solutions for a problem. .</p>
        </div>
      </div>
    </article>
  </section>
</template>

<script lang="ts">
export default {
  name: "portfolio"
}
</script>

<style scoped>

</style>

<template>
 <div class="container mx-auto px-40 ">
    <!--   <h1 class="text-center text-xl  text-blue-600">Home page</h1>-->
       <div class="grid grid-cols-2  mt-12  ">
         <div class=" rounded-full">
           <img class="w-72 object-center  rounded-full " src="~/assets/dp.png" alt="hero-cover">
         </div>
         <div class="w-full mt-20 text-blue-900">
           <h1  class="text-7xl  font-semibold">
             Hello 🤚🏿
           </h1>
        <div class="text-5xl   font-semibold leading-normal">
          <h1  class="">
            I'm Stephen Victor
          </h1>
          <span class="text-4xl " >a Software Developer.</span>
        </div>
         </div>
       </div>
   <div class="mt-12">
     <h1 class=" font-semibold text-xl underline pb-4   text-blue-900">About me</h1>
     <p class="tracking-wider text-gray-800 leading-loose">
       My passion is making ideas come to life, be it working solo, as part of a team or leading a team of fellow developers.

       Throughout my 5 years of development experience, I worked as a freelancer building products from the ground up or implementing new features. Also relevant to my set of skills is that. My go-to technologies are Laravel and Vue.js, and I have completed a wide range of projects using them. Those are not the only two libraries/frameworks I'm familiar with though,
       and I'm always happy to learn new skill to find the best solutions for a problem. I consider myself creative and hardworking, as my stats show. If you liked my profile so far, drop me a message and we'll discuss how I can be useful to your project.
     </p>
    </div>
   <div class="mt-12">
     <h1 class=" font-semibold text-xl underline pb-4   text-blue-900">Skills</h1>
     <ul class="inline-flex items-center space-x-4 text-lg font-bold text-black">
       <li>PHP ( Laravel ),</li>
       <li>JavaScript ( VueJS ),</li>
       <li>
         HTML,
       </li>
       <li>CSS ( tailwindcss ),</li>
       <li>Typescript,</li>
       <li>Flutter,</li>
       <li>Docker</li>
     </ul>
   </div> <div class="mt-12">
     <h1 class=" font-semibold text-xl underline pb-4   text-blue-900">Portfolio</h1>
   <section>
     <div class="grid grid-cols-2 gap-4">
       <img class="h-52 object-cover w-52 rounded-md" src="~/assets/dp.png" alt="">
       <div>
         <h1 class="font-semibold text-xl underline pb-">lorem ipsum dolor sit ametr</h1>
         <p>lorem ipsum dolor sit amet, consectetur sit amet, consectetur</p>
       </div>
     </div>
   </section>
   </div>
   <div class="mt-12">
   <h1 class=" font-semibold text-xl underline pb-4   text-blue-900">Articles</h1>

 </div>
 </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

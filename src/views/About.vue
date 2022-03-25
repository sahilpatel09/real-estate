<template>
<Head/>
<div class="md:px-16 py-4 bg-white">
  <!-- <h2 class="text-3xl pl-5 mt-10 mon text-center md:text-left">About the project.</h2> -->

  <section class="text-gray-600 body-font">
  <div class="container mx-auto flex px-5 py-16 md:flex-row flex-col">
    <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
      <h1 class="title-font sm:text-4xl text-xl font-medium text-gray-900">Place where you find yourself

      </h1>
      <p class="pt-10 pl-4 leading-relaxed">
      <ul class="list-disc">
        <li>Quite and peaceful location near the nature</li>
        <li>Shopping and fitness center right inside the complex</li>
        <li>Lot of parking places, even for your visitors</li>
        <li>Many play areas for your kids</li>
      </ul>
    </p>
      <div class="flex justify-center mt-4">
        <button class="inline-flex text-white bg-indigo-500 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded text-lg">Button</button>
        <button class="ml-4 inline-flex text-gray-700 bg-gray-100 border-0 py-2 px-6 focus:outline-none hover:bg-gray-200 rounded text-lg">Button</button>
      </div>
    </div>
    <div class=" lg:w-full md:w-1/2 w-5/6">
<!--       <img class="object-cover object-center rounded" alt="hero" src="https://dummyimage.com/720x600"> -->
      <video src="@/assets/about.mp4" autoplay class="w-full"></video>
    </div>
  </div>
</section>
</div>
</template>
<script setup>
import Head from '../components/GlobalHead.vue'
</script>
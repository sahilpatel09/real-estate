<template>
<header >
  <div class="relative">
  <img :src="imageUrl" alt="aminities" class="image-background">
	<div class="overlay-image">

	<div class="px-3 md:px-16">
    <Head/>
    <div class="flex items-center justify-center w-max-lg mt-20">
      <div class="text-center lg:w-3/4">
          <h1 class="text-5xl md:text-8xl mb-2 font-medium text-white vibes fadeInDown">{{ props.herotitle }}</h1>
          <p class="leading-relaxed mb-8 text-base text-gray-200 lg:w-2/3 mx-auto mon in-left">{{ props.herotext }}</p>
        </div>
      </div>
	</div>

	</div>
  <!-- overlay -->
	</div>  
  <!-- relative -->
</header>
</template>

<script setup>
import { ref,defineProps } from 'vue'
import Head from './Nav.vue'
const props = defineProps(['herotitle','herotext','heroimage'])
const imageUrl = ref(require("@/assets/"+props.heroimage))
</script>

<style scoped>
.image-background { /* class name used in javascript too */
    width: 100%; /* width needs to be set to 100% */
    height: 400px; /* height needs to be set to 100% */
    position: absolute;
    left: 0;
    top: 0;
    z-index:-1;
    object-fit: cover;
}
.overlay-image {
	width: 100%;
	height: 400px;
  top: 0;
  left: 0;
  background: rgba(0,0,0,0.4);
  background-size: 3px 3px;
  z-index: 2;
}
</style>
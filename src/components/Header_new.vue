<template>
<header id="header" class=""><div class="relative">

	<video class="video-background" autoplay="autoplay" muted>
		<source src="@/assets/homepage.mp4" type="video/mp4">
	</video>
	<div class="overlay">
	<div class="py-3 px-3 md:px-16">
    <Head/>
<!--     <h1 class="text-white text-9xl vibes">Luxurious Living</h1> -->
    <div class="flex items-center justify-center w-max-lg h-screen">
    <div class="text-center lg:w-3/4 w-full">
          <h1 class="text-5xl md:text-8xl mb-2 font-medium text-white vibes ">Luxurious Living, Redefined.</h1>
          <p class="leading-relaxed mb-8 text-gray-200 lg:w-2/3 mx-auto mon">3 BHK Luxurious apartments near you in Navarangpura. Samyak49 is the one of the modern and nice to decore flats in the Ahmedabad.</p>
          <div class="flex justify-center">
<!--             <button class="inline-flex text-white bg-red-500 border-0 py-2 px-6 focus:outline-none hover:bg-red-600 rounded text-lg">Button</button>
            <button class="ml-4 inline-flex text-gray-400 bg-gray-800 border-0 py-2 px-6 focus:outline-none hover:bg-gray-700 hover:text-white rounded text-lg">Button</button> -->
          </div>
        </div>
</div>
	</div>		
	</div>
	</div>
</header>
</template>

<script setup>
import Head from './Nav.vue'
</script>

<style>
.video-background { /* class name used in javascript too */
    width: 100%; /* width needs to be set to 100% */
    height: 100vh; /* height needs to be set to 100% */
    position: absolute;
    left: 0;
    top: 0;
    z-index: -1;
    object-fit: cover;
}
.overlay {
	width: 100%;
	height: 100vh;
  top: 0;
  left: 0;
  background: rgba(0,0,0,0.4);
  background-size: 3px 3px;
  z-index: 2;
}
.wine {
	color:#722F37;
}
.bg-wine {
	background:#722F37;
}
.bg-wine-dark{
	background: #2e1316;
}
.border-wine {
border-bottom: 4px solid #39181c;
}
.vibes{
	font-family: 'Great Vibes', cursive;
}
</style>
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
            <button @click="this.$store.state.isHidden = !this.$store.state.isHidden" class="inline-flex text-white bg-wine border-0 py-2 px-6 focus:outline-none hover:bg-red-600 rounded text-lg">Inquire now</button>
<!--             <a href="tel:+918200489230">
            <button class="ml-4 inline-flex text-gray-400 bg-yellow-600 border-0 py-2 px-6 focus:outline-none hover:bg-gray-700 hover:text-white rounded text-lg">Call us</button></a> -->
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



@-webkit-keyframes fadeInLeft {
    from {
        opacity:0;
        -webkit-transform: translatex(-10px);
        -moz-transform: translatex(-10px);
        -o-transform: translatex(-10px);
        transform: translatex(-10px);
    }
    to {
        opacity:1;
        -webkit-transform: translatex(0);
        -moz-transform: translatex(0);
        -o-transform: translatex(0);
        transform: translatex(0);
    }
}
@-moz-keyframes fadeInLeft {
    from {
        opacity:0;
        -webkit-transform: translatex(-10px);
        -moz-transform: translatex(-10px);
        -o-transform: translatex(-10px);
        transform: translatex(-10px);
    }
    to {
        opacity:1;
        -webkit-transform: translatex(0);
        -moz-transform: translatex(0);
        -o-transform: translatex(0);
        transform: translatex(0);
    }
}
@keyframes fadeInLeft {
    from {
        opacity:0;
        -webkit-transform: translatex(-100px);
        -moz-transform: translatex(-100px);
        -o-transform: translatex(-100px);
        transform: translatex(-100px);
    }
    to {
        opacity:1;
        -webkit-transform: translatex(0);
        -moz-transform: translatex(0);
        -o-transform: translatex(0);
        transform: translatex(0);
    }
}
.in-left {
    -webkit-animation-name: fadeInLeft;
    -moz-animation-name: fadeInLeft;
    -o-animation-name: fadeInLeft;
    animation-name: fadeInLeft;
    -webkit-animation-fill-mode: both;
    -moz-animation-fill-mode: both;
    -o-animation-fill-mode: both;
    animation-fill-mode: both;
    -webkit-animation-duration: 200ms;
    -moz-animation-duration: 200ms;
    -o-animation-duration: 200ms;
    animation-duration: 200ms;
    -webkit-animation-delay: 200ms;
    -moz-animation-delay: 200ms;
    -o-animation-duration:200ms;
    animation-delay: 200ms;
}

</style>
<template>
	<header id="header" class=""><div class="">
<!-- 	<video class="video-background" src="@/assets/video.mp4" autoplay></video> -->
<img src="@/assets/living.jpeg" class="video-background">
	<div class="overlay">
	<div class="py-3 px-3 md:px-16">
    <Nav />
    <div class="pt-40 px-16">
    <h2 class="md:text-7xl text-5xl text-white mon font-semibold">
    Get Ready.<br>We're finishing!
</h2>
    </div>
	</div>		
	</div>
	</div>
</header>
</template>

<script setup>
import Nav from './Nav.vue'
</script>

<style>

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
.border-wine {
border-bottom: 4px solid #39181c;
}
.mon {
font-family: 'Montserrat', sans-serif;
}
</style>
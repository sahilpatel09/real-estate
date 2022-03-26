<template>
<header id="header" class=""><div class="">
	<video  class="video-background" src="@/assets/homepage.mp4" autoplay loop></video>
<!-- <img src="@/assets/living.jpeg" class="video-background"> -->
	<div class="overlay">
	<div class="py-3 px-3 md:px-16">
    <Head/>
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
    position: fixed;
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
.border-wine {
border-bottom: 4px solid #39181c;
}
</style>
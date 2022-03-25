<template>
<header>
	<div class="">
<!-- 	<video class="video-background" src="@/assets/video.mp4" autoplay></video> -->
<img src="@/assets/living.jpeg" class="video-background">
	<div class="overlay">
	<div class="py-3 flex flex-row justify-between items-center px-16">
		<div class="logo">
			<img src="@/assets/logow.png" alt="" class="w-44">
		</div>
		<div class="menu flex flex-row justify-center items-center gap-4">
			<ul class=" hidden flex flex-row gap-4 text-white text-base antialiased">
				<li>Home</li>
				<li>About</li>
				<li>Amenities</li>
				<li>Blog</li>
				<li>Gallery</li>
				<li>Contact</li>
			</ul>
			<button class="hidden text-white px-4 py-2 bg-indigo-600 rounded">Brochure</button>
			<button class="">SVG</button>
		</div>
	</div>		
	</div>
	</div>

</header>
</template>
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
  background: rgba(0,0,0,0.6);
  background-size: 3px 3px;
  z-index: 2;
}

</style>
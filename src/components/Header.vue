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
			<ul class="flex flex-row gap-4 text-white text-base">
				<li>Home</li>
				<li>About</li>
				<li>Amenities</li>
				<li>Blog</li>
				<li>Gallery</li>
				<li>Contact</li>
			</ul>
			<button class="text-white px-4 py-2 bg-indigo-600 rounded">Brochure</button>
		</div>
	</div>		
	</div>
	</div>

</header>

<section class="text-gray-400 bg-gray-900 body-font">
  <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
    <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
      <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-white">Before they sold out
        <br class="hidden lg:inline-block">readymade gluten
      </h1>
      <p class="mb-8 leading-relaxed">Copper mug try-hard pitchfork pour-over freegan heirloom neutra air plant cold-pressed tacos poke beard tote bag. Heirloom echo park mlkshk tote bag selvage hot chicken authentic tumeric truffaut hexagon try-hard chambray.</p>
      <div class="flex justify-center">
        <button class="inline-flex text-white bg-indigo-500 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded text-lg">Button</button>
        <button class="ml-4 inline-flex text-gray-400 bg-gray-800 border-0 py-2 px-6 focus:outline-none hover:bg-gray-700 hover:text-white rounded text-lg">Button</button>
      </div>
    </div>
    <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
      <img class="object-cover object-center rounded" alt="hero" src="@/assets/plan.png">
    </div>
  </div>
</section>
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
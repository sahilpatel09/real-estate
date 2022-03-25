<template>
	<header id="header" class=""><div class="">
<!-- 	<video class="video-background" src="@/assets/video.mp4" autoplay></video> -->
<img src="@/assets/living.jpeg" class="video-background">
	<div class="overlay">
	<div class="py-3 px-3 md:px-16">
    <nav class=" w-full">
      <div class="max-w-6xl mx-auto px-4">
        <div class="flex justify-between">
          <div class="flex space-x-7">
            <div>
              <!-- Website Logo -->
              <a href="#" class="flex items-center py-4 px-2">
                <img
                  src="@/assets/invert.png"
                  alt="Logo"
                  class="w-40 mr-2"
                />
<!--                 <h2 class="w-40 mr-2 text-white text-2xl">SAMYAK 49</h2> -->
                <!-- <span class="font-semibold text-gray-500 text-lg">AUTOCAR</span> -->
              </a>
            </div>
            <!-- Primary Navbar items -->
            <div class="hidden md:flex items-center space-x-1 text-white">
              <a
                href=""
                class="
                  py-2
                  px-2
                  text-white
                  border-b-4 border-wine
                  font-semibold
                "
                >Home</a
              >
              <a
                href=""
                class="
                  py-4
                  px-2
                  font-semibold
                  hover:text-green-500
                  transition
                  duration-300
                "
                >Services</a
              >
              <a
                href=""
                class="
                  py-4
                  px-2
                  font-semibold
                  hover:text-green-500
                  transition
                  duration-300
                "
                >About</a
              >
              <a
                href=""
                class="
                  py-4
                  px-2
                  font-semibold
                  hover:text-green-500
                  transition
                  duration-300
                "
                >Contact Us</a
              >
            </div>
          </div>
          <!-- Secondary Navbar items -->
          <div class="hidden md:flex items-center space-x-3">
            
            <a
              href=""
              class="
                py-2
                px-4
                font-medium
                text-white
                bg-wine
                rounded
                hover:bg-gray-700
                transition
                duration-300
              "
              >Brochure</a
            >
          </div>
          <!-- Mobile menu button -->
          <div class="md:hidden flex items-center">
            <button class="outline-none mobile-menu-button" @click="isOpen = !isOpen">
              <svg
                class="w-9 h-9 text-white hover:text-gray-100"
                x-show="!showMenu"
                fill="none"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path d="M4 6h16M4 12h16M4 18h16"></path>
              </svg>
            </button>
          </div>
        </div>
      </div>
      <!-- mobile menu -->
      <div class="mobile-menu" :class="{ 'hidden': isOpen }">
        <ul class="">
          <li class="active">
            <a
              href="index.html"
              class="
                block
                text-sm
                px-4
                py-4
                text-white
                bg-green-500
                font-semibold
              "
              >Home</a
            >
          </li>
          <li>
            <a
              href="#services"
              class="
                block
                text-sm
                px-4
                py-4
                text-white
                bg-green-500
                hover:bg-indigo-500
                transition
                duration-300
              "
              >Services</a
            >
          </li>
          <li>
            <a
              href="#about"
              class="
                block
                text-sm
                px-4
                py-4
                hover:bg-indigo-500
                text-white
                bg-green-500

                transition
                duration-300
              "
              >About</a
            >
          </li>
          <li>
            <a
              href="#contact"
              class="
                block
                text-sm
                px-4
                py-4
                hover:bg-indigo-500
                text-white
                bg-green-500
                transition
                duration-300
              "
              >Contact Us</a
            >
          </li>
        </ul>
      </div>
    </nav>




	</div>		
	</div>
	</div>
</header>
</template>

<script setup>
import { ref } from 'vue'
const isOpen = ref(true)

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
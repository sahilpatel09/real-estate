<template>
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
              </a>
            </div>
            <!-- Primary Navbar items -->
            <div class="hidden md:flex items-center space-x-1 text-white">
              <router-link to="/" class="
                  py-2
                  px-2
                  text-white
                  font-semibold
                  hover:text-gray-200
                  transition
                  duration-300
                ">Home</router-link>

                <router-link to="/about" class="
                  py-2
                  px-2
                  text-white
                  font-semibold
                  hover:text-gray-200
                  transition
                  duration-300
                ">About</router-link>

                <router-link to="/aminities" class="
                  py-2
                  px-2
                  text-white
                  font-semibold
                  hover:text-gray-200
                  transition
                  duration-300
                ">Aminities</router-link>

                <router-link to="/gallery" class="
                  py-2
                  px-2
                  text-white
                  font-semibold
                  hover:text-gray-200
                  transition
                  duration-300
                ">Gallery</router-link>

                <router-link to="/blog" class="
                  py-2
                  px-2
                  text-white
                  font-semibold
                  hover:text-gray-200
                  transition
                  duration-300
                ">Blog</router-link>

                <router-link to="/contact-us" class="
                  py-2
                  px-2
                  text-white
                  font-semibold
                  hover:text-gray-200
                  transition
                  duration-300
                ">Contact</router-link>


            </div>
          </div>
          <!-- Secondary Navbar items -->
          <div class="hidden md:flex items-center space-x-3">
            
            <a
              href="/download"
              class="
                py-2
                px-4
                font-medium
                text-white
                bg-wine
                rounded
                hover:bg-yellow-500
                transition
                duration-300
                shadow-2xl
              "
              >Brochure</a
            >
                        <a
              href="/inquire-us"
              class="
                py-2
                px-4
                font-medium
                text-white
                bg-wine
                rounded
                hover:bg-yellow-500
                transition
                duration-300
                rounded
                shadow-2xl
              "
              >Inquire us</a
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
      <div class="mobile-menu fadeInDown" :class="{ 'hidden': isOpen }">
        <ul class="mobile-menu-overlay">
        
          <li class="active">
            <router-link to="/" class="block
                text-sm
                px-4
                py-4
                text-white
                hover:bg-yellow-500
                font-semibold">
              Home
            </router-link>
          </li>

          <li>
            <router-link to="/about" class="block
                text-sm
                px-4
                py-4
                text-white
                hover:bg-yellow-500
                font-semibold">
              About
            </router-link>
          </li>

          <li>
            <router-link to="/aminities" class="block
                text-sm
                px-4
                py-4
                text-white
                hover:bg-yellow-500
                font-semibold">
              Aminities
            </router-link>
          </li>

          <li>
            <router-link to="/gallery" class="block
                text-sm
                px-4
                py-4
                text-white
                hover:bg-yellow-500
                font-semibold">
              Gallery
            </router-link>
          </li>
          
          <li>
            <router-link to="/blog" class="block
                text-sm
                px-4
                py-4
                text-white
                hover:bg-yellow-500
                font-semibold">
              Blog
            </router-link>
          </li>

          <li>
            <router-link to="/contact-us" class="block
                text-sm
                px-4
                py-4
                text-white
                hover:bg-yellow-500
                font-semibold">
              Contact Us
            </router-link>
          </li>
          <li>
            <router-link to="/download" class="block
                text-sm
                px-4
                py-4
                bg-wine
                text-white
                hover:bg-yellow-500
                transition duration-300
                font-semibold">
              Brochure
            </router-link>
          </li>
          <li>
            <router-link to="/inquire-us" class="block
                text-sm
                px-4
                py-4
                bg-wine
                text-white
                hover:bg-yellow-500
                transition duration-300
                font-semibold">
              Inquire us
            </router-link>
          </li>
        </ul>
      </div>
    </nav>
</template>

<script setup>
import { ref } from 'vue'
const isOpen = ref(true)

</script>
<style>
.mobile-menu-overlay {
  background: rgba(0,0,0,0.4);
  background-size: 3px 3px;
  z-index: 2;
}

@-webkit-keyframes fadeInDown {
            0% {
               opacity: 0;
               -webkit-transform: translateY(-20px);
            }
            100% {
               opacity: 1;
               -webkit-transform: translateY(0);
            }
         }
         
         @keyframes fadeInDown {
            0% {
               opacity: 0;
               transform: translateY(-20px);
            }
            100% {
               opacity: 1;
               transform: translateY(0);
            }
         }
         
         .fadeInDown {
            -webkit-animation-name: fadeInDown;
            animation-name: fadeInDown;
            -webkit-animation-duration: 1s;
            animation-duration: 1s;
            -webkit-animation-fill-mode: both;
            animation-fill-mode: both;
         }
</style>
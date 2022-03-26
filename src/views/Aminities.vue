<template>
	<UniHead herotitle="Luxurious Aminities."
	herotext="3 BHK Luxurious apartments near you in Navarangpura. Samyak49 is the one of the modern and nice to decore flats in the Ahmedabad."
	heroimage="living.jpeg"
	/>



<div class="relative flex flex-col-reverse py-16 lg:pt-0 lg:flex-col lg:pb-0">
  <div class="inset-y-0 top-0 right-0 z-0 w-full max-w-xl px-4 mx-auto md:px-0 lg:pr-0 lg:mb-0 lg:mx-0 lg:w-7/12 lg:max-w-full lg:absolute xl:px-0">
    <svg class="absolute left-0 hidden h-full text-white transform -translate-x-1/2 lg:block" viewBox="0 0 100 100" fill="currentColor" preserveAspectRatio="none slice">
      <path d="M50 0H100L50 100H0L50 0Z"></path>
    </svg>
    <img
      class="object-cover w-full h-56 rounded shadow-lg lg:rounded-none lg:shadow-none md:h-96 lg:h-full"
      src="https://images.pexels.com/photos/3184291/pexels-photo-3184291.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;h=750&amp;w=1260"
      alt=""
    />
  </div>
  <div class="relative flex flex-col items-start w-full max-w-xl px-4 mx-auto md:px-0 lg:px-8 lg:max-w-screen-xl">
    <div class="mb-16 lg:my-40 lg:max-w-lg lg:pr-5">
      <p class="inline-block px-3 py-px mb-4 text-xs font-semibold tracking-wider text-teal-900 uppercase rounded-full bg-teal-accent-400">
        Brand new
      </p>
      <h2 class="mb-5 font-sans text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none">
        Everything you<br class="hidden md:block" />
        can imagine
        <span class="inline-block text-deep-purple-accent-400">is real</span>
      </h2>
      <p class="pr-5 mb-5 text-base text-gray-700 md:text-lg">
        Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae. explicabo.
      </p>
      <div class="flex items-center">
        <a
          href="/"
          class="inline-flex items-center justify-center h-12 px-6 mr-6 font-medium tracking-wide text-white transition duration-200 rounded shadow-md bg-deep-purple-accent-400 hover:bg-deep-purple-accent-700 focus:shadow-outline focus:outline-none"
        >
          Get started
        </a>
        <a href="/" aria-label="" class="inline-flex items-center font-semibold text-gray-800 transition-colors duration-200 hover:text-deep-purple-accent-700">Learn more</a>
      </div>
    </div>
  </div>
</div>














<div class="bg-wine">
  <div class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
    <div class="max-w-xl sm:mx-auto lg:max-w-2xl">
      <div class="flex flex-col mb-16 sm:text-center sm:mb-0">
        <a href="/" class="mb-6 sm:mx-auto">
          <div class="flex items-center justify-center w-12 h-12 rounded-full bg-teal-accent-400">
            <svg class="w-10 h-10 text-deep-purple-900" stroke="currentColor" viewBox="0 0 52 52">
              <polygon stroke-width="3" stroke-linecap="round" stroke-linejoin="round" fill="none" points="29 13 14 29 25 29 23 39 38 23 27 23"></polygon>
            </svg>
          </div>
        </a>
        <div class="max-w-xl mb-10 md:mx-auto sm:text-center lg:max-w-2xl md:mb-12">
          <h2 class="max-w-lg mb-6 font-sans text-3xl font-bold leading-none tracking-tight text-white sm:text-4xl md:mx-auto">
            <span class="relative inline-block">
              <svg viewBox="0 0 52 24" fill="currentColor" class="absolute top-0 left-0 z-0 hidden w-32 -mt-8 -ml-20 text-deep-purple-accent-100 lg:w-32 lg:-ml-28 lg:-mt-10 sm:block">
                <defs>
                  <pattern id="700c93bf-0068-4e32-aafe-ef5b6a647708" x="0" y="0" width=".135" height=".30">
                    <circle cx="1" cy="1" r=".7"></circle>
                  </pattern>
                </defs>
                <rect fill="url(#700c93bf-0068-4e32-aafe-ef5b6a647708)" width="52" height="24"></rect>
              </svg>
              <span class="relative">The</span>
            </span>
            quick, brown fox jumps over a lazy dog
          </h2>
          <p class="text-base text-indigo-100 md:text-lg">
            Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque rem aperiam, eaque ipsa quae.
          </p>
        </div>
        <div>
          <a
            href="/"
            class="inline-flex items-center justify-center h-12 px-6 font-semibold tracking-wide text-teal-900 transition duration-200 rounded shadow-md hover:text-deep-purple-900 bg-teal-accent-400 hover:bg-deep-purple-accent-100 focus:shadow-outline focus:outline-none"
          >
            Get started
          </a>
        </div>
      </div>
    </div>
  </div>
</div>



	<Footer/>
</template>
<script setup>
import UniHead from '../components/UniversalHead.vue'
import Footer from '../components/Footer.vue'
</script>
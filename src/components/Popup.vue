<template>
	<div class="inset-0 fixed blacklayer w-screen h-screen flex items-center justify-center">
		<div class="px-5 bg-wine rounded shadow-xl">
		<div class=" flex flex-col md:ml-auto w-full md:py-8 mt-8 md:mt-0">
      
      <div class="flex flex-row justify-between items-center">
      <h2 class="text-white text-lg mb-1 font-medium title-font">Feedback</h2>
      <img @click="this.$store.state.isHidden = !this.$store.state.isHidden" 
      src="@/assets/svg/close.svg" class="text-white text-lg mb-1 font-medium title-font" />
      </div>
      
      <p class="leading-relaxed mb-5 text-gray-300">Get a call back from us about your inquiry.</p>
      <div class="relative mb-4">
        <label for="name" class="leading-7 text-sm text-gray-400">Name</label>
        <input type="text" id="name" name="name" class="w-full bg-gray-800 rounded border border-gray-700 focus:border-indigo-500 focus:ring-2 focus:ring-indigo-900 text-base outline-none text-gray-100 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
      </div>
      <div class="relative mb-4">
        <label for="email" class="leading-7 text-sm text-gray-400">Mobile no,</label>
        <input type="email" id="email" name="email" class="w-full bg-gray-800 rounded border border-gray-700 focus:border-indigo-500 focus:ring-2 focus:ring-indigo-900 text-base outline-none text-gray-100 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
      </div>
      <div class="relative mb-4">
        <label for="message" class="leading-7 text-sm text-gray-400">Message</label>
        <textarea id="message" name="message" class="w-full bg-gray-800 rounded border border-gray-700 focus:border-indigo-500 focus:ring-2 focus:ring-indigo-900 h-32 text-base outline-none text-gray-100 py-1 px-3 resize-none leading-6 transition-colors duration-200 ease-in-out"></textarea>
      </div>
      <button class="text-white bg-indigo-800 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded text-lg">Get a call back</button>
      <p class="text-xs text-gray-400 text-opacity-90 mt-3">Chicharrones blog helvetica normcore iceland tousled brook viral artisan.</p>
    </div>
  </div>
		</div>
</template>

<style scoped>
	.blacklayer{
	background: rgba(0,0,0,0.8);
	}
</style>
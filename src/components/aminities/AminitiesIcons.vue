<template>
	<div class="relative px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
  
<div class="flex flex-col mb-10 sm:text-center sm:mb-0">
            <div class="max-w-xl mb-10 md:mx-auto sm:text-center lg:max-w-2xl md:mb-12">
        <h2 class="max-w-lg mb-6 font-sans text-3xl font-bold leading-none tracking-tight text-gray-900 sm:text-4xl md:mx-auto">
          <span class="relative inline-block">
            <span class="relative">Location</span>
          </span>
          Connectivity
        </h2>
      </div>
    </div>
  
  <div class="relative grid gap-5 sm:grid-cols-2 lg:grid-cols-4">
    
    

    <div v-for="index in 4" :key="index" class="flex flex-col justify-between overflow-hidden text-left transition-shadow duration-200 bg-wine rounded shadow-xl group hover:shadow-2xl">
      <div class="p-10 bg-red-900 flex flex-col items-center">
        <div class="flex items-center justify-center p-2 w-24 h-34 rounded mb-4 shadow-2xl drop-shadow bg-blend-multiply">
          <img src="@/assets/tempale.png" alt="">
        </div>
         <p class=" font-bold text-gray-100">Security</p>
         <p class="text-sm leading-5 text-white">
                  Tempal | 2 min
                </p>
      </div>
      <div class="w-full h-1 ml-auto duration-300 origin-left transform scale-x-0 bg-deep-purple-accent-400 group-hover:scale-x-100"></div>
    </div>





    
    
  </div>
</div>



</template>
<style scoped>
	.bgSmallTab{
		background: #672a32;
	}
</style>
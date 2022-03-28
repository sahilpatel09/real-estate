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
  
  <div class="relative grid gap-5 grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 items-center">
    
  
    <div v-for="item in imageData" :key="item" class="flex flex-col justify-between items-center overflow-hidden text-left transition-shadow duration-200 bg-wine rounded shadow-xl group hover:shadow-2xl">
      <div class="py-3 flex flex-col items-center">
        <div class="flex items-center justify-center p-2 w-24 h-24 rounded shadow-2xl drop-shadow bg-blend-multiply">
          <img :src="item.imgUrl" alt="">
        </div>
         <p class=" font-bold text-gray-100">{{ item.title }}</p>
         <p class="text-sm leading-5 text-white">
                  {{ item.desc }}
                </p>
      </div>

    </div>




    
    
  </div>
</div>



</template>
<script setup>
import { ref } from 'vue';
//const url = '@/assets/';
const imageData = ref({
    0:{
      title: "Temple",
      desc: "500m | 4 min walk",
      imgUrl: require('@/assets/images/temple.png'),
    },
    1:{
      title: "School",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/school.png')
    },
    2:{
      title: "Bus Stop",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/bus-stop.png')
    },
    3:{
      title: "Airport",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/airport.png')
    },
    4:{
      title: "Grocery Store",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/grocery.png')
    },
    5:{
      title: "Hospital",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/hospital.png')
    },
    7:{
      title: "Railway Station",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/railway.png')
    },
    8:{
      title: "Restaurant",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/restaurant.png')
    },
    9:{
      title: "Theater",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/theater.png')
    },
    10:{
      title: "City Center",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/city-center.png')
    },


});
</script>
<style scoped>
	.bgSmallTab{
		background: #672a32;
	}
</style>
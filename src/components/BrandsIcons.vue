<template>
	<div class="relative px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
<div class="flex flex-col sm:text-center sm:mb-0">
            <div class="max-w-xl mb-10 md:mx-auto sm:text-center lg:max-w-2xl md:mb-12">

    <a href="/" aria-label="View" class="inline-block mb-5 rounded-full sm:mx-auto">
     
    </a>
    <h2 class="mb-4 font-sans text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none">
      Associated Brands
    </h2>
    <p class="text-base text-gray-700 md:text-lg sm:px-4">
      Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque rem aperiam, eaque ipsa quae.
    </p>
      </div>
    </div>
  
  <div class="relative grid gap-5 grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 items-center">
    
  
    <div v-for="item in imageData" :key="item" class="flex flex-col justify-between items-center overflow-hidden text-left transition-shadow duration-200 rounded shadow-xl group hover:shadow-2xl">
      <div class="flex flex-col items-center p-5">
        <div class="flex items-center justify-center p-2 w-40 h-20 items-center rounded drop-shadow bg-blend-multiply">
          <img :src="item.imgUrl" alt="">
        </div>
         <p class=" font-bold text-gray-900">{{ item.title }}</p>
         <!-- <p class="text-sm leading-5 text-black">
                  {{ item.desc }}
                </p> -->
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
      title: "CrabTree",
      desc: "500m | 4 min walk",
      imgUrl: require('@/assets/images/brands/crabtree.jpeg'),
    },
    1:{
      title: "Mitsubishi",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/brands/mitsubishi.jpeg')
    },
    2:{
      title: "Kohler",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/brands/kohler.png')
    },
    3:{
      title: "Kone",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/brands/kone.png')
    },
    4:{
      title: "Aluk",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/brands/aluk.jpeg')
    },
    5:{
      title: "Havells",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/brands/havells.png')
    },
    7:{
      title: "Qutone",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/brands/qutone.jpeg')
    },
    8:{
      title: "ElectroTherm",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/brands/electrotherm.png')
    },
    9:{
      title: "RR Cables",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/brands/rrcable.png')
    },
    10:{
      title: "Franke",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/brands/franke.jpeg')
    },

    11:{
      title: "Franke",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/brands/asianpaints.jpeg')
    },

    12:{
      title: "Franke",
      desc: "1Km | 4 min",
      imgUrl: require('@/assets/images/brands/astral.jpeg')
    },


});
</script>
<style scoped>
	.bgSmallTab{
		background: #672a32;
	}
</style>
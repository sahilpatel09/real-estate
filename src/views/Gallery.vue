<template>
	<UniHead herotitle="Gallery"
	herotext="3 BHK Luxurious apartments near you in Navarangpura. Samyak49 is the one of the modern and nice to decore flats in the Ahmedabad."
	heroimage="living.jpeg"
	/>


<section class="text-gray-600 body-font">
  <div class="container px-5 py-24 mx-auto">
    <div class="flex flex-col text-center w-full mb-20">
      <h1 class="sm:text-3xl mon text-2xl font-medium title-font mb-4 text-gray-900">Beautiful Homes, Crafted with Care</h1>
      <p class="lg:w-2/3 mx-auto leading-relaxed text-base">Whatever cardigan tote bag tumblr hexagon brooklyn asymmetrical gentrify, subway tile poke farm-to-table. Franzen you probably haven't heard of them man bun deep jianbing selfies heirloom.</p>
    </div>

    <div class="flex flex-wrap -m-4">
      

      <div class="sm:w-1/2 w-full p-4" v-for="item in galleryData" :key="item">
        <div class="flex relative">
          <img alt="gallery" class="absolute inset-0 w-full h-full object-cover object-center" 
          :src="item.img">
          <div class="px-8 py-52 relative z-10 w-full opacity-0 hover:opacity-100 transition duration-200 box">
<!--             <h2 class="tracking-widest text-sm title-font font-medium text-white mb-1">THE SUBTITLE</h2> -->
            <h1 class="title-font text-lg font-medium text-white mb-3 text-center">{{ item.title }}</h1>
<!--             <p class="leading-relaxed text-white">{{ item.desc }}</p> -->
          </div>
        </div>
      </div>


<div class="flex flex-col text-center w-full mb-20">
      <h1 class="sm:text-3xl mon text-2xl font-medium title-font mb-4 text-gray-900">Modern Homes for Modern People</h1>
      <p class="lg:w-2/3 mx-auto leading-relaxed text-base">Whatever cardigan tote bag tumblr hexagon brooklyn asymmetrical gentrify, subway tile poke farm-to-table. Franzen you probably haven't heard of them man bun deep jianbing selfies heirloom.</p>
    </div>


      <div class="sm:w-1/2 p-4" v-for="item in videoData" :key="item">
        <div class="flex relative">
        
          <video :src="item.video" autobuffer autoloop loop controls :poster="item.poster" class="inset-0 w-full h-96 object-cover object-center"></video>

        </div>
      </div>



      

    
    </div>
  </div>
</section>




	<Footer/>
</template>
<script setup>
import UniHead from '../components/UniversalHead.vue'
import Footer from '../components/Footer.vue'
import { ref } from 'vue';
//const url = '@/assets/';
const galleryData = ref({
    0:{
      title: "Bedroom",
      img: require('@/assets/images/gallery/bedroom.jpeg'),
    },
    1:{
      title: "Mitsubishi",
      img: require('@/assets/images/gallery/bedroom-front.jpeg'),
    },
    2:{
      title: "Mitsubishi",
      img: require('@/assets/images/gallery/bedroom-with-tv.jpeg'),
    },
    3:{
      title: "Mitsubishi",
      img: require('@/assets/images/gallery/bedroom-closet.jpeg'),
    },
    4:{
      title: "Mitsubishi",
      img: require('@/assets/images/gallery/bedroom-front.jpeg'),
    },
    5:{
      title: "Mitsubishi",
      img: require('@/assets/images/gallery/bedroom-study.jpeg'),
    },
    6:{
      title: "Mitsubishi",
      img: require('@/assets/images/gallery/bedroom-one-side.jpeg'),
    },
    7:{
      title: "Mitsubishi",
      img: require('@/assets/images/gallery/bedroom-one-profile.jpeg'),
    },
    8:{
      title: "Mitsubishi",
      img: require('@/assets/images/gallery/bedroom-two.jpeg'),
    },
    9:{
      title: "Mitsubishi",
      img: require('@/assets/images/gallery/bedroom-two-front.jpeg'),
    },
    10:{
      title: "Mitsubishi",
      img: require('@/assets/images/gallery/bedroom-two-side.jpeg'),
    },
    11:{
      title: "Mitsubishi",
      img: require('@/assets/images/gallery/dining-area.jpeg'),
    },
    12:{
      title: "Entrance",
      img: require('@/assets/images/gallery/Entrance.jpeg'),
    },
    13:{
      title: "Living Room",
      img: require('@/assets/images/gallery/living-room.jpeg'),
    },
    14:{
      title: "Mitsubishi",
      img: require('@/assets/images/gallery/living-room-full.jpeg'),
    },
    15:{
      title: "Living Room",
      img: require('@/assets/images/gallery/living-room-front.jpeg'),
    },
    16:{
      title: "Living Room",
      img: require('@/assets/images/gallery/living-room-side-profile.jpeg'),
    },


});



const videoData = ref({
    0:{
      title: "Homes",
      video: require('@/assets/homepage.mp4'),
      poster: require('@/assets/living.jpeg'), 
    },
    1:{
      title: "About",
      video: require('@/assets/about.mp4'),
      poster: require('@/assets/blog.jpeg'),
    }
    });

</script>

<style scoped>
.overlay-box {
	width: 100%;
	height: 400px;
  top: 0;
  left: 0;
  background: rgba(0,0,0,0.4);
  background-size: 3px 3px;
  z-index: 2;
}
.box:hover{
background: rgba(0,0,0,0.4);

}
</style>
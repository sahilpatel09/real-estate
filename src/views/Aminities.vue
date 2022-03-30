<template>
	<UniHead herotitle="Luxurious Aminities."
	herotext="3 BHK Luxurious apartments near you in Navarangpura. Samyak49 is the one of the modern and nice to decore flats in the Ahmedabad."
	heroimage="living.jpeg"
	/>

<Biwt/>

<section class="text-gray-600 body-font">
  <div class="container px-5 py-24 mx-auto">
    
      <div class="mx-auto sm:text-center lg:max-w-7xl">
    <div class="max-w-xl mb-10 md:mx-auto sm:text-center lg:max-w-2xl md:mb-12">
      <h2 class="max-w-lg mb-6 font-sans text-3xl font-bold leading-none tracking-tight text-gray-900 sm:text-4xl md:mx-auto">
        <span class="relative inline-block">
          <svg viewBox="0 0 52 24" fill="currentColor" class="absolute top-0 left-0 z-0 hidden w-32 -mt-8 -ml-20 text-blue-gray-100 lg:w-32 lg:-ml-28 lg:-mt-10 sm:block">
            <defs>
              <pattern id="5dc90b42-5ed4-45a6-8e63-2d78ca9d3d95" x="0" y="0" width=".135" height=".30">
                <circle cx="1" cy="1" r=".7"></circle>
              </pattern>
            </defs>
            <rect fill="url(#5dc90b42-5ed4-45a6-8e63-2d78ca9d3d95)" width="52" height="24"></rect>
          </svg>
          <span class="relative">The</span>
        </span>
        Specifications
      </h2>
      <p class="text-base text-gray-700 md:text-lg">
The term &quot;privilege&quot; describes a condition of opulence and elegance. Samyak49 is developed with
the intent of bringing grandeur in its finest, most basic form, combining elements of vitality, serenity,
suppleness, and an open-air lifestyle.

      </p>
    </div>
  </div>


    <div class="flex flex-wrap -m-4">



      <div class="p-4 md:w-1/3" v-for="item in specificationData" :key="item">
        <div class="h-full border-2 border-gray-200 border-opacity-60 rounded-lg overflow-hidden">
          <img class="lg:h-48 md:h-36 w-full object-cover object-center" :src="item.img" alt="blog">
          <div class="p-6">
            <img :src="item.logo" class="w-full h-20 object-cover" alt="">
            <h1 class="title-font text-lg font-medium text-gray-900 m-1 text-center">{{ item.title }}</h1>
            <p class="leading-relaxed mb-2 text-center" v-html="item.data">
            </p>
          </div>
        </div>
      </div>

          
    </div>
  </div>
</section>








<section class="text-gray-600 body-font bg-white">
  <div class="container px-5 mx-auto flex flex-wrap">

    <div class="flex flex-wrap md:-m-2 -m-1 flex-col md:flex-row">
      <div class="flex md:flex-wrap md:flex-row w-full flex-col md:w-1/2">

        <div class="md:p-2 p-1 w-full md:w-1/2 image-card relative">
          <img alt="gallery" class="w-full object-cover h-full object-center block transition duration-300" src="https://img.staticmb.com/mbimages/project/Photo_h310_w462/2020/01/29/Project-Photo-9-Samyak-49-Ahmedabad-5132013_545_1050_310_462.jpg">
          <div class="bottom">Gym Area
          </div>
        </div>

        <div class="md:p-2 p-1 w-full md:w-1/2 image-card relative">
          <img alt="gallery" 
          class="w-full object-cover h-full object-center" src="https://is1-3.housingcdn.com/012c1500/00e08a0fed7977a7becd8cbe001fbf7d/v0/medium.jpeg">
          <div class="bottom">Dining
          </div>
        </div>
        <div class="md:p-2 p-1 w-full image-card relative">
          <img alt="gallery" class="w-full object-cover h-full object-center" src="https://newprojects.99acres.com/projects/unknown/samyak_49/images/gyoh97fz.jpg">
          <div class="bottom">Playground
          </div>
        </div>
      </div>

      <div class="flex flex-wrap w-full md:w-1/2 flex-col md:flex-row">
        <div class="md:p-2 p-1 w-full relative image-card">
          <img alt="gallery" class="w-full h-full object-cover object-center block" src="https://newprojects.99acres.com/projects/unknown/samyak_49/images/gic02wqp_optOrig.jpg">
          <div class="bottom">Dining Area
          </div>
        </div>
        <div class="md:p-2 p-1 w-full md:w-1/2 image-card relative">
          <img alt="gallery" class="w-full object-cover h-full object-center block" src="https://teja12.kuikr.com/is/a/c/880x425/gallery_images/original/cf5d2d658495a7f.gif">
          <div class="bottom">Entrance 
          </div>
        </div>
        <div class="md:p-2 p-1 w-full md:w-1/2 image-card relative">
          <img alt="gallery" class="w-full object-cover h-full object-center block" src="https://is1-2.housingcdn.com/01c16c28/4ab28d8143ddc3f8d194fab77089d61f/v0/medium/3_bhk_apartment-for-sale-navrangpura-Ahmedabad-hall.jpg">
          <div class="bottom">Living Room
          </div>
        </div>
      </div>
    </div>
  </div>
</section>













<div class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
  <div class="mx-auto sm:text-center lg:max-w-7xl">
    <div class="max-w-xl mb-10 md:mx-auto sm:text-center lg:max-w-2xl md:mb-12">
      <div>
        <p class="inline-block px-3 py-px mb-4 text-xl font-semibold tracking-wider text-teal-900 rounded-full mon">
          SAMYAK 49
        </p>
      </div>
      <h2 class="max-w-lg mb-6 font-sans text-3xl font-bold leading-none tracking-tight text-gray-900 sm:text-4xl md:mx-auto">
        <span class="relative inline-block">
          <svg viewBox="0 0 52 24" fill="currentColor" class="absolute top-0 left-0 z-0 hidden w-32 -mt-8 -ml-20 text-blue-gray-100 lg:w-32 lg:-ml-28 lg:-mt-10 sm:block">
            <defs>
              <pattern id="5dc90b42-5ed4-45a6-8e63-2d78ca9d3d95" x="0" y="0" width=".135" height=".30">
                <circle cx="1" cy="1" r=".7"></circle>
              </pattern>
            </defs>
            <rect fill="url(#5dc90b42-5ed4-45a6-8e63-2d78ca9d3d95)" width="52" height="24"></rect>
          </svg>
          <span class="relative">The</span>
        </span>
        Floor Plan
      </h2>
      <p class="text-base text-gray-700 md:text-lg">
Samyak 49 offers you a premium location, a luxurious lifestyle with all utilities, beautiful construction, and numerous other features that distinguish Samyak 49 from the rivals.

      </p>
    </div>

    <div class="mb-4 mx-auto text-center lg:mb-6 flex flex-col md:flex-row items-center justify-center gap-5">
    
      <div class="flex flex-col transition-shadow duration-300 hover:shadow-xl">
        <h2 class="p-2 text-black text-lg">Block A</h2>
       <img class="object-cover w-full rounded shadow-lg" src="@/assets/floor-plan.jpg" alt="" /> 
      </div>
      <div class="flex flex-col transition-shadow duration-300 hover:shadow-xl">
        <h2 class="p-2 text-black text-lg">Block B</h2>
       <img class="object-cover w-full rounded shadow-lg" src="@/assets/block-b.jpg" alt="" /> 
      </div>

    </div>
    <div class="flex flex-row flex-wrap md:flex-nowrap">
      
      <TableA />
      <TableB />



    </div>
  </div>
</div>












        






<div class="relative px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
  
<div class="flex flex-col mb-16 sm:text-center sm:mb-0">
      
      <div class="max-w-xl mb-10 md:mx-auto sm:text-center lg:max-w-2xl md:mb-12">
        <h2 class="max-w-lg mb-6 font-sans text-3xl font-bold leading-none tracking-tight text-gray-900 sm:text-4xl md:mx-auto">
          <span class="relative inline-block">
            <span class="relative">The</span>
          </span>
          Ground Plan
        </h2>
        <p class="text-base text-gray-700 md:text-lg">
Samyak 49 offers you a premium location, a luxurious lifestyle with all utilities.
Check out the Ground plan for the site.
        </p>
      </div>
      <img
      class="object-cover w-full h-56 rounded shadow-lg lg:rounded-none lg:shadow-none sm:h-96 lg:h-full"
      src="@/assets/floor-plan.png"
      alt=""
    />
    </div>

<!--   <div class="absolute inset-x-0 top-0 items-center justify-center hidden overflow-hidden md:flex md:inset-y-0">
    <svg viewBox="0 0 88 88" class="w-full max-w-screen-xl text-indigo-100">
      <circle fill="lightblue" cx="90" cy="44" r="15.5"></circle>
      <circle fill-opacity="0.2" fill="lightgreen" cx="90" cy="44" r="44"></circle>
      <circle fill-opacity="0.2" fill="currentColor" cx="-90" cy="10" r="37.5"></circle>
      <circle fill-opacity="0.3" fill="currentColor" cx="44" cy="44" r="29.5"></circle>
      <circle fill-opacity="0.3" fill="currentColor" cx="44" cy="44" r="22.5"></circle>
    </svg>
  </div> -->


<div class="flex flex-col mb-16 sm:text-center sm:mb-0 mt-20">
      
      <div class="max-w-xl mb-10 md:mx-auto sm:text-center lg:max-w-2xl md:mb-12">
        <h2 class="max-w-lg mb-6 font-sans text-3xl font-bold leading-none tracking-tight text-gray-900 sm:text-4xl md:mx-auto">
          <span class="relative inline-block">
            <span class="relative">Our</span>
          </span>
          Salient Features
        </h2>
        <p class="text-base text-gray-700 md:text-lg">
Samyak 49 offers you a premium location, a luxurious lifestyle with all utilities.
Check out the Ground plan for the site.
        </p>
      </div>
      
    </div>






  
  <div class="relative grid gap-5 sm:grid-cols-2 lg:grid-cols-4">
    
    

    <div class="flex flex-col justify-between overflow-hidden text-left transition-shadow duration-200 bg-wine rounded shadow-xl group hover:shadow-2xl">
      <div class="p-5">
        <div class="flex items-center justify-center w-12 h-12 mb-4">
          <img src="@/assets/svg/security-system.svg" alt="">
        </div>
        <p class="mb-2 font-bold text-gray-100">Security</p>
        <p class="text-sm leading-5 text-white">
          Sed ut perspiciatis unde omnis iste. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </p>
      </div>
      <div class="w-full h-1 ml-auto duration-300 origin-left transform scale-x-0 bg-deep-purple-accent-400 group-hover:scale-x-100"></div>
    </div>



    <div class="flex flex-col justify-between overflow-hidden text-left transition-shadow duration-200 bg-wine rounded shadow-xl group hover:shadow-2xl">
      <div class="p-5">
        <div class="flex items-center justify-center w-12 h-12 mb-4">
          <img src="@/assets/svg/gym.svg" alt="Indoor gym">
        </div>
        <p class="mb-2 font-bold text-gray-100">Indoor Gym</p>
        <p class="text-sm leading-5 text-white">
          Sed ut perspiciatis unde omnis iste. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </p>
      </div>
      <div class="w-full h-1 ml-auto duration-300 origin-left transform scale-x-0 bg-deep-purple-accent-400 group-hover:scale-x-100"></div>
    </div>



    <div class="flex flex-col justify-between overflow-hidden text-left transition-shadow duration-200 bg-wine rounded shadow-xl group hover:shadow-2xl">
      <div class="p-5">
        <div class="flex items-center justify-center w-12 h-12 mb-4">
          <img src="@/assets/svg/common-plot.svg" alt="">
        </div>
        <p class="mb-2 font-bold text-gray-100">Common Plot</p>
        <p class="text-sm leading-5 text-white">
          Sed ut perspiciatis unde omnis iste. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </p>
      </div>
      <div class="w-full h-1 ml-auto duration-300 origin-left transform scale-x-0 bg-deep-purple-accent-400 group-hover:scale-x-100"></div>
    </div>



    <div class="flex flex-col justify-between overflow-hidden text-left transition-shadow duration-200 bg-wine rounded shadow-xl group hover:shadow-2xl">
      <div class="p-5">
        <div class="flex items-center justify-center w-12 h-12 mb-4">
          <img src="@/assets/svg/hall.svg" alt="">
        </div>
        <p class="mb-2 font-bold text-gray-100">Hall</p>
        <p class="text-sm leading-5 text-white">
          Sed ut perspiciatis unde omnis iste. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </p>
      </div>
      <div class="w-full h-1 ml-auto duration-300 origin-left transform scale-x-0 bg-deep-purple-accent-400 group-hover:scale-x-100"></div>
    </div>


    <div class="flex flex-col justify-between overflow-hidden text-left transition-shadow duration-200 bg-wine rounded shadow-xl group hover:shadow-2xl">
      <div class="p-5">
        <div class="flex items-center justify-center w-12 h-12 mb-4">
          <img src="@/assets/svg/gate.svg" alt="">
        </div>
        <p class="mb-2 font-bold text-gray-100">Entrance Gate</p>
        <p class="text-sm leading-5 text-white">
          Sed ut perspiciatis unde omnis iste. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </p>
      </div>
      <div class="w-full h-1 ml-auto duration-300 origin-left transform scale-x-0 bg-deep-purple-accent-400 group-hover:scale-x-100"></div>
    </div>


<div class="flex flex-col justify-between overflow-hidden text-left transition-shadow duration-200 bg-wine rounded shadow-xl group hover:shadow-2xl">
      <div class="p-5">
        <div class="flex items-center justify-center w-12 h-12 mb-4">
          <img src="@/assets/svg/waterbody.svg" alt="">
        </div>
        <p class="mb-2 font-bold text-gray-100">Water Body</p>
        <p class="text-sm leading-5 text-white">
          Sed ut perspiciatis unde omnis iste. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </p>
      </div>
      <div class="w-full h-1 ml-auto duration-300 origin-left transform scale-x-0 bg-deep-purple-accent-400 group-hover:scale-x-100"></div>
    </div>

    <div class="flex flex-col justify-between overflow-hidden text-left transition-shadow duration-200 bg-wine rounded shadow-xl group hover:shadow-2xl">
          <div class="p-5">
            <div class="flex items-center justify-center w-12 h-12 mb-4">
              <img src="@/assets/svg/electric.svg" alt="">
            </div>
            <p class="mb-2 font-bold text-gray-100">Electricity Room</p>
            <p class="text-sm leading-5 text-white">
              Sed ut perspiciatis unde omnis iste. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            </p>
          </div>
          <div class="w-full h-1 ml-auto duration-300 origin-left transform scale-x-0 bg-deep-purple-accent-400 group-hover:scale-x-100"></div>
        </div>


        <div class="flex flex-col justify-between overflow-hidden text-left transition-shadow duration-200 bg-wine rounded shadow-xl group hover:shadow-2xl">
              <div class="p-5">
                <div class="flex items-center justify-center w-12 h-12 mb-4">
                  <img src="@/assets/svg/parking.svg" alt="">
                </div>
                <p class="mb-2 font-bold text-gray-100">Basement Parking</p>
                <p class="text-sm leading-5 text-white">
                  Sed ut perspiciatis unde omnis iste. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                </p>
              </div>
              <div class="w-full h-1 ml-auto duration-300 origin-left transform scale-x-0 bg-deep-purple-accent-400 group-hover:scale-x-100"></div>
            </div>


    
    
  </div>
</div>







<div class="relative flex bg-wine flex-col py-16 lg:pt-0 lg:flex-col lg:pb-0">
  <div class="flex flex-col items-start w-full max-w-xl px-4 mx-auto lg:px-8 lg:max-w-screen-xl">
    <div class="mb-16 lg:my-40 lg:max-w-lg lg:pr-5">
      <div class="max-w-xl mb-6">
        <div>
          <p class="inline-block mb-4 text-xs font-semibold tracking-wider text-teal-900 uppercase rounded-full text-gray-100">
            What we have used in your dream home
          </p>
        </div>
        <h2 class="max-w-lg mb-6 font-sans text-3xl font-bold tracking-tight sm:text-4xl sm:leading-none text-white">
          Premium Range of Products
        </h2>
        <p class="text-base text-gray-200 md:text-lg">
          The Samyak49 is a project that offers astoundingly promising golden prospects, ample connectivity,
leisurely and peaceful leisure, long-term sustainability, and complementary financial appreciation.
The skilled architects have developed an outstanding blend of contemporary style with certified
luxury.
        </p>
      </div>
      <div class="flex flex-col items-center md:flex-row">
        <router-link
          to="/contact-us"
          class="inline-flex items-center justify-center w-full h-12 px-6 mb-3 font-medium tracking-wide text-white transition duration-200 rounded shadow-md md:w-auto md:mr-4 md:mb-0 bg-indigo-600 hover:bg-indigo-900 focus:shadow-outline focus:outline-none"
        >
          Contact us
        </router-link>
      </div>

    </div>
  </div>
  <div class="inset-y-0 right-0 w-full max-w-xl px-4 mx-auto lg:pl-8 lg:pr-0 lg:mb-0 lg:mx-0 lg:w-1/2 lg:max-w-full lg:absolute xl:px-0">
    <video 
    class=" w-full h-56 rounded shadow-lg lg:rounded-none lg:shadow-none sm:h-96 lg:h-full"
    src="@/assets/about.mp4" autobuffer autoloop loop controls poster="@/assets/living.jpeg"></video>
    <!-- <img
      class="object-cover w-full h-56 rounded shadow-lg lg:rounded-none lg:shadow-none sm:h-96 lg:h-full"
      src="@/assets/providers.jpg"
      alt=""
    /> -->
  </div>
</div>





<div class="flex flex-col items-center justify-center max-w-2xl px-4 pt-16 mx-auto sm:max-w-xl md:max-w-2xl lg:pt-32 md:px-8">
  <div class="max-w-xl mb-10 md:mx-auto sm:text-center lg:max-w-2xl md:mb-12">
    <div>
      <p class="inline-block px-3 py-px mb-4 text-xs font-semibold tracking-wider text-teal-900 uppercase rounded-full bg-teal-accent-400">
        SAMYAK 49
      </p>
    </div>
    <h2 class="max-w-lg mb-6 font-sans text-3xl font-bold leading-none tracking-tight text-gray-900 sm:text-4xl md:mx-auto">
      3D View of The Apartment
    </h2>
    <p class="text-base text-gray-700 md:text-lg">
      To have a better clearity of the apartments, we have build you a 3D view.
    </p>
  </div>

</div>
<img src="@/assets/plan.png" class="w-full mx-auto" alt="" />




<AminitiesIcons />




<div class="relative flex flex-col-reverse py-16 lg:py-0 lg:flex-col border-2 shadow-2xl">
  <div class="w-full max-w-xl px-4 mx-auto md:px-0 lg:px-8 lg:py-20 lg:max-w-screen-xl">
    <div class="lg:my-10 lg:max-w-lg lg:pr-5">
      <p class="inline-block mb-4 text-xs font-semibold tracking-wider text-teal-900 uppercase rounded-full bg-teal-accent-400">
      Visit us for the inquiry.
      </p>
      <h2 class="mb-5 font-sans text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none">
        Reach us.
      </h2>
      <p class="pr-5 mb-5 text-base text-gray-700 md:text-lg">
We are situated in the heart of the city of the Ahmedabad. Please do visit the location for overlook of the spacious 3BHK high-end living apartments. 
      </p>
      <div class="flex items-center">
        <router-link
          to="/contact-us"
          class="inline-flex items-center justify-center h-12 px-6 mr-6 font-medium tracking-wide text-white transition duration-200 rounded shadow-md bg-wine focus:shadow-outline focus:outline-none"
        >
          Contact us
        </router-link>
      </div>
    </div>
  </div>
  <div class="inset-y-0 top-0 right-0 w-full max-w-xl px-4 mx-auto mb-6 md:px-0 lg:pl-8 lg:pr-0 lg:mb-0 lg:mx-0 lg:w-1/2 lg:max-w-full lg:absolute xl:px-0">
    <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d14686.944542478008!2d72.5591935!3d23.0334586!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xc562d20ed1dbfefc!2sSamyak%2049!5e0!3m2!1sen!2sin!4v1648371094745!5m2!1sen!2sin"  allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade" class="object-cover w-full h-56 rounded shadow-lg lg:rounded-none lg:shadow-none md:h-96 lg:h-full"></iframe>


  </div>
</div>
























	<Footer/>
</template>
<script setup>
import UniHead from '../components/UniversalHead.vue'
import Biwt from '../components/aminities/BuildingImageWithText.vue'
import Footer from '../components/Footer.vue'
import AminitiesIcons from '../components/aminities/AminitiesIcons.vue'
import TableA from '../components/aminities/TableA.vue'
import TableB from '../components/aminities/TableB.vue'
import { ref } from 'vue'
const specificationData = ref({
  0:{
    img: require('@/assets/contact.png'),
    logo:require('@/assets/images/brands/qutone.jpeg'),
    title: "Flooring",
    data: "Quotone Tiles <br/>1200 X 1200 Vitrified Mirror Polished Tiles"
  },
  1:{
    img: require('@/assets/images/kitchen-area.jpeg'),
    logo:require('@/assets/images/brands/franke.jpeg'),
    title: "Kitchen",
    data: "Franke SS Matt Finish Sink<br/>Kohler Premium Fittings<br/>Granite Platform<br/>Kota stone tack in store room."
  },
  2:{
    img: require('@/assets/images/door.jpg'),
    logo:require('@/assets/images/brands/aluk.jpeg'),
    title: "Doors & Windows",
    data: "Ghana Sagvan Wood Frame<br/>Doors With Laminates<br/>Aluk Italian Aluminium Anodise<br/>Premium SS Heavy Door Hindges/Handles"
  },
  3:{
    img: require('@/assets/images/bathroom.png'),
    logo:require('@/assets/images/brands/kohler.png'),
    title: "Bathrooms & Plumbing",
    data: "Quotone Vitrified Tiles Dado upto Lintel Level<br/>Floor with Anti Skid Tiles<br/>Kohler Premium Series Fittings<br/>Kohler Premium Frameless Sanitaryware "
  },
  4:{
    img: require('@/assets/images/craptree.jpg'),
    logo:require('@/assets/images/brands/crabtree.jpeg'),
    title: "CrabTree",
    data: "CrabTree Universal Type Switches"
  },
  5:{
    img: require('@/assets/images/ac.jpg'),
    logo:require('@/assets/images/brands/mitsubishi.jpeg'),
    title: "Air Conditioner",
    data: "Mitsubishi Heavy Industrial Split & VRF High wall Air Conditioner"
  },
  

})
</script>

<style>
.box:hover{
background: rgba(0,0,0,0.4);

}
</style>
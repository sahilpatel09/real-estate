<template>
	<UniHead herotitle="Contact us"
	herotext="3 BHK Luxurious apartments near you in Navarangpura. Samyak49 is the one of the modern and nice to decore flats in the Ahmedabad."
	heroimage="contact.png"
	/>

<section class="text-gray-600 body-font relative">
  <div class="container px-5 py-24 mx-auto flex sm:flex-nowrap flex-wrap">
    <div class="lg:w-2/3 md:w-1/2 bg-gray-900 rounded-lg overflow-hidden sm:mr-10 md:p-10 flex items-end justify-start relative w-full">
      <iframe width="100%" height="100%" class="md:absolute md:h-full h-96 inset-0" frameborder="0" title="map" marginheight="0" marginwidth="0" scrolling="no" src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d14686.944542478008!2d72.5591935!3d23.0334586!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xc562d20ed1dbfefc!2sSamyak%2049!5e0!3m2!1sen!2sin!4v1648301524566!5m2!1sen!2sin"></iframe>

      <div class="hidden md:block bg-white relative bg-wine flex flex-wrap py-6 rounded shadow-md">
        <div class=" px-6">
          <h2 class="title-font font-semibold text-gray-200 tracking-widest text-xs">ADDRESS</h2>
          <p class="mt-1 text-white">Near Vallabha Dinning Hall Digamber Jain Derasar Lane Girish Coldrink Cross Road, Chimanlal Girdharlal Rd, Navrangpura, Ahmedabad, Gujarat 380009</p>
        </div>
        <div class="lg:w-1/2 px-6 mt-4 lg:mt-0">
          <h2 class="title-font font-semibold text-gray-900 tracking-widest text-xs">EMAIL</h2>
          <a class="leading-relaxed text-gray-100">info@samyak49.com</a>
          <h2 class="title-font font-semibold text-gray-100 tracking-widest text-xs mt-4">PHONE</h2>
          <p class="leading-relaxed text-white">+91 98253 04692</p>
        </div>
      </div>
    </div>
    <div class="lg:w-1/3 md:w-1/2 bg-white flex flex-col md:ml-auto w-full md:py-8 mt-8 md:mt-0">
      <h2 class="text-gray-900 text-lg mb-1 font-medium title-font">Feedback & Inquiry</h2>
      <p class="leading-relaxed mb-5 text-gray-600">Post-ironic portland shabby chic echo park, banjo fashion axe</p>
      <div class="relative mb-4">
        <label for="name" class="leading-7 text-sm text-gray-600">Name</label>
        <input type="text" id="name" name="name" class="w-full bg-white rounded border border-gray-300 focus:border-indigo-500 focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
      </div>
      <div class="relative mb-4">
        <label for="email" class="leading-7 text-sm text-gray-600">Email</label>
        <input type="email" id="email" name="email" class="w-full bg-white rounded border border-gray-300 focus:border-indigo-500 focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
      </div>
      <div class="relative mb-4">
        <label for="message" class="leading-7 text-sm text-gray-600">Message</label>
        <textarea id="message" name="message" class="w-full bg-white rounded border border-gray-300 focus:border-indigo-500 focus:ring-2 focus:ring-indigo-200 h-32 text-base outline-none text-gray-700 py-1 px-3 resize-none leading-6 transition-colors duration-200 ease-in-out"></textarea>
      </div>
      <button class="text-white bg-indigo-500 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded text-lg">Send Message</button>
      <p class="text-xs text-gray-500 mt-3">Chicharrones blog helvetica normcore iceland tousled brook viral artisan.</p>
    </div>
  </div>
</section>



	<Footer/>
</template>
<script setup>
import UniHead from '../components/UniversalHead.vue'
import Footer from '../components/Footer.vue'
</script>
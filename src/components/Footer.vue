<template>
	<footer class="text-gray-600 body-font bg-wine">
  <div class="container px-20 py-24 mx-auto flex md:items-center lg:items-start md:flex-row md:flex-nowrap flex-wrap flex-col">
    <div class="w-64 flex-shrink-0 md:mx-0 mx-auto text-center md:text-left">
      <a class="flex title-font font-medium items-center md:justify-start justify-center text-gray-900">
        <img src="@/assets/invert.png" class="" />
      </a>
      <p class="mt-2 text-sm text-gray-200 text-center">
      3BHK Living Houses

</p>
    </div>
    <div class="flex-grow flex flex-wrap md:pl-20 -mb-10 md:mt-0 mt-10 md:text-left text-center">
      <div class="lg:w-1/4 md:w-1/2 w-full px-4">
        <h2 class="title-font font-medium text-white tracking-widest text-sm mb-3">Links</h2>
        <nav class="list-none mb-10">
          <li>
            <router-link to="/aminities" class="text-gray-300 hover:text-gray-100">Aminities</router-link>
          </li>
          <li>
            <router-link to="/gallery" class="text-gray-300 hover:text-gray-100">Gallery</router-link>
          </li>
          <li>
            <router-link to="/about" class="text-gray-300 hover:text-gray-100">About</router-link>
          </li>
          <li>
            <router-link to="/" class="text-gray-300 hover:text-gray-100">Home</router-link>
          </li>
        </nav>
      </div>
      <div class="lg:w-1/4 md:w-1/2 w-full px-4">
        <h2 class="title-font font-medium text-white tracking-widest text-sm mb-3">External Link</h2>
        <nav class="list-none mb-10">
          <li>
            <a class="text-gray-300 hover:text-gray-100" href="/gallery">Videos</a>
          </li>
          <li>
            <a class="text-gray-300 hover:text-gray-100" href="https://apexa.in/">Apexa Group</a>
          </li>
          <li>
            <a class="text-gray-300 hover:text-gray-100" href="https://khushroo.in/">Khushroo Residency</a>
          </li>
          <li>
            <a class="text-gray-300 hover:text-gray-100" href="https://drive.google.com/file/d/1ftzOGnEHTOTMRfdA_6SypGNbH1ZQ1Nf4/view?usp=sharing">Brochure</a>
          </li>
        </nav>
      </div>      

      <div class="lg:w-1/2 w-full px-4">
        <span class="text-base font-medium tracking-wide text-gray-300">Get a call back.</span>
        <form class="flex flex-col mt-4 md:flex-row">
          <input
            placeholder="Mobile"
            required=""
            type="text"
            class="flex-grow w-full h-12 px-4 mb-3 bg-gray-900 transition duration-200 bg-white border border-gray-300 rounded shadow-sm appearance-none md:mr-2 md:mb-0 focus:border-deep-purple-accent-400 focus:outline-none focus:shadow-outline"
          />
          <button
            type="submit"
            class="inline-flex items-center justify-center h-12 px-6 font-medium tracking-wide text-white transition duration-200 rounded shadow-md bg-deep-purple-accent-400 hover:bg-deep-purple-accent-700 focus:shadow-outline focus:outline-none"
          >
            Call
          </button>
        </form>
        <p class="mt-4 text-sm text-gray-300">
          We will call you as soon as possible.
        </p>
      </div>


    </div>
  </div>
  <div class="bg-wine-dark px-20">
    <div class="container mx-auto py-4 px-5 flex flex-wrap flex-col sm:flex-row">
      <p class="text-white text-sm text-center sm:text-left">© {{ new Date().getFullYear() }} SAMYAK49 — All Rights Reserved.
      </p>
      <span class="inline-flex sm:ml-auto sm:mt-0 mt-2 justify-center sm:justify-start">
        <a class="text-gray-200">
          <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
            <path d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z"></path>
          </svg>
        </a>
        <a class="ml-3 text-gray-300">
          <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
            <rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect>
            <path d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01"></path>
          </svg>
        </a>
      </span>
    </div>
  </div>
</footer>
</template>

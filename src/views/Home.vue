<template>
<Newhead />
<Aminities />
<title>Real-Estate</title>
<AminitiesIcons />
<BrandsIcons/>

<div class="relative flex flex-col-reverse py-16 lg:py-0 lg:flex-col border-2 shadow-2xl">
  <div class="w-full max-w-xl px-4 mx-auto md:px-0 lg:px-8 lg:py-20 lg:max-w-screen-xl">
    <div class="lg:my-10 lg:max-w-lg lg:pr-5">
      <p class="inline-block mb-4 text-xs font-semibold tracking-wider text-teal-900 uppercase rounded-full bg-teal-accent-400">
        Easy EMI & Loan Options
      </p>
      <h2 class="mb-5 font-sans text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none">
        Loans Approved<br class="hidden md:block" />
        By
        <span class="inline-block wine m-1">Major Banks</span>
      </h2>
      <p class="pr-5 mb-5 text-base text-gray-700 md:text-lg">
        We have got your back by getting all the najor banks on board for financing the purchase. Financing was never really easy.
      </p>
      <div class="flex items-center">
        <button
          @click="this.$store.state.isHidden = !this.$store.state.isHidden"
          class="inline-flex items-center justify-center h-12 px-6 mr-6 font-medium tracking-wide text-white transition duration-200 rounded shadow-md bg-wine focus:shadow-outline focus:outline-none"
        >
          Get a Call Back
        </button>
      </div>
    </div>
  </div>
  <div class="inset-y-0 top-0 right-0 w-full max-w-xl px-4 mx-auto mb-6 md:px-0 lg:pl-8 lg:pr-0 lg:mb-0 lg:mx-0 lg:w-1/2 lg:max-w-full lg:absolute xl:px-0">
    <img src="https://media.istockphoto.com/photos/financial-advisor-with-indian-family-picture-id1146830235?k=20&m=1146830235&s=612x612&w=0&h=eqjQWVzejEYBVlqnDR4qCccxNBgOq9t0FKfwt0ydAl4=" class="object-cover w-full h-56 rounded shadow-lg lg:rounded-none lg:shadow-none md:h-min p-5 shadow-xl lg:h-full" />


  </div>
</div>


<Popup @open-popup="popIt" :class="{ 'hidden': this.$store.state.isHidden }"/>
<Footer/>
</template>

<script>
import Aminities from '../components/Aminities.vue'
import Newhead from '../components/Header_new.vue'
import Footer from '../components/Footer.vue'
import AminitiesIcons from '../components/aminities/AminitiesIcons.vue'
import BrandsIcons from '../components/BrandsIcons.vue'
import Popup from '../components/Popup.vue'

export default {
  name: 'HelloWorld',
  components:{
    Aminities,
    Newhead,Footer,
    AminitiesIcons,
    BrandsIcons,
    Popup
  },
  data(){
    return{
      isHidden: true
    };
  },
  head: {
    title: {
      inner: 'It will be a pleasure'
    },
  },
  metainfo(){
    return {
      title: "Real Estate"
    }
  },
  methods: {
    popIt() {
      console.log("This is the event")
    },
  }
}

</script>

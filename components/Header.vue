<template>

    <!-- Main Nav Container -->
    <nav class="z-50 h-auto w-full xl:px-10 bg-gray-700 flex flex-wrap items-center justify-between 
    navbar-expand-lg fixed">
        <!-- Container Holds All of the Content -->
        <div class="container mx-auto flex flex-wrap items-center pt-2 rounded-b-xl"
        v-bind:class="{'bg-transparent': !showMenu, 'bg-gray-700': showMenu}">

            <!-- Content on Left Side and Mobile Dropdown Button -->
            <div class="w-full relative flex justify-between lg:w-auto lg:block lg:justify-start">
                <NuxtLink
                class="link text-yellow-400 text-3xl lg:text-4xl font-bold leading-relaxed inline-block m-3 p-2" 
                to="#home"
                >Gold Cuts
                </NuxtLink>
                <button 
                class="mr-10 text-white hover:text-yellow-400 cursor-pointer text-xl leading-none border border-solid border-transparent 
                rounded bg-transparent block lg:hidden outline-none focus:outline-none" 
                v-on:click="toggleNavbar()"
                >
                <fa-icon class="text-4xl" :icon="['fas','bars']" />
                </button>
            <!-- Content on Left Side and Mobile Dropdown Button -->
            </div>
            <!-- Content on Right Side of Screen -->
            <div 
            v-bind:class="{'hidden': !showMenu, 'flex': showMenu}" 
            class="lg:flex lg:flex-grow flex-col 2xl:text-xl mx-5 pb-5 lg:pb-0"
            >
                <!-- List of Links -->
                <ul class="flex flex-col lg:flex-row tracking-widest lg:ml-auto">
                    <li class="">
                        <NuxtLink 
                        class="link flex items-center lg:mx-6 lg:mr-2 lg:ml-1 my-2 px-5 lg:px-1 lg:py-2 text-md font-bold text-white hover:text-yellow-400" 
                        to="#about"
                        >About
                        </NuxtLink> 
                    </li>
                    <li class="">
                        <NuxtLink 
                        class="link flex items-center lg:mx-6 lg:mr-2 lg:ml-1 my-2 px-5 lg:px-1 lg:py-2 text-md font-bold text-white hover:text-yellow-400" 
                        to="#barber"
                        >Barbers
                        </NuxtLink>
                    </li>
                    <li class="">
                        <NuxtLink 
                        class="link flex items-center lg:mx-6 lg:mr-2 lg:ml-1 my-2 px-5 lg:px-1 lg:py-2 text-md font-bold text-white hover:text-yellow-400" 
                        to="#contact"
                        >Contact
                        </NuxtLink>
                    </li>
                    <li class="">
                        <a 
                        class="flex items-center lg:mx-6 lg:mr-2 lg:ml-1 my-2 px-5 lg:px-1 lg:py-2 text-md font-bold text-white hover:text-yellow-400" 
                        href="https://booksy.com/en-us/390352_gold-cuts_barber-shop_18229_chicago"
                        >Book Now
                        </a>
                    </li>
                </ul>

            <!-- Content on Right Side of Screen -->
            </div>
        <!-- Container Holds All of the Content -->     
        </div>
    <!-- Main Nav Container -->
    </nav>
</template>

<script>

export default {
  
  data() {

    return {
      showMenu: false,
    }
  },

  methods: {
    toggleNavbar: function(){
      this.showMenu = !this.showMenu;
    }
  },

  // Hides menu when an option is clicked
  watch: {
        '$route' () {
            this.showMenu = false
        }
    },

 
}
</script>
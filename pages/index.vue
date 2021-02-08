<template>
  <div class="bg-gray-200 pb-20">

    <!-- Carousel -->
    <div class="carousel relative shadow-2xl pt-24">
      <div class="carousel-inner relative overflow-hidden w-full">


        <!--Slide 1-->
        <input class="carousel-open" type="radio" id="carousel-1" name="carousel" aria-hidden="true" hidden="" checked="checked">
        <div class="carousel-item absolute opacity-0" style="height:80vh;">
          <div 
            class="block h-full w-full bg-cover bg-center text-white text-5xl text-center"
            style='background-image: url("../slide-1.jpg");'
            >
          </div>
        </div>
        <label for="carousel-3" class="prev control-1 w-10 h-10 ml-2 md:ml-10 absolute cursor-pointer hidden text-3xl font-bold text-yellow-400 hover:text-gray-700 rounded-full bg-gray-800 hover:bg-yellow-400 leading-tight text-center z-10 inset-y-0 left-0 my-auto">‹</label>
        <label for="carousel-2" class="next control-1 w-10 h-10 mr-2 md:mr-10 absolute cursor-pointer hidden text-3xl font-bold text-yellow-400 hover:text-gray-700 rounded-full bg-gray-800 hover:bg-yellow-400 leading-tight text-center z-10 inset-y-0 right-0 my-auto">›</label>
          

        <!--Slide 2-->
        <input class="carousel-open" type="radio" id="carousel-2" name="carousel" aria-hidden="true" hidden="">
        <div class="carousel-item absolute opacity-0" style="height:80vh;">
          <div 
            class="block h-full w-full bg-cover bg-center text-white text-5xl text-center"
            style='background-image: url("../slide-2.jpg");'
            >
          </div>
        </div>
        <label for="carousel-1" class="prev control-2 w-10 h-10 ml-2 md:ml-10 absolute cursor-pointer hidden text-3xl font-bold text-yellow-400 hover:text-gray-700 rounded-full bg-gray-800 hover:bg-yellow-400 leading-tight text-center z-10 inset-y-0 left-0 my-auto">‹</label>
        <label for="carousel-3" class="next control-2 w-10 h-10 mr-2 md:mr-10 absolute cursor-pointer hidden text-3xl font-bold text-yellow-400 hover:text-gray-700 rounded-full bg-gray-800 hover:bg-yellow-400 leading-tight text-center z-10 inset-y-0 right-0 my-auto">›</label> 
          
          
        <!--Slide 3-->
        <input class="carousel-open" type="radio" id="carousel-3" name="carousel" aria-hidden="true" hidden="">
        <div class="carousel-item absolute opacity-0" style="height:80vh;">
          <div 
            class="block h-full w-full bg-cover bg-center text-white text-5xl text-center"
            style='background-image: url("../slide-3.jpg");'
            >
          </div>
        </div>

        <label for="carousel-2" class="prev control-3 w-10 h-10 ml-2 md:ml-10 absolute cursor-pointer hidden text-3xl font-bold text-yellow-400 hover:text-gray-700 rounded-full bg-gray-800 hover:bg-yellow-400 leading-tight text-center z-10 inset-y-0 left-0 my-auto">‹</label>
        <label for="carousel-1" class="next control-3 w-10 h-10 mr-2 md:mr-10 absolute cursor-pointer hidden text-3xl font-bold text-yellow-400 hover:text-gray-700 rounded-full bg-gray-800 hover:bg-yellow-400 leading-tight text-center z-10 inset-y-0 right-0 my-auto">›</label>

        <!-- Add additional indicators for each slide-->
        <ol class="carousel-indicators">
          <li class="inline-block mr-3 mt-40">
            <label for="carousel-1" class="carousel-bullet cursor-pointer block text-4xl text-white hover:text-yellow-400">•</label>
          </li>
          <li class="inline-block mr-3">
            <label for="carousel-2" class="carousel-bullet cursor-pointer block text-4xl text-white hover:text-yellow-400">•</label>
          </li>
          <li class="inline-block mr-3">
            <label for="carousel-3" class="carousel-bullet cursor-pointer block text-4xl text-white hover:text-yellow-400">•</label>
          </li>
        </ol>
      </div>

    <!-- Carousel -->
    </div>

    <!-- First Section -->
    <section>
      <div class="flex flex-col lg:flex-row md:px-10 xl:px-20 2xl:px-32">
        <!-- Left Side -->
        <div class="text-center px-5 md:px-0 lg:w-2/3 xl:w-3/4">
          <h3
            class="mt-20 md:mb-3 text-gray-700 font-bold tracking-wider text-4xl sm:text-5xl"
            >Gold Cuts Barber Shop
          </h3>
          <hr class="">
          <div class="">
            <p
              class="tracking-wide text-gray-600 mt-5 whitespace-pre-line text-lg sm:text-xl md:text-2xl"
              >Gold Cuts first opened in October of 2014 and has 
              quickly become well known around Chicago, Illinois. 
              We offer a classic barber shop experience while 
              providing a range of classic and modern barber 
              services. If you are in need of a classic cut, 
              a clean face, or whatever it is you are looking for. 
              <NuxtLink to="/" class="text-yellow-400 font-bold text-xl sm:text-2xl md:text-3xl">Gold Cuts</NuxtLink> has you covered.
            </p>
            <p
              class="tracking-wide text-gray-600 mt-5 whitespace-pre-line text-lg sm:text-xl md:text-2xl"
              >We continue to stress the importance of preventing 
              the spread of infection and ask for you to follow the 
              information being circulated by healthcare officials.
            </p>
            <div class="mt-8 mb-20 lg:mb-5">
              <a
                href="/"
                class="uppercase py-1 px-2 font-semibold tracking-wide text-gray-700 hover:text-yellow-400 focus:text-yellow-500
                text-xl sm:text-2xl md:text-3xl"
                >Book An Appointment
              </a>
            </div>
          </div>
        </div>
        <!-- Right Side -->
        <div class="lg:w-1/3 xl:w-7/12 xl:p-10 lg:my-auto lg:p-2 xl:p-0 lg:mr-3 xl:mr-0">
            <img
              alt="..."
              src="../static/article1.jpg"
              class="h-80 lg:h-96 w-full md:rounded-xl shadow-lg"
            />
        </div>
      </div>
    </section>
    
  </div>
</template>

<style>
			.carousel-open:checked + .carousel-item {
				position: static;
				opacity: 100;
			}
			.carousel-item {
				-webkit-transition: opacity 0.6s ease-out;
				transition: opacity 0.6s ease-out;
			}
			#carousel-1:checked ~ .control-1,
			#carousel-2:checked ~ .control-2,
			#carousel-3:checked ~ .control-3 {
				display: block;
			}
			.carousel-indicators {
				list-style: none;
				margin: 0;
				padding: 0;
				position: absolute;
				bottom: 2%;
				left: 0;
				right: 0;
				text-align: center;
				z-index: 10;
			}
			#carousel-1:checked ~ .control-1 ~ .carousel-indicators li:nth-child(1) .carousel-bullet,
			#carousel-2:checked ~ .control-2 ~ .carousel-indicators li:nth-child(2) .carousel-bullet,
			#carousel-3:checked ~ .control-3 ~ .carousel-indicators li:nth-child(3) .carousel-bullet {
				color: #fbbf24;  /*Set to match the Tailwind colour you want the active one to be */
			}
		</style>
<template>
  <div class="bg-gray-200">

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

    <!-- First Section/ About Company-->
    <section>
      <div class="flex flex-col lg:flex-row pb-20 lg:py-20 md:px-10 xl:px-20 2xl:px-32 bg-gradient-to-b from-gray-200 to-gray-400">
        <!-- Left Side -->
        <div class="text-center px-5 md:px-0 lg:w-2/3 xl:w-3/4">
          <h3
            class="mt-20 mb-10 lg:mb-3 text-gray-700 font-bold tracking-wider text-4xl sm:text-5xl"
            >Gold Cuts Barber Shop
          </h3>
          <div class="">
            <p
              class="tracking-wide text-gray-600 mt-5 text-lg sm:text-xl md:text-2xl whitespace-pre-line"
              >Gold Cuts first opened in 2017 and has quickly 
              become well known around Chicago, Illinois. We 
              offer a classic barber shop experience, while also 
              offering you a fun and laid back atmosphere. We 
              take pride in bringing Old School and New School 
              Styles to the Golden Light! Come in and enjoy a 
              great haircut, a hot towel cleansing and come out 
              <a href="https://booksy.com/en-us/390352_gold-cuts_barber-shop_18229_chicago" class="hover:text-yellow-400 italic hover:font-bold text-xl sm:text-2xl md:text-3xl">Golden Crisp</a>. We got you covered.
            </p>
            <p
              class="tracking-wide text-gray-600 mt-5 whitespace-pre-line text-lg sm:text-xl md:text-2xl"
              >We continue to stress the importance of preventing 
              the spread of infection and ask for you to follow the 
              information being circulated by healthcare officials.
            </p>
            <div class="mt-8 mb-20 lg:mb-5">
              <a
                href="https://booksy.com/en-us/390352_gold-cuts_barber-shop_18229_chicago"
                class="uppercase py-1 px-2 font-semibold tracking-wide text-gray-700 hover:text-yellow-400 focus:text-yellow-500
                text-xl sm:text-2xl md:text-3xl"
                >Book An Appointment
              </a>
            </div>
          </div>
        </div>
        <!-- Right Side -->
        <div class="md:mx-auto md:w-3/4 lg:w-1/3 xl:w-7/12 xl:p-10 lg:my-auto lg:p-2 xl:p-0 lg:mr-3 xl:mr-0">
          <div class="">
            <img
              alt="..."
              src="article1.jpg"
              class="h-80 lg:h-96 w-full md:rounded-md shadow-lg"
            />
          </div>
        </div>
      </div>
    </section>

    <!-- Second Section/ Barbers and Contact -->
    <section>
      <div 
        class="h-full bg-fixed bg-center bg-cover"
        style='background-image: url("../section-22.jpg");'
        >
        <div class="">
          <h2
            class="pt-20 p-10 text-6xl font-bold uppercase text-center text-gray-800"
            >Barbers
          </h2>
        </div>

        <div class="py-10 px-5 flex flex-col lg:flex-row items-center lg:justify-center lg:flex-wrap">
          <!-- Barber 1 -->
          <div class="flex justify-center w-full md:w-6/12 lg:w-3/12 mb-10">
            <div class="items-center flex flex-col bg-gradient-to-b from-gray-400 to-gray-200 p-1 shadow-lg">
              <img 
                src="junior.jpg"
                alt=""
                class="h-96 w-96 lg:h-52 lg:w-52 xl:h-64 xl:w-64 2xl:w-72 2xl:h-72 rounded-md shadow-lg"
              />
              <div class="text-center text-gray-700">
                <h5
                  class="mt-2 text-2xl font-bold"
                  >Junior
                </h5>
                <div class="my-1">
                  <a
                    href="https://booksy.com/en-us/390352_gold-cuts_barber-shop_18229_chicago/staffer/331840"
                    class="uppercase font-medium text-lg text-gray-700 hover:text-yellow-400 font-thin border-2 border-gray-700 hover:border-yellow-500 hover:bg-gray-100 rounded-md p-1"
                    >Book Now
                  </a>
                </div>
              </div>
            </div>
          </div>
          <!-- Barber 2 -->
          <div class="flex justify-center w-full md:w-6/12 lg:w-3/12 mb-10">
            <div class="items-center flex flex-col bg-gradient-to-b from-gray-400 to-gray-200 p-1 shadow-lg">
              <img 
                src="adrian.jpg"
                alt=""
                class="h-96 w-96 lg:h-52 lg:w-52 xl:h-64 xl:w-64 2xl:w-72 2xl:h-72 rounded-md shadow-lg"
              />
              <div class="text-center text-gray-700">
                <h5
                  class="mt-2 text-2xl font-bold"
                  >Adrian
                </h5>
                <div class="my-1">
                  <a
                    href="https://booksy.com/en-us/390352_gold-cuts_barber-shop_18229_chicago/staffer/367500"
                    class="uppercase font-medium text-lg text-gray-700 hover:text-yellow-400 font-thin border-2 border-gray-700 hover:border-yellow-500 hover:bg-gray-100 rounded-md p-1"
                    >Book Now
                  </a>
                </div>
              </div>
            </div>
          </div>
          <!-- Barber 3 -->
          <div class="flex justify-center w-full md:w-6/12 lg:w-3/12 mb-10">
            <div class="items-center flex flex-col bg-gradient-to-b from-gray-400 to-gray-200 p-1 shadow-lg">
              <img 
                src="brandon.jpg"
                alt=""
                class="h-96 w-96 lg:h-52 lg:w-52 xl:h-64 xl:w-64 2xl:w-72 2xl:h-72 rounded-md shadow-lg"
              />
              <div class="text-center text-gray-700">
                <h5
                  class="mt-2 text-2xl font-bold"
                  >Brandon
                </h5>
                <div class="my-1">
                  <a
                    href="https://booksy.com/en-us/390352_gold-cuts_barber-shop_18229_chicago/staffer/279719"
                    class="uppercase font-medium text-lg text-gray-700 hover:text-yellow-400 font-thin border-2 border-gray-700 hover:border-yellow-500 hover:bg-gray-100 rounded-md p-1"
                    >Book Now
                  </a>
                </div>
              </div>
            </div>
          </div>
        
        </div>


      
      </div>
    </section>

    <!-- Prices for Cuts -->
    <section>
      <div class="bg-gradient-to-b from-gray-400 to-gray-700">
        <div class="flex flex-col lg:flex-row pb-20 lg:py-20 md:px-10 xl:px-20 2xl:px-32">
          <!-- Left Side/ Icon or Picture -->
          <div class="w-1/2 flex justify-center">
            <img 
              class="hidden lg:inline-block md:rounded-md shadow-lg h-96 w-80 my-auto"
              src="priceimage.jpg"
              alt=""
            >
          </div>
          <!-- Right Side/ Prices -->
          <div class="lg:w-2/3 xl:w-1/2 flex flex-col justify-center text-center lg:text-left">
            <!-- Haircuts & Combos -->
            <div class="">
              <!-- Popular Services -->
              <h2
                class="mx-auto w-2/3 lg:mx-0 lg:w-11/12 xl:w-full 2xl:w-11/12 mt-20 lg:mt-0 mb-10 text-gray-800 font-bold tracking-wider text-4xl sm:text-5xl 
                border-b-2 border-gray-900 pb-5"
                >Barber Services
              </h2>
              <h3
                class="text-gray-900 font-semibold tracking-widest text-2xl"
                >Popular Services
              </h3>
              <ul>
                <li
                  class="text-gray-900 font-medium tracking-widest lg:tracking-wider xl:tracking-widest sm:text-lg mt-2"
                  >Barber Hair Cut ( hair lining now included) - <span class="text-yellow-400 font-semibold">$25</span>
                </li>
                <li
                  class="text-gray-900 font-medium tracking-widest lg:tracking-wider xl:tracking-widest sm:text-lg"
                  >Seniors, kids, military and buzz cut w/ no line up - <span class="text-yellow-400 font-semibold">$18</span>
                </li>
              </ul>
            </div>
            <!-- Other Services -->
            <div class="">
              <h3
                class="text-gray-900 font-semibold tracking-widest text-2xl mt-5"
                >Other Services
              </h3>
              <ul>
                <li
                  class="text-gray-900 font-medium tracking-widest lg:tracking-wider xl:tracking-widest sm:text-lg mt-2"
                  >Barber Hair Cut ( hair lining now included ) - <span class="text-yellow-400 font-semibold">$25</span>
                </li>
                <li
                  class="text-gray-900 font-medium tracking-widest lg:tracking-wider xl:tracking-widest sm:text-lg"
                  >Seniors, kids, military and buzz cut w/ no line up - <span class="text-yellow-400 font-semibold">$18</span>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <!-- Services may vary per barber statement -->
        <div class="text-center px-5 pb-20">
        <h5
          class="whitespace-pre-line lg:whitespace-normal text-lg sm:text-xl text-gray-900 tracking-wider font-semibold italic"
          >At Gold Cuts, our barbers are independent 
          consultants, so prices and services may vary.
        </h5>
        </div>
      </div>
    </section>

    <!-- Time and Location -->
    <section>
      
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
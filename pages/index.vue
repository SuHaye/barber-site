<template>

  <div  id="container" class="relative h-full">
    
    <section class="section1 h-full w-full">
      <div id="home">
        <div class="hero bg-cover bg-center shadow-2xl relative">
                <!-- Background Opacity -->
                <div 
                    class="bg-black opacity-60 w-full h-full absolute"
                    >
                </div>
                <div class="text-white absolute h-full w-full">
                    <div class="flex flex-col mx-auto lg:mx-20 h-full">
                        <div class="my-auto text-center lg:text-left mx-auto lg:mx-10 xl:mx-28 2xl:mx-64">
                            <p
                                class="subtext text-2xl md:text-4xl lg:text-5xl whitespace-pre-line tracking-wide font-semibold"
                                >We got you covered.
                            </p>
                            <p
                                class="subtext text-xl md:text-2xl lg:text-3xl mb-10 font-semibold lg:tracking-wider lg:whitespace-pre-line lg:mt-5"
                                >Learn what sets us 
                                apart from average.
                            </p>
                            <div class="mt-10 subtext lg:w-max">
                                <a
                                    href="https://booksy.com/en-us/390352_gold-cuts_barber-shop_18229_chicago"
                                    class="text-2xl md:text-3xl lg:text-2xl xl:text-3xl uppercase font-semibold bg-gradient-to-l 
                                    from-gray-600 to-gray-400 px-20 py-3 lg:px-28 xl:px-24
                                    text-yellow-400 hover:underline hover:shadow-xl"
                                    >BOOK NOW
                                </a>
                            </div>
                        </div>
                    </div>
                            

                </div>
            </div>
      </div>
    </section>

    <!-- First Section/ About Company-->
    <section  class="section2 h-screen w-full">
      <div 
        id="about"
        class="lg:h-screen h-full justify-center lg:items-center flex flex-col lg:flex-row
       py-20 md:px-10 xl:px-20 2xl:px-32 bg-gradient-to-b from-gray-300 to-gray-500">
        <!-- Left Side -->
        <div class="text-center px-5 md:px-0 lg:w-2/3 xl:w-3/4">
          <h3
            class="mb-20 lg:mb-3 text-white font-bold tracking-wider text-4xl sm:text-5xl"
            >Gold Cuts Barber Shop
          </h3>
          <div class="">
            <p
              class="tracking-wide text-gray-100 mt-5 text-lg sm:text-xl md:text-2xl whitespace-pre-line"
              >Gold Cuts first opened in 2017 and has quickly 
              become well known around Chicago, Illinois. We 
              offer a classic barber shop experience, while also 
              offering you a fun and laid back atmosphere. We 
              take pride in bringing Old School and New School 
              Styles to the Golden Light! Come in and enjoy a 
              great haircut, a hot towel cleansing and come out 
              <a href="https://booksy.com/en-us/390352_gold-cuts_barber-shop_18229_chicago" class="hover:text-gray-300 italic hover:font-bold text-xl sm:text-2xl md:text-3xl">Golden Crisp</a>. We got you covered.
            </p>
            <p
              class="tracking-wide text-gray-100 mt-5 whitespace-pre-line text-lg sm:text-xl md:text-2xl"
              >We continue to stress the importance of preventing 
              the spread of infection and ask for you to follow the 
              information being circulated by healthcare officials.
            </p>
            <div class="mt-8 mt-10 lg:mb-5">
              <a
                href="https://booksy.com/en-us/390352_gold-cuts_barber-shop_18229_chicago"
                class="uppercase py-1 px-2 font-semibold tracking-wide text-white hover:text-gray-300 focus:text-yellow-500
                text-xl sm:text-2xl md:text-3xl"
                >Book An Appointment
              </a>
            </div>
          </div>
        </div>
        <!-- Right Side -->
        <div class="md:mx-auto md:w-3/4 lg:w-1/3 xl:w-7/12 xl:p-10 lg:my-auto lg:p-2 xl:p-0 lg:mr-3 xl:mr-0">
          <div class="hidden lg:flex">
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
    <section class="section3 h-full lg:h-screen w-full">
      <div
        id="barber"
        class="h-full py-20 lg:py-40 bg-fixed bg-center bg-cover bg-gradient-to-b from-gray-400 to-gray-200"
        >
        <div class="">
          <h2
            class="pt-20 p-10 text-6xl sm:text-7xl md:text-8xl font-bold uppercase text-center text-gray-300"
            >Barbers
          </h2>
        </div>

        <div class="py-10 px-5 flex flex-col lg:flex-row items-center lg:justify-center lg:flex-wrap">
          <!-- Barber 1 -->
          <div class="flex justify-center w-full md:w-6/12 lg:w-3/12 mb-10">
            <div class="items-center flex flex-col bg-gradient-to-b from-gray-400 to-gray-300 p-1 shadow-lg">
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
                <div class="my-1 py-2">
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
            <div class="items-center flex flex-col bg-gradient-to-b from-gray-400 to-gray-300 p-1 shadow-lg">
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
                <div class="my-1 py-2">
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
            <div class="items-center flex flex-col bg-gradient-to-b from-gray-400 to-gray-300 p-1 shadow-lg">
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
                <div class="my-1 py-2">
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
    <section class="section4 h-screen w-full">
      <div class="bg-gradient-to-b from-gray-500 to-gray-400 h-full">
        <div class="flex flex-col lg:flex-row justify-center h-full md:px-10 xl:px-20 2xl:px-32 pb-40 md:pb-0">
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
                class="mx-auto w-2/3 lg:mx-0 lg:w-11/12 xl:w-full 2xl:w-11/12 mt-20 lg:mt-0 mb-10 text-gray-100 font-bold tracking-wider text-4xl sm:text-5xl 
                border-b-2 border-gray-100 pb-5"
                >Barber Services
              </h2>
              <h3
                class="text-gray-100 font-semibold tracking-widest text-2xl"
                >Popular Services
              </h3>
              <ul>
                <li
                  class="text-gray-100 font-medium tracking-widest lg:tracking-wider xl:tracking-widest sm:text-lg mt-2"
                  >Barber Hair Cut ( hair lining now included) - <span class="text-yellow-400 font-semibold">$25</span>
                </li>
                <li
                  class="text-gray-100 font-medium tracking-widest lg:tracking-wider xl:tracking-widest sm:text-lg"
                  >Seniors, kids, military and buzz cut w/ no line up - <span class="text-yellow-400 font-semibold">$18</span>
                </li>
              </ul>
            </div>
            <!-- Other Services -->
            <div class="">
              <h3
                class="text-gray-100 font-semibold tracking-widest text-2xl mt-5"
                >Other Services
              </h3>
              <ul>
                <li
                  class="text-gray-100 font-medium tracking-widest lg:tracking-wider xl:tracking-widest sm:text-lg mt-2"
                  >Barber Hair Cut ( hair lining now included ) - <span class="text-yellow-400 font-semibold">$25</span>
                </li>
                <li
                  class="text-gray-100 font-medium tracking-widest lg:tracking-wider xl:tracking-widest sm:text-lg"
                  >Seniors, kids, military and buzz cut w/ no line up - <span class="text-yellow-400 font-semibold">$18</span>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Time and Location -->
    <section class="section5 h-screen w-full">
      <div 
        id="contact" 
        class="lg:items-center pb-40 md:pb-0 pt-10 h-full justify-center flex flex-col 
        lg:flex-row bg-gradient-to-b from-gray-400 to-gray-700 text-center">
        <!-- Hours -->
        <div class="lg:border-b-0 lg:border-r-2 border-b-2 border-white w-5/6 mx-auto lg:pt-28">
          <h2
            class="uppercase pb-3 font-bold tracking-wider text-4xl md:text-5xl text-white border-b-2 border-white w-3/5 md:w-1/2 mx-auto"
            >Hours
          </h2>
          <h3
            class="text-xl md:text-2xl xl:text-3xl mt-5 font-semibold tracking-widest text-white"
            >Monday-Saturday:
          </h3>
          <h4
            class="text-lg md:text-xl xl:text-2xl text-yellow-400 font-medium tracking-widest"
            >09:30am - 6:30pm
          </h4>
          <h3
            class="text-xl md:text-2xl xl:text-3xl mt-3 font-semibold tracking-widest text-white"
            >Sunday:
          </h3>
          <h4
            class="text-lg md:text-xl xl:text-2xl text-yellow-400 font-medium tracking-widest"
            >Closed
          </h4>
          <h3
            class="md:text-lg xl:text-xl mt-10 mb-20 text-yellow-400 tracking-wider font-semibold italic"
            >*Hours May Vary on Holidays*
          </h3>
        </div>
        <!-- Location -->
        <div class="mt-20 mb-20 lg:m-0 w-5/6 mx-auto">
          <h2
            class="uppercase pb-3 font-bold tracking-wider text-4xl md:text-5xl text-white border-b-2 border-white w-3/5 md:w-1/2 mx-auto"
            >Location
          </h2>
          <h3
            class="text-xl md:text-2xl xl:text-3xl mt-5 font-semibold tracking-widest text-white"
            >Address:
          </h3>
          <h4
            class="text-lg md:text-xl xl:text-2xl text-yellow-400 font-medium tracking-widest whitespace-pre-line"
            >4141 N Broadway St. 
            Chicago, IL 60613
          </h4>
          <h3
            class="text-xl md:text-2xl xl:text-3xl mt-3 font-semibold tracking-widest text-white"
            >Phone:
          </h3>
          <h4
            class="text-lg md:text-xl xl:text-2xl text-yellow-400 font-medium tracking-widest"
            >(312)-783-5812
          </h4>
        </div>

      </div>
    </section>

    
  </div>
</template>


<script>
export default {

}
</script>


<style scoped>

    #barber {
      background: url(/bricks.jpg);
      background-repeat: none;
      background-size:cover;
    }

    .hero {
        background-image: url("/slide-3.jpg");
        height: 100vh;
    }

</style>
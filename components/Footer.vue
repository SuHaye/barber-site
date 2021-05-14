    <template>
        <footer class="text-gray-600 bg-gray-700 pt-10 border-t-2 border-white">
            <div class="container mx-auto px-5 lg:pb-10">
                <!-- Flex -->
                <div class="flex flex-col lg:flex-row">
                    <!-- Left Side/Top -->
                    <div class="">
                            <div class="hidden lg:block mx-16">
                                <h2 class="text-white text-3xl font-semibold tracking-widest"
                                >Let's stay connected!
                                </h2>
                                <p class="text-yellow-400 text-xl w-4/5 mt-2 mb-5 tracking-wider font-thin"
                                >Find us on any of these platforms or feel free to
                                    <NuxtLink
                                        to="/contact"
                                        class="text-yellow-400 hover:text-gray-100"
                                        >contact
                                    </NuxtLink>
                                us.
                                </p>
                            </div>
                            <div class="justify-evenly flex text-gray-200">
                                <a 
                                    href="https://www.facebook.com/goldcutschicago"
                                    class="hover:text-yellow-400"
                                    ><fa-icon class="text-6xl lg:text-5xl xl:text-6xl" :icon="['fab','facebook']" />
                                </a>
                                <NuxtLink
                                    to="/"
                                    class="hover:text-yellow-400"
                                    >
                                    <fa-icon class="text-6xl lg:text-5xl xl:text-6xl" :icon="['fab','twitter']" />
                                </NuxtLink>
                                <a 
                                    href="https://www.instagram.com/goldcuts_chicago/"
                                    class="hover:text-yellow-400"
                                    ><fa-icon class="text-6xl lg:text-5xl xl:text-6xl" :icon="['fab','instagram']" />
                                </a>
                                
                            </div>
                    </div>
                    <!-- Right Side/Bottom -->
                    <div class="pt-10 lg:pt-0 lg:mx-auto text-xl lg:text-lg 2xl:text-xl lg:flex lg:w-1/2 lg:flex lg:justify-evenly">
                        <div class="text-center mb-10">
                            <h2
                                class="hidden lg:block text-gray-100 font-bold tracking-widest"
                                >Useful Links
                            </h2>
                            <hr class="hidden lg:block my-2">
                            <div class="text-white lg:flex-col flex justify-evenly">
                                <NuxtLink
                                    to="/"
                                    class="hover:text-yellow-400 text-gray-200"
                                    >About Us
                                </NuxtLink>
                                <span class="lg:hidden text-gray-200">|</span>
                                <NuxtLink
                                    to="/"
                                    class="hover:text-yellow-400 text-gray-200"
                                    >Barbers
                                </NuxtLink>
                                <span class="lg:hidden text-gray-200">|</span>
                                <NuxtLink
                                    to="/"
                                    class="hover:text-yellow-400 text-gray-200"
                                    >Contact
                                </NuxtLink>
                                <span class="lg:hidden text-gray-200">|</span>
                                <NuxtLink
                                    to="/"
                                    class="hidden lg:inline-block hover:text-yellow-400 text-gray-200"
                                    >Book Now
                                </NuxtLink>
                                <NuxtLink
                                    to="/"
                                    class="lg:hidden hover:text-yellow-400 text-gray-200"
                                    >Locations
                                </NuxtLink>
                            </div>
                        </div>
                        <div class="hidden lg:flex lg:flex-col text-center mt-10 lg:mt-0">
                            <h2
                            class="text-gray-100 font-bold tracking-widest"
                            >Other Resources
                            </h2>
                            <hr class="hidden lg:block my-2">
                            <NuxtLink
                                to=""
                                class="hover:text-yellow-400 text-gray-200"
                                >Our Location
                            </NuxtLink>
                            <NuxtLink
                                to="/"
                                class="hover:text-yellow-400 text-gray-200"
                                >Terms & Conditions
                            </NuxtLink>
                            <NuxtLink
                                to="/"
                                class="hover:text-yellow-400 text-gray-200"
                                >Privacy Policy
                            </NuxtLink>
                            <NuxtLink
                                to="/"
                                class="hover:text-yellow-400 text-gray-200"
                                >Licenses
                            </NuxtLink>
                        </div>
                    </div>
                <!-- Flex -->
                </div>
            </div>
            <!-- Copyright Info. -->
            <div class="items-center justify-center py-6 bg-gray-800">
                <div class="flex flex-wrap items-center justify-center mx-auto">
                    <p class="mr-5 text-sm text-center text-gray-100">© Your Company — 2021
                    </p>
                    <a
                        href="#"
                        class="justify-center mr-5 text-sm text-center text-gray-400 hover:text-yellow-400"
                        > All Rights Reserves
                    </a>
                </div>
            </div>
        </footer>
    </template>
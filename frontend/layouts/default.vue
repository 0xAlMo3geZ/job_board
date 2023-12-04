<template>
    <div>
        <nav class="p-6 flex items-center justify-between bg-cyan-800">
            <div>
                <NuxtLink to="/" class="text-white text-xl font-bold">
                    <div class="flex items-center">
                        <img src="~/assets/images/logo.svg" alt="Logo" class="h-8 w-8 mr-2">
                        Job Board
                    </div>
                </NuxtLink>
            </div>
            <div class="relative">
                <input type="search" placeholder="Search jobs"
                    class="pl-8 pr-4 py-2 border rounded-md outline-none text-gray-700">
                <svg class="absolute left-2 top-2 text-gray-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"
                    width="24" height="24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                    stroke-linejoin="round">
                    <circle cx="11" cy="11" r="8"></circle>
                    <line x1="21" y1="21" x2="16.65" y2="16.65"></line>
                </svg>
            </div>
            <div class="flex items-center space-x-4">
                <NuxtLink to="/" class="text-white hover:text-cyan-300">Home</NuxtLink>
                <NuxtLink to="/Jobs" class="text-white hover:text-cyan-300">Jobs</NuxtLink>
                <NuxtLink to="/about" class="text-white hover:text-cyan-300">About</NuxtLink>
            </div>
        </nav>

        <slot />

        <footer class="bg-gray-800">
            <!-- Flex Container -->
            <div
                class="container flex flex-col-reverse justify-between px-6 py-10 mx-auto space-y-8 md:flex-row md:space-y-0">
                <!-- Logo and social links Container  -->
                <div
                    class="flex flex-col-reverse items-center justify-between space-y-12 md:flex-col md:space-y-0 md:items-start">
                    <div>
                        <NuxtLink to="/" class="text-white text-xl font-bold">
                            <div class="flex items-center">
                                <img src="~/assets/images/logo.svg" alt="Logo" class="h-8 w-8 mr-2">
                                Job Board
                            </div>
                        </NuxtLink>
                    </div>
                    <!-- Social links Container -->
                    <div class="flex justify-center mx-auto space-x-4">
                        <a href="#">
                            <img src="~/assets/images/icon-facebook.svg" class="h-6" alt="facebook">
                        </a>
                        <a href="#">
                            <img src="~/assets/images/icon-twitter.svg" class="h-6" alt="twitter">
                        </a>
                        <a href="#">
                            <img src="~/assets/images/icon-instagram.svg" class="h-6" alt="instagram">
                        </a>
                    </div>
                </div>
                <!-- List Container -->
                <div class="flex justify-around space-x-32">
                    <div class="flex flex-col space-y-3 text-white">
                        <NuxtLink to="/" class="text-white hover:text-cyan-300">Home</NuxtLink>
                        <NuxtLink to="/Jobs" class="text-white hover:text-cyan-300">Jobs</NuxtLink>
                    </div>
                    <div class="flex flex-col space-y-3 text-white">
                        <NuxtLink to="/about" class="text-white hover:text-cyan-300">About</NuxtLink>
                    </div>
                </div>
                <!-- Input Container -->
                <div class="flex flex-col justify-between">
                    <div class="flex items-center space-x-4">
                        <NuxtLink to="/login" class="py-2 px-4 text-white bg-cyan-500 hover:bg-cyan-700 rounded-xl">Login
                        </NuxtLink>
                        <NuxtLink to="/signup" class="py-2 px-4 text-white bg-cyan-600 hover:bg-cyan-700 rounded-xl">Sign up
                        </NuxtLink>
                    </div>
                    <div class="hidden text-white text-sm mt-4 md:block">
                        Copyright &copy; 2023 - <i>@0xAlMo3geZ</i>
                    </div>
                </div>
            </div>
        </footer>
    </div>
</template>
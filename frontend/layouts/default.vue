<template>
    <div>
        <nav class="p-6 flex items-center justify-between bg-cyan-800">
            <NuxtLink to="/" class="text-white text-xl font-bold">Job Board</NuxtLink>
            <div class="flex items-center space-x-4">
                <NuxtLink to="/login" class="py-2 px-4 text-white bg-green-400 hover:bg-green-700 rounded-xl">Login
                </NuxtLink>
                <NuxtLink to="/signup" class="py-2 px-4 text-white bg-red-400 hover:bg-red-700 rounded-xl">Sign up
                </NuxtLink>
            </div>
        </nav>

        <slot />

        <footer class="p-6 flex flex-wrap items-center justify-between bg-gray-800">
            <p class="text-gray-300">Copyright &copy; 2023 - AlMo3geZ</p>

            <div class="flex items-center space-x-4">
                <NuxtLink to="/" class="text-white hover:text-cyan-300">Home</NuxtLink>
                <NuxtLink to="/jobs" class="text-white hover:text-cyan-300">Jobs</NuxtLink>
                <NuxtLink to="/about" class="text-white hover:text-cyan-300">about</NuxtLink>
            </div>
        </footer>
    </div>
</template>
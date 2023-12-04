<template>
    <div class="min-h-screen bg-gray-100">
        <div class="py-20 px-6 bg-cyan-700 text-center">
            <img src="~/assets/images/logo.svg" alt="Logo" class="h-20 w-20 mx-auto mb-6">
            <h1 class="text-5xl font-bold text-cyan-300 mb-6 animated-text">Job Board</h1>
            <NuxtLink to="/jobs" class="py-2 px-4 text-white bg-cyan-500 hover:bg-cyan-900 rounded-xl inline-block">Browse
                jobs
            </NuxtLink>
        </div>
        <div class="py-10 px-6">
            <h2 class="text-center text-2xl font-semibold text-gray-800">Newest Jobs</h2>
            <div class="container grid grid-cols-3 gap-6 mx-auto p-8">
                <!-- Job Card -->
                <div class="max-w-md mx-auto bg-white rounded-md overflow-hidden shadow-md">
                    <div class="p-4">
                        <!-- Job Title -->
                        <h2 class="text-xl font-semibold text-gray-800">Software Engineer</h2>
                        <!-- Company Name -->
                        <p class="text-gray-600 mt-2">Acme Corporation</p>
                        <!-- Job Location -->
                        <p class="text-gray-600 mt-2">San Francisco, CA</p>
                        <!-- Job Description -->
                        <p class="text-gray-700 mt-4">We are looking for a skilled software engineer...</p>
                        <!-- Apply Button -->
                        <a href="#" class="mt-4 block bg-green-500 text-white px-4 py-2 rounded-md text-center">Apply
                            Now</a>
                    </div>
                </div>
                <div class="max-w-md mx-auto bg-white rounded-md overflow-hidden shadow-md">
                    <div class="p-4">
                        <!-- Job Title -->
                        <h2 class="text-xl font-semibold text-gray-800">Software Engineer</h2>
                        <!-- Company Name -->
                        <p class="text-gray-600 mt-2">Acme Corporation</p>
                        <!-- Job Location -->
                        <p class="text-gray-600 mt-2">San Francisco, CA</p>
                        <!-- Job Description -->
                        <p class="text-gray-700 mt-4">We are looking for a skilled software engineer...</p>
                        <!-- Apply Button -->
                        <a href="#" class="mt-4 block bg-green-500 text-white px-4 py-2 rounded-md text-center">Apply
                            Now</a>
                    </div>
                </div>
                <div class="max-w-md mx-auto bg-white rounded-md overflow-hidden shadow-md">
                    <div class="p-4">
                        <!-- Job Title -->
                        <h2 class="text-xl font-semibold text-gray-800">Software Engineer</h2>
                        <!-- Company Name -->
                        <p class="text-gray-600 mt-2">Acme Corporation</p>
                        <!-- Job Location -->
                        <p class="text-gray-600 mt-2">San Francisco, CA</p>
                        <!-- Job Description -->
                        <p class="text-gray-700 mt-4">We are looking for a skilled software engineer...</p>
                        <!-- Apply Button -->
                        <a href="#" class="mt-4 block bg-green-500 text-white px-4 py-2 rounded-md text-center">Apply
                            Now</a>
                    </div>
                </div>
                <div class="max-w-md mx-auto bg-white rounded-md overflow-hidden shadow-md">
                    <div class="p-4">
                        <!-- Job Title -->
                        <h2 class="text-xl font-semibold text-gray-800">Software Engineer</h2>
                        <!-- Company Name -->
                        <p class="text-gray-600 mt-2">Acme Corporation</p>
                        <!-- Job Location -->
                        <p class="text-gray-600 mt-2">San Francisco, CA</p>
                        <!-- Job Description -->
                        <p class="text-gray-700 mt-4">We are looking for a skilled software engineer...</p>
                        <!-- Apply Button -->
                        <a href="#" class="mt-4 block bg-green-500 text-white px-4 py-2 rounded-md text-center">Apply
                            Now</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style scoped>
@keyframes bounce {

    0%,
    20%,
    50%,
    80%,
    100% {
        transform: translateY(0);
    }

    40% {
        transform: translateY(-20px);
    }

    60% {
        transform: translateY(-10px);
    }
}

.animated-text {
    animation: bounce 2s infinite;
}</style>
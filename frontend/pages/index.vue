<script setup>
const { data: jobs } = await useFetch('http://127.0.0.1:8000/api/v1/jobs/newest/')
</script>

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

            <div class="space-y-4">
                <Job v-for="job in jobs" v-bind:key="job.id" v-bind:job="job" />
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
}
</style>
<template>
    <div class="min-h-screen bg-gray-100">
        <div class="py-20 px-6 bg-cyan-700 text-center">
            <h1 class="text-5xl font-bold text-cyan-300 mb-6 animated-text">About Us</h1>
            <p class="text-md text-white">Some text about who we are and what we do.</p>
        </div>

        <div class="py-10 px-6">
            <h2 class="text-center text-2xl font-semibold text-gray-800">Our Team</h2>
            <div class="container grid grid-cols-3 gap-6 mx-auto p-8">
                <div class="max-w-md mx-auto bg-white rounded-md overflow-hidden shadow-md">
                    <div class="p-4">
                        <img src="https://www.w3schools.com/w3images/team1.jpg" alt="Jane" style="width:100%">
                        <h2>Jane Doe</h2>
                        <p class="title">CEO & Founder</p>
                        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
                        <p>jane@example.com</p>
                        <a href="#" class="mt-4 block bg-blue-500 text-white px-4 py-2 rounded-md text-center">Contact</a>
                    </div>
                </div>

                <div class="max-w-md mx-auto bg-white rounded-md overflow-hidden shadow-md">
                    <div class="p-4">
                        <img src="https://www.w3schools.com/w3images/team2.jpg" alt="Mike" style="width:100%">
                        <h2>Mike Ross</h2>
                        <p class="title">Talent Director</p>
                        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
                        <p>mike@example.com</p>
                        <a href="#" class="mt-4 block bg-blue-500 text-white px-4 py-2 rounded-md text-center">Contact</a>
                    </div>
                </div>

                <div class="max-w-md mx-auto bg-white rounded-md overflow-hidden shadow-md">
                    <div class="p-4">
                        <img src="https://www.w3schools.com/w3images/team3.jpg" alt="John" style="width:100%">
                        <h2>John Doe</h2>
                        <p class="title">Talent Director</p>
                        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
                        <p>john@example.com</p>
                        <a href="#" class="mt-4 block bg-blue-500 text-white px-4 py-2 rounded-md text-center">Contact</a>
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
}
</style>
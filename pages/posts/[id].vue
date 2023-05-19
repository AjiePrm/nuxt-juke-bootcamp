<template>
    <div>
        <div>
                <main class="h-screen w-full flex flex-col justify-center items-center bg-[rgb(26,34,56)]">
            <h1 class="lg:text-9xl font-extrabold text-white tracking-widest sm:text-8xl ">Poduct {{ id }}</h1>
            <div class="bg-[#FF6A3D] px-2 text-sm rounded rotate-12 absolute">
                Page Not Found
            </div>
            <div class="bg-[#FF6A3D] px-2 text-sm rounded rotate-12 absolute">
                This page is under develope, please come back latter !
            </div>
            <NuxtLink to="/app">
            <button class="mt-5">
                <a
                    class="relative inline-block text-sm font-medium text-[#FF6A3D] group active:text-orange-500 focus:outline-none focus:ring"
                >
                    <span
                    class="absolute inset-0 transition-transform translate-x-0.5 translate-y-0.5 bg-[#FF6A3D] group-hover:translate-y-0 group-hover:translate-x-0"
                    ></span>


                        <span class="relative block px-8 py-3 bg-[#1A2238] border border-current">
                        Go Home
                        </span>
                    
                </a>
                </button>
            </NuxtLink>
        </main>
        </div>
    </div>
</template>

<script setup>
     const {id} = useRoute().params
</script>
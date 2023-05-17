<template>
            <div class="lg:w-1/3 my-4 md:my-6">
                <div class="border-t-4 border-solid border-white bg-white text-center max-w-sm mx-auto hover:border-red-400 transition-colors duration-300">
                <div class="p-6 md:py-8">
                    <h4 class="font-medium leading-tight text-2xl mb-2">{{ ingri }}</h4>
                </div>
                <div class="bg-indigo-100 p-6 transition-colors duration-300">
                    <div class=""><span class="text-4xl font-semibold">{{ gram }}</span> {{ takar }}</div>
                </div>
                <div class="p-6">
                    <div class="mt-6 py-4">
                        <NuxtLink to="/shop">
                            <button class="bg-red-400 text-xl text-white py-2 px-6 rounded hover:bg-red-700 transition-colors duration-300">
                            Shop recipe
                            </button>
                        </NuxtLink>
                    </div>
                </div>
                </div>
            </div>                    
</template>

<script setup>
const props = defineProps({
    gram : String,
    ingri : String,
    takar : String
})
</script>
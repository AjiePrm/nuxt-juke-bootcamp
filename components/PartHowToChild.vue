<template>
    <div class="px-4">
        <div class="max-w-lg rounded overflow-hidden shadow-lg mx-auto my-8">
           <slot/>
            <div class="px-6 py-4">
                <div class="font-bold text-xl text-gray-100 mb-2">Step {{ step }}</div>
                <div class="font-bold text-xl text-gray-100 mb-2">{{ part }}</div>
                <p class="text-gray-200 text-base">
                    {{ desc }}
                </p>
            </div>
        </div>
    </div>
</template>

<script setup>
const props = defineProps({
    step: Number,
    part: String,
    desc: String
})
</script>
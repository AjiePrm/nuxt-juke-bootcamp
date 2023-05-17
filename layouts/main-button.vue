<template>
    <NuxtLink to="/HowTo">
        <button onclick={goto()} class=" fancy-btn inline-flex text-white border-0 py-2 px-6 focus:outline-none bg-red-400 hover:bg-red-600 rounded text-lg">
            Learn more
            <slot/>
        </button>
    </NuxtLink>
     <!-- required here only -->
</template>

<script setup>
    definePageMeta({
        layout: "main-button"
    })
    methods: {
    function goto() {
      this.$router.replace({ name: this.$route.name, hash: '#example' }); 
    }
}
</script>

<style >

</style>
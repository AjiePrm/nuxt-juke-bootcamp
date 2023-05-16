<template>
    <div class="container mx-auto px-8 shadow-lg border my-5">
                    <div class="pricing-plans lg:flex lg:-mx-6 lg:px-3 mt-6 md:mt-12">
                        <div class="lg:w-5/12 px-4 py-12 object-center m-auto sm:w-11/12">
                            <slot/>
                        </div>
                      <div class="lg:w-11/12 my-4 md:my-6 sm:w-11/12">
                        <div class="border-t-4 border-solid border-white bg-white max-w-sm mx-auto hover:border-red-400 transition-colors duration-300">
                          <div class=" md:py-8">
                            <h4 class="font-medium leading-tight text-2xl mb-2">{{ title }}</h4>
                          </div> 
                          <div class="">
                            <h6 class="leading-tight text-xl py-1">{{ description }}</h6>
                          </div>                               
                          <div class="pricing-amount bg-indigo-100 p-6 transition-colors duration-300">
                            <div class="text-4xl font-semibold"><span class="text-4xl font-semibold">$</span> {{ price }}</div>
                          </div>
                          <div class="p-6 flex flex-row space-x-5">
                            <div class="mt-6 py-4">
                              <button class="bg-red-400 text-xl text-white py-2 px-6 rounded hover:bg-red-700 transition-colors duration-300">Buy</button>
                            </div>
                            <div class="mt-6 py-4">
                              <button class="border shadow-lg text-xl text-black py-2 px-6 rounded hover:bg-red-700 transition-colors duration-300">Add to chart</button>
                            </div>
                          </div>
                        </div>
             </div>               
        </div>
    </div>
</template>

<script setup>
const props = defineProps({
  title: String,
  description : String,
  price : Number,
  image: String,
})


</script>
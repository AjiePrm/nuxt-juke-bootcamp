<template>
    <div class="pricing-table-2 bg-gray-800 py-6 md:py-12">
                      <div class="container mx-auto px-4">

                        <div class="max-w-3xl mx-auto text-center">
                          <h1 class="text-3xl md:text-4xl font-medium text-white mb-4 md:mb-6">Ingredients</h1>
                          <p class="text-gray-500 xl:mx-12">We can help you prepare !</p>
                        </div>

                        <div class="pricing-plans lg:flex lg:-mx-4 mt-6 md:mt-12">
                          <Two :gram="'1/2'" :ingri="'ground beef'" :takar="'pound'"></Two> 
                          <Two :gram="'1 to 2'" :ingri="'tomato'" :takar="'sliced'"></Two> 
                          <Two :gram="'1 to 3'" :ingri="'salt and pepper'" :takar="'pinch'"></Two> 
                        </div>

                        <div class="pricing-plans lg:flex lg:-mx-4 mt-6 md:mt-12">
                          <Two :gram="'1/2'" :ingri="'ground beef'" :takar="'pound'"></Two> 
                          <Two :gram="'1 to 2'" :ingri="'tomato'" :takar="'sliced'"></Two> 
                          <Two :gram="'1 to 3'" :ingri="'salt and pepper'" :takar="'pinch'"></Two> 
                        </div>
                        
                        <div class="pricing-plans lg:flex lg:-mx-4 mt-6 md:mt-12">
                          <Two :gram="'1/2'" :ingri="'ground beef'" :takar="'pound'"></Two> 
                          <Two :gram="'1 to 2'" :ingri="'tomato'" :takar="'sliced'"></Two> 
                          <Two :gram="'1 to 3'" :ingri="'salt and pepper'" :takar="'pinch'"></Two> 
                        </div>

            </div>
          </div>
</template>

<script setup>

</script>
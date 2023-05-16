
<template>
   <!-- header part -->
   <div class="content">
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
    <CardProduct :title = "'Fancy Sweater'" :description = "'This in a cute thing right ?'" :price="10" >
      <img class="object-cover object-center rounded md:place-content-center" alt="image" src="~/assets/baju.webp" />
    </CardProduct>
    <CardProduct :title = "'Gray women blouse top'" :description = "'Mostcrepe ingredients LD 100 Length 68/70 The material is not hot and falls (polyester)'" :price="7" >
      <img class="object-cover object-center rounded md:place-content-center" alt="image" src="~/assets/atasas.webp" />
    </CardProduct>
    <CardProduct :title = "'Women blouse tops'" :description = "'Moscrepa material LD 100 Length 68/70 The material is not hot and falls (polyester)'" :price="8" :image="'baju.webp'">
      <img class="object-cover object-center rounded md:place-content-center" alt="image" src="~/assets/atasan.webp" />
    </CardProduct>
    <Footer></Footer>   
   </div>
</template>

<script setup>

</script>

<style>
.content{
  overflow-x: hidden;
}

.body{
  font-family: 'Roboto';
}

</style>
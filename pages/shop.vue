
<template>
    <div>
        <Header></Header> 

       
            <CardProduct :title = "'ground beef'" :description = "'right here you can get best meat'" :price="10" >
            <NuxtLink to="/posts/1">
                <img class="cursor-pointer object-cover object-center rounded md:object-center" alt="image" src="~/assets/meat.webp" style="aspect-ratio: 4/4;" />
            </NuxtLink>
            </CardProduct>
            <CardProduct :title = "'tomato'" :description = "'a fresh tomate'" :price="7" >
                <NuxtLink to="/posts/2">
                    <img class="cursor-pointer object-cover object-center rounded md:place-content-center " alt="image" src="~/assets/tomtow.webp " style="aspect-ratio: 4/4; width: 400px;"/>
                </NuxtLink>
            </CardProduct>

            <CardProduct :title = "'onion'" :description = "'fresh onion fell free to ask'" :price="8">
                <NuxtLink to="/posts/3">
                    <img class="cursor-pointer object-cover object-center rounded md:place-content-center" alt="image" src="~/assets/onion.jpg" style="aspect-ratio: 4/4; width: 400px;"/>
                </NuxtLink>
            </CardProduct>
        

        <Footer></Footer>
    </div>
</template>

<script setup>
   
</script>
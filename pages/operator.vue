<template>
    <div class="text-center">
      <h1>Masukan total belanjaan anda untuk melihat diskon</h1>
      <input v-model="itemPrice" type="number" placeholder="type here ..." />
      <button @click="applyDiscount" class="bg-green-300 rounded-md px-6 py-1 hover:bg-green-400">submit</button>
  
      <div v-if="discountedPrice !== null">
        <h2>Harga diskon: Rp. {{ discountedPrice }}</h2>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        itemPrice: null,
        discountedPrice: null
      };
    },
    methods: {
      applyDiscount() {
        let discountPercentage = 0;
  
        if (this.itemPrice >= 100000) {
          discountPercentage = 0.1; 

        } else if (this.itemPrice >= 50000) {
          discountPercentage = 0.05
        }
  
        if (discountPercentage > 0) {
          const discountedPrice = this.itemPrice * (1 - discountPercentage);
          this.discountedPrice = discountedPrice.toFixed(2);
        } else {
          this.discountedPrice = "tidak ada diskon";
        }
      }
    }
  };
  </script>
  
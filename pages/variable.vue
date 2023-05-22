<template>
  <div class="xl:w-6/12 m-auto lg:w-9/12">
    <div class="container mx-auto my-9 rounded-lg shadow-md">
      <div class="flex">
        <div class="w-2/5">
          <img
            src="http://bit.ly/2tMBBTd"
            class="h-420 w-327 rounded-l-lg"
            alt="Harvest Vase"
          />
        </div>

        <div class="w-3/5 bg-white rounded-r-lg">
          <div class="p-8">
            <h1 class="text-4xl font-serif"></h1>
            <h2
              class="mt-4 text-xs font-semibold uppercase text-gray-600 tracking-wider"
            >
              by studio and friends
            </h2>
            <p class="mt-6 text-base font-serif text-gray-700 leading-relaxed">
              Harvest Vases are a reinterpretation<br />
              of peeled fruits and vegetables as<br />
              functional objects. The surfaces<br />
              appear to be sliced and pulled aside,<br />
              allowing room for growth.
            </p>
          </div>

          <div class="flex items-center justify-between px-5 py-4 mt-4">
            <p class="inline-block font-serif text-xl font-light text-gray-700">
              <span class="font-serif text-2xl">$78</span>
            </p>

            <div class="container m-0 flex justify-center px-5">
              <button
                @click="count--"
                type="submit"
                class="btn btn-default inline-block bg-slate-500 hover:bg-slate-600 text-white py-1 rounded-full px-6"
              >
                -
              </button>
              <span>
                <h1 class="bg-gray-200 px-3 py-1 rounded-sm shadow-lg">
                  {{ count }}
                </h1>
              </span>
              <button
                @click="count++"
                type="submit"
                class="btn btn-default inline-block bg-gray-500 hover:bg-gray-600 text-white py-1 rounded-full px-6"
              >
                +
              </button>
            </div>

            <button
              class="inline-block px-10 py-2 font-semibold text-xs uppercase tracking-tight text-white bg-red-400 rounded-full hover:bg-red-500"
            >
              Buy Now
            </button>
          </div>
        </div>
      </div>
    </div>

    <div class="container mx-auto flex space-x-2 px-5">
      <h1></h1>
    </div>
  </div>
</template>

<script>
import dataProduct from "~/json/dataCard.json";

export default {
  data() {
    return {
      count: 0,
    };
  },
};
 
let angka = 0;
console.log(`angka: ${angka} `)
let kalimat ="kasur"
console.log(`kalimat: ${kalimat} `)

angka += 2;
console.log("dynamic variable angka + 2")
console.log(angka)

console.log(kalimat.split(""))

kalimat = "kalimat baru"

console.log(kalimat)

console.log("static variable")

console.log()
console.log()
const array = [1, 2, 3, 4, 5];

const reversedArray = array.reverse();
console.log("reverse");
console.log(reversedArray);

const joinedArray = array.join("->");
console.log("join");
console.log(joinedArray);

const splicedArray = array.splice(0, 3);
console.log("splice");
console.log(splicedArray);


const item = dataProduct.products

console.log(dataProduct.products);

//unsolve
console.log(dataProduct.products[0].title);
</script>

<template>
    <div>
        
 
    </div>
</template>

<script>
//case 1

const symbolString = (string) => string.split('').join('@');
let inputString = symbolString("Hello World");
console.log('%c case 1 ', 'background: #222; color: #bada55')
console.log(inputString);

//case 2

const sortHandler = (objects) => {
  let nameList = [...new Set(objects.map(obj => obj.name))];  
  let sorting = nameList.sort();
  return sorting.map(name => objects.find(obj => obj.name === name));
}

let inputArray = [
  { name: "John", age: 25 },
  { name: "Jane", age: 30 },
  { name: "John", age: 35 },
  { name: "Alice", age: 28 },
  { name: "Ajie", age: 22},  
];

let outputArray = sortHandler(inputArray);
console.log('%c case 2 ', 'background: #222; color: #bada55')
console.log(outputArray);

//case 3

const sumArray = (number) => {
  let sum = 0;
  return number.map(num => {
    sum += num;
    return sum;
  });
}

let output = sumArray([1, 2, 3, 4, 5]);
console.log('%c case 3 ', 'background: #222; color: #bada55')
console.log(output); 

</script>
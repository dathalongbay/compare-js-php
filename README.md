# compare-js-php
```
# thêm phần tử vào mảng
const fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.push("Kiwi");

# in_array php
const fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.includes("Mango");

const fruits = ["Banana", "Orange", "Apple", "Mango"];
let result = Array.isArray(fruits);

# convert mảng thành chuỗi
const fruits = ["Banana", "Orange", "Apple", "Mango"];
let text = fruits.join();

# chuyển chuỗi thành mảng
var string = "0,1";
var array = string.split(",");
alert(array[0]);

# gộp 2 mảng
const arr1 = ["Cecilie", "Lone"];
const arr2 = ["Emil", "Tobias", "Linus"];

const children = arr1.concat(arr2); 

# lọc các phần tử trong mảng thỏa mãn điều kiện nào đó
const ages = [32, 33, 16, 40];
document.getElementById("demo").innerHTML = ages.filter(function checkAdult(age) {
  return age >= 18;
});

# tìm 1 phần tử đầu tiên thỏa mãn điều kiện cho trước
const ages = [3, 10, 30, 18, 20];

document.getElementById("demo").innerHTML = ages.find(function(age) {
  return age > 18;
});

# forEach
let text = "";
const fruits = ["apple", "orange", "cherry"];
fruits.forEach(function(item, index) {
  text += index + ": " + item + "<br>"; 
});

document.getElementById("demo").innerHTML = text;
# Map => Tạo ra 1 mảng mới từ 1 mảng cho trước theo 1 quy tắc trong function callback
const numbers = [65, 44, 12, 4];
const newArr = numbers.map(function(num) {
  return num * 10;
});

document.getElementById("demo").innerHTML = newArr;

# thêm phần từ vào mảng như php
const numbers = [45, 4, 9, 16, 25];

numbers[7] = 100;
numbers[10] = 100;
console.log(numbers);
# mảng đa chiều trong js
let activities = [
    ['Work', 9],
    ['Eat', 1],
    ['Commute', 2],
    ['Play Game', 1],
    ['Sleep', 7]
];
```

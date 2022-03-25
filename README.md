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
```

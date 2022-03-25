### Example solutions for nextLevel exercises

**Exercise 1**  
```js
var today = new Date();
var dd = today.getDate();

// The getMonth() method returns the month (from 0 to 11) of a date, according to local time.
// Remember!! This means that January is 0, February is 1, and so on.

var mm = today.getMonth()+1; 
var yyyy = today.getFullYear();
if(dd<10) 
{
    dd='0'+dd;
} 

if(mm<10) 
{
    mm='0'+mm;
} 
today = mm+'-'+dd+'-'+yyyy;
console.log(today);
today = mm+'/'+dd+'/'+yyyy;
console.log(today);
today = dd+'-'+mm+'-'+yyyy;
console.log(today);
today = dd+'/'+mm+'/'+yyyy;
console.log(today);
```
---

**Exercise 2**  
```javascript
const side1 = 5; 
const side2 = 6; 
const side3 = 7; 
const perimeter = (side1 + side2 + side3)/2;
const area =  Math.sqrt(perimeter*((perimeter-side1)*(perimeter-side2)*(perimeter-side3)));
console.log("This is the total triangle area:", area);
```
---

**Exercise 3**  
```javascript
// steps one by one
const string = "We are CodeWomen"
const stringSplit = string.split("")
const reversedString = stringSplit.reverse()
const joinedString = reversedString.join("")
console.log(joinedString);

// concatenating methods in one go
const secondString = "We are CodeWomen"
const secondReversedString = string.split("").reverse().join("")
console.log(secondReversedString);
```
---

**Exercise 4**  
```javascript
let arrOne = [2, 5, 7, 34, 52, 457, 8, 35];
let arrTwo = [5, 21, 43, 8, 52];

function getFirstOnes(arr1, arr2) {
  arr1.forEach((number) => {
    if (!arr2.includes(number)) {
      console.log(number);
    }
  });
}

getFirstOnes(arrOne, arrTwo);
}
```
---

**Exercise 5**  
```javascript
let sentence =
  "Now I am sitting here waiting for my coffee and cake but the cafe is a bit slow executing my order.";

function findLongestWord(myStr) {
  var strSplit = myStr.split(" ");  
  var mostChars = 0;
  var arrLongest = []
  for (var i = 0; i < strSplit.length; i++) {
    if (strSplit[i].length > mostChars) {
      mostChars = strSplit[i].length;
      arrLongest.push(strSplit[i])
    }    
  }
  let longestWord = arrLongest[arrLongest.length - 1];
  return longestWord;
}

console.log(findLongestWord(sentence));

```
---

**Exercise 6**  
```javascript
for (var i = 0; i <= 10; i++) {
  console.log("7 x " + i + " = " + (7 * i));
}
```
---

**Exercise 7**  
```javascript

function celsiusToFahrenheit(num) {
  return num * 1.8 + 32
}

console.log(celsiusToFahrenheit(20));

```
---

**Exercise 8**  
```javascript
let drinks = [
  { name: "lemonade", price: 50 },
  { name: "lime", price: 10 },
  { name: "coffee", price: 1.75 },
  { name: "beer", price: 2.0 },
  { name: "water", price: 1.0 },
];

function sortByPrice(arr) {
  arr.sort((a, b) => {
    return a.price - b.price;
  });

  arr.forEach((drink) => {
    console.log(`${drink.name}, price is ${drink.price}`);
  });
}

sortByPrice(drinks)

```
---

**Exercise 1:**  
``` js
if (a.length > b.length) {
  console.log(a);
} else {
console.log(b);
}

// OR with ternary operator:
(a.length > b.length) ? console.log(a) : console.log(b);
```
---

**Exercise 2:**  
``` js
if (sentence.includes(word)) {
  console.log(word);
}

// OR with ternary operator:
sentence.includes(word) ? console.log(word) : console.log("Not found");
```
---

**Exercise 3:** 
 ```js
 for (let i = 0; i < years.length; i++) {
  if (i % 4 === 0) {
    console.log(years[i]);
  } else {
    console.log("Not a leap year");
  }
}
```
OR
```js
years.map(year => year % 4 === 0 ? console.log(year) : console.log("Not a leap year"))
```
---

**Exercise 4:**  
```js
for (let i = 0; i <= 50; i++) {  
  if (i % 10 === 0 || i % 15 === 0) {
    console.log("Hello");
  } else if (i % 5 === 0) {
    console.log("");
  } else if (i % 2 !== 0 && (i - 1) % 10 === 0) {
    console.log("World!");
  }
}
```
---

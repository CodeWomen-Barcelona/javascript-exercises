### Example solutions for arrays exercises

**Exercise 1**  
```js
const animalArray = ["dog", "cat", "fish"]
animalArray.push("horse", "goat")
console.log("add", animalArray);
animalArray.splice(0, 2)
console.log("remove", animalArray);
animalArray.splice(-1, 1, "last")
console.log("replace", animalArray);

```

**Exercise 2**  
```js
const foods = ['chocolate', 'peanuts', 'bread', 'eggs', 'juice', 'wine']
foods.forEach((item) => {
  if (foods.indexOf(item) % 2 === 0) {
    console.log(item);
  }
})
```

**Exercise 3**  
```js
let word = "bear";
let arr = ["bcn", "mia", "sao", "mex", "par", "mini", "ams", "bear", "paris", "lis", "mad"];
if (arr.includes("bear")) {
  console.log("bear is included");
}
```

**Exercise 4**  
```js
const prices = [10.99, 44.56, 112.79, 3, 5];

function addPrice() {
  let sum = 0;
  for (let i = 0; i < prices.length; i++) {
    sum = sum + prices[i]
  }
  return sum.toFixed(1)
}
console.log(addPrice(prices));

// OR
let addPrice = (item) => {
  let sum = 0;
  item.forEach((price) => {
    sum = sum + price
  })
  return sum.toFixed(1)
}
console.log(addPrice(prices));
```


**Exercise 5**  
```js
let products = [
  {
      name: "iPhone",
      price: 799.99
  },
  {
      name: "Samsung Galaxy S10",
      price: 900.00
  }
];

console.log(products[0].price);
console.log(products[1].name);

products.unshift({name: "whatPhone", price: 650.20})
console.log(products);

products.pop()
console.log(products);

```
---

**Exercise 6**  
```js
const someArr = ["max", 34, true, {name: "sandra", student: true}, ["javascript", "mongodb", "react"]];

someArr.forEach((item) => {
  console.log(typeof item);
})

```
---

**Exercise 7:**  
 
---

**Exercise 9:**  
 
---

**Exercise 10:**  


---
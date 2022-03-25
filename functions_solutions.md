**Exercise 1:**  
```js
function welcome(name) {
  console.log("Hello", name);
}

welcome("Add your name here!")
```

---
**Exercise 2:**
```js
function printToTwenty() {
  for (let i = 0; i <= 20; i++)
  console.log(i);
}

printToTwenty()
``` 
---
**Exercise 3:**  
```js
function printNumbers(number) {
  for (let i = 0; i <= number; i++)
  console.log(i);
}

printNumbers(22)
```
---
**Exercise 4:**   
```js
function printArrElements(myArr) {
  for (let i = 0; i < myArr.length; i++) {
    console.log(myArr[i]);
  }
}

printArrElements(countries)
```
OR 
```js
function printArrElements(myArr) {
  myArr.forEach(item => console.log(item))
}

printArrElements(countries)
```
---
**Exercise 5:**  
```js
function printSecondElements(myArr){
  for (let i = 0; i < myArr.length; i++) {
    if (i % 2 === 0)
    console.log(myArr[i]);
  }
}

printSecondElements(countries)
```
---
**Exercise 6:**  
```js
function changeToLetters(myStr) {
  console.log(myStr.split(''));
}

changeToLetters("what")
```
---

**Exercise 7:**  
```js
function fizzBuzz() {
  for (let i = 0; i <= 100; i++) {
    if (i % 9 === 0) {
      console.log("");
    } else if (i % 3 === 0 && i % 5 === 0) {
      console.log("FizzBuzz",;
    } else if (i % 3 === 0) {
      console.log("Fizz");
    } else if (i % 5 === 0) {
      console.log("Buzz");
    }
  }
}

fizzBuzz();
```
---
**Exercise  8:**  
```javascript
function getCredentials() {
  console.log("Username is: " + user.username + ", and the password is: " + user.password);
}

getCredentials(user)
```
OR with template literal:

```js
function getCredentials() {
  console.log(`Username is: ${user.username}, and the password is: ${user.password}`);
}

getCredentials(user)
```
---


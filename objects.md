## Objects

**Exercise 1**  
Iterate over this object and log all the properties in the console:
```javascript
const items = {
  'first': new Date(),
  'second': 2,
  'third': 'test',
  'fourth': 78.90,
  'fifth': null
}
```
---

**Exercise 2**  
Define a function checkProperty() that will use the following object passed as an argument. The function is expected to print as output in the console the object and its properties if the house is for sale. If not, a message must be printed telling the user that the property with this address is not for sale. You can make up the text to be printed yourself, but you need to use all the values in the property object.

```javascript
let property = {
  owner: {
    firstName: "John",
    lastName: "Doe",
    age: 44,
  },
  isForSale: true,
  sqrm: 120,
  address: {
    street: "Happy St",
    number: 123,
    city: "Miami",
    state: "FL",
    country: "US",
  },
  amenities: ["pool", "tennis court", "private parking", "yard"],
};
```
---

**Exercise 3**  
Given the object with nested objects in it, print:
1. name of the course
1. street
1. city
1. the student's name

```javascript
let student = {
  firstName: "Ana",
  lastName: "Blair",
  course: {
    name: "Web Development",
    type: "part-time"
  },
  attendedIn: "Madrid",
  address: {
    street: "Happy Street",
    number: 123,
    city: "Barcelona",
    zip: 08015,
    country: "Spain"
  }
};
```
---
**Exercise 4:**  
Retrieve elements from the following object to use as variables, so that you can print a sentence in the console, using these words with the variables: 
"At MigraCode, I learn *variable* and my favourite frameworks are *variable* and *variable*".

```javascript
let skill = {
  language: "JavaScript",
  frameworks: [
    {
      end: "back",
      list: [
        {
          name: "ExpressJS",
          released: 2010
        },
        {
          name: "MeteorJS",
          released: 2012
        }
      ]
    },
    {
      end: "front",
      list: [
        {
          name: "ReactJS",
          released: 2013
        },
        {
          name: "VueJS",
          released: 2014
        }
      ]
    }
  ]
};
``` 
---
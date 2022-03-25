### Example solutions for objects exercises


**Exercise 1**  
```javascript
const items = {
  'first': new Date(),
  'second': 2,
  'third': 'test',
  'fourth': 78.90,
  'fifth': null
}

for (item in items) {
  console.log(item);
}
```
---

**Exercise 2**  
```javascript
function checkProperty() {
  if (property.isForSale === true) {
    console.log(
      `The owner, ${property.owner.firstName} ${property.owner.lastName} put the home for sale! The property has ${property.amenities.length} amenities: `
    );
    for (let i = 0; i < property.amenities.length; i++) {
      console.log(`${i + 1} - ${property.amenities[i]}`);
    }
  } else {
    console.log(
      `The home in ${property.address.street} ${property.address.number} is not for sale.`
    );
  }
}
// run code:
checkProperty()
```
---

**Exercise 3**  
```js
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

console.log(student.course.name);
console.log(student.address.street);
console.log(student.address.city);
console.log(student.firstName + " " + student.lastName);
```
---

**Exercise 4**  
```js
let sentence = `At MigraCode, I learn ${skill.language} and my favourite frameworks are ${skill.frameworks[0].list[0].name} and ${skill.frameworks[1].list[0].name}.`
console.log(sentence);
```
---



## Objects

Define a function `getCredentials()` that will receive the following object as argument and print the following result:

```javascript
let user = {
  username: "codingNewbie",
  password: "learning2021",
};
```

=> expected output in the console: _Username is: codingNewbie and the password is: learning2021._
---

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
```
---


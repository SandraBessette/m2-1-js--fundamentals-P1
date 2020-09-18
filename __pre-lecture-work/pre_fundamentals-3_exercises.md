# Fundamentals: Exercises

_We will correct these exercises in class._

## Exercise 1

```js
// Look at these expressions below and determine whether they evaluate to true or false

1. true || false = true
2. false && false = false
3. 1 < 2 && 2 > 1 = true
4. 31 < 13 || 1 < 2 && 3 > 1 = true
5. 400 <= 400 && 399 < 400 && (30 > 31 || 400 > 31) = true
6. true && false && false || false && true = false
7. true && false || true || false = true
8. true && false && false || false && true ? true && false && false || false && true : 1 < 2 && 2 > 1 = true
```

---

## Exercise 2

Given this data structure:

```js
let data = [0, [], [], [1, 2, 3, [4]]];
```

1. How would you access the value `0`? data[0];
2. How would you access the value `3`? data[3][2];
3. How would you access the value `4`? data[3][3][0];

---

## Exercise 3

- List the number of properties for each object.
- For each property, indicate its key and its value.
- For each property value, indicate its type.

```js
{ label: 'corn', price: 5.3 + '$' };
{ ISBN: 53532, isAvailable: true, author: 'Nakamoto' };
```
1) a) has 2 properties
b) label property: label is the key and "corn" the value. price property: price is the key and '5.3$' the value.
c) 'corn' is a string and '5.3$' is a string

2) a) has 3 properties
b) ISBN property: ISBN is the key and 53532 is the value. isAvailable property: isAvailable is the key and true the value. author property: author is the key and 'Nakamoto' the value
c)  53532 is an integer , true is a Boolean and 'Nakamoto' is a string
---

## Exercise 4

```js
// Given
let person = { name: 'Bob', age: 23 };
let name = 'John';
```

What is the value of the following expressions?

1. person.name = "Bob"
2. person['name'] = "Bob"
3. person[name] = create an error...

---

## Exercise 5

```js
// Given
let person = { name: 'Bob', age: 23 };
let key = 'name';
```

What is the value of the following expressions:

1. person.key = undefined
2. person['key'] = undefined
3. person[key] = create an error

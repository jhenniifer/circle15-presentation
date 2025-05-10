---
theme: default
class: text-center
title: Circle 15 JavaScript Journey
date: 2025-05-07
---

# 🎉 Welcome to Circle 15's Recap  
### A Journey Through JavaScript  
Let’s explore what we’ve learned so far this semester!

---
layout: center
class: text-left text-[1vw]
---

### 👥 Circle 15 Members

| Name                           | Status       |
|--------------------------------|--------------|
| Ritda Evelyn Aleburu           | ✅ Active    |
| Asogwa Ifunanyachukwu Ruth     | ✅ Active    |
| Marvelous Udugbesi             | ✅ Active    |
| **Motunrayo Adeneye**          | ❌ Inactive  |
| Boluwatife Moyaki              | ✅ Active    |
| Omowunmi Olawehinmi            | ✅ Active    |
| Merveille Njikou Naomi         | ✅ Active    |
| Mubarak Bello O                | ✅ Active    |
| Chukwuma Kosiso Jennifer       | ✅ Active    |
| Chioma Ineh                    | ✅ Active    |
| Tochukwu Ejiofor               | ✅ Active    |

> We're committed to learning together and supporting each other through the journey.

---

## 🔗 External Resources

Here are some helpful links and tools that were recommended to be used throughout the semester:

- [Refactoring UI](https://www.refactoringui.com/) — Frontend Masters
- [Learning How to Learn](https://www.coursera.org/learn/learning-how-to-learn?action=enroll) — Coursera



---

## 📚 Topics Covered

- Introduction to JavaScript
- Variables & Data Types
- Operators
- Conditionals
- Loops
- Functions
- Arrays & Objects
- DOM Manipulation

---

## 📚 Arrays

---

## ✅ What is an Array?

An **array** is a special variable used to **store multiple values** in a single variable name. It helps in organizing and managing collections of data efficiently.

Think of it like a container holding items in a specific order. Each item can be accessed using its index.

```javascript
let fruits = ["apple", "banana", "cherry"];
console.log(fruits[0]); // Output: apple 
```
---

## ✅ Array Methods

In JavaScript, array methods are built-in functions that help you manipulate and interact with arrays.These methods make it easier to write shorter and cleaner code.They let you add, remove, update, loop through, and transform array elements with cleaner code. Some of the common array methods includes:


### 🔹 Push

Adds a new item to the end of an array.

```javascript
fruits.push("orange");
console.log(fruits); // ["apple", "banana", "cherry", "orange"]
```

### 🔹 Pop

Removes the last element from an array.

```javascript
fruits.push("orange");
console.log(fruits); // ["apple", "banana", "cherry", "orange"]
```
---

### 🔹Shift

Removes the first element from an array.

```javascript
let fruits = ["apple", "banana", "orange"];
fruits.shift();
console.log(fruits); // ["banana", "orange"]

```

### 🔹Unshift

Adds one or more elements to the beginning of an array.

```javascript
let fruits = ["banana", "orange"];
fruits.unshift("apple");
console.log(fruits); // ["apple", "banana", "orange"]

```

### 🔹 Slice
Returns a shallow copy of a portion of an array.

```javascript
let fruits = ["apple", "banana", "orange", "grape"];
let sliced = fruits.slice(1, 3);
console.log(sliced); // ["banana", "orange"]

```
---

### 🔹  Splice
Changes the contents of an array by removing or replacing existing elements.

```javascript
let fruits = ["apple", "banana", "orange"];
fruits.splice(1, 1, "grape");
console.log(fruits); // ["apple", "grape", "orange"]
```

### 🔹  For each

Executes a function for each element in the array

```javascript
let fruits = ["apple", "banana", "orange"];
fruits.splice(1, 1, "grape");
console.log(fruits); // ["apple", "grape", "orange"]


```

### 🔹  Filter

Creates a new array with elements that pass a condition.

```javascript
const numbers = [1, 2, 3, 4, 5];
const evens = numbers.filter(num => num % 2 === 0);
console.log(evens); // [2, 4]

```
---

## 📚 Functions
---

## 🚀 What is a Function?

A **function** is a reusable block of code designed to perform a specific task. It helps break your program into smaller, manageable parts. You can call a function multiple times without rewriting code.


## 📚 Function Syntax

```js
function functionName(parameters) {
  // code to be executed
}
```

 Example

```js
 function greet(name) {
  console.log("Hello, " + name + "!");
}

greet("Jhennifer");
```

---

## 🧰 Types of Function


- Function Declaration
```js
function add(a, b) {
  return a + b;
}

console.log(add(3, 4)); // 7
```

- Function Expression
```js
const multiply = function (x, y) {
  return x * y;
};

console.log(multiply(5, 2)); // 10

```

- Arrow Function (ES6)

##### This is a shorter and cleaner way to write functions.
```js
const divide = (a, b) => a / b;

console.log(divide(10, 2)); // 5


```
---

- Anonymous Function 

##### Functions without a name, often used as callbacks.
```js
setTimeout(function () {
  console.log("This runs after 2 seconds");
}, 2000);

```
<br/>

## 🔄 Returning Values from Functions
#### Functions can return values using the return keyword.

```js
function square(num) {
  return num * num;
}

const result = square(6);
console.log(result); // 36
```
<br/>

## ⚙️ Parameters vs Arguments
Parameters are variables in function definition. Arguments on the other hand are actual values passed when calling the function

---

```js
Copy code
function sayHello(name) {  // name is a parameter
  console.log("Hello, " + name);
}

sayHello("Chioma"); // "Chioma" is the argument
```
<br/>

## ✅ Why Use Functions?
1. Improves code reusability

2. Easier debugging

3. Clean and organized code

4. Helps divide complex problems
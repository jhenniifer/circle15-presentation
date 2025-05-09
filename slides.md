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
## 📌 Topic: ARRAYS  
### 👩🏽‍💻 Circle 15 Presentation  
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
`

### 🔹  For each

Executes a function for each element in the array

```javascript
let fruits = ["apple", "banana", "orange"];
fruits.splice(1, 1, "grape");
console.log(fruits); // ["apple", "grape", "orange"]


```
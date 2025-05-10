---
theme: default
class: text-center
title: Circle 15 JavaScript Journey
date: 2025-05-07
---

## 🎉 Welcome to Circle 15's Recap  
### A Journey Through JavaScript  
Let’s explore what we’ve learned so far this semester!

---
layout: center
class: text-left text-[.7vw]
---

### 👥 Circle 15 Members

| Name                           | Status       |
|--------------------------------|--------------|
| Ritda Evelyn Aleburu           | ✅ Active    |
| Asogwa Ifunanyachukwu Ruth     | ✅ Active    |
| Marvelous Udugbesi             | ✅ Active    |
| Motunrayo Adeneye              | ✅ Active    |
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

<br/>
<br/>
<br/>
<img src="./images/array.svg" alt="array" width="700" he/>

---
## 📌 Topic: ARRAYS  
### 👩🏽‍💻 Circle 15 Presentation  
---

## ✅ What is an Array?

An **array** is a special variable used to **store multiple values** in a single variable name. It helps in organizing and managing collections of data efficiently.  It can numbers, string and other data types as values. 


```javascript
let myArray = []
```


If we check the console to know the type of of the myArray.This will output object.

```javascript
let myArray = [];
console.log(typeof(myArray)); //object
console.log(typeof myArray); //object
```



Think of it like a container holding items in a specific order. Each item can be accessed using its index.

```javascript
let fruits = ["apple", "banana", "cherry"];
console.log(fruits[0]); // Output: apple 
```


Array can hold all kind of data types including numbers, objects and nested array.

```javascript
let myArray = [42, "Hello, World!", true, { name: "Alice", age: 30 }, [1, 2, 3], ]

```

---

## **To create array, you can create it by using**:

<br/>

- To create array, you can create it by using:


```javascript
let fruits = ["apple", "banana"];
console.log(fruits);// ["apple", "banana"]
```

- Using Arrow constructor

```javascript
let colors = new Array("pink", "red", "brown");
console.log(colors);// ["pink", "red", "brown"]
```


To access an array, you have to use indexing method. Array are indexed by number, starting from 0. It is zero-index based starting from 0 to 9. It tells the position of the value, if interchanged the position also change.

```javascript
let person =["John", "Doe", "Hope"]
// Accessing the elements
console.log(person[0]); // John
console.log(person[1]);// Doe
console.log(person[2]);// Hope
```

---

Another way to access is using the method length property `arrayName.length` .

```javascript
const fruits = ["Tangerine", "Banana", "Cherry", "Pawpaw"];  
console.log(fruits.length)// 4
console.log(fruits[fruits.length -1])//Pawpaw
```

<br/>

```javascript
const fruits = ["Tangerine", "Banana", "Cherry", "Pawpaw"];  
console.log(fruits.length)// 4
console.log(fruits[fruits.length -2]) //Cherry
```

<br/>

```javascript
const myArray = [];
console.log(myArray.length); // 0
```
<br/>

```javascript
const mixedArray = [20, 4, "Pawpaw", "Watermelon", 6, 7];  
console.log(mixedArray.length) // 6
console.log(mixedArray[mixedArray.length - 1]) // 7
```

<br/>
---


## ✅ Array Methods

<br/>

<img src="./images/array_methods.svg" alt="array_method" width="300" />


<br/>

In JavaScript, array methods are built-in functions that help you manipulate and interact with arrays.These methods make it easier to write shorter and cleaner code.They let you add, remove, update, loop through, and transform array elements with cleaner code. Some of the common array methods includes:


#### 🔸Push

Adds a new item to the end of an array.

```javascript
fruits.push("orange");
console.log(fruits); // ["apple", "banana", "cherry", "orange"]
```
---

#### 🔹Pop

Removes the last element from an array.

```javascript
fruits.push("orange");
console.log(fruits); // ["apple", "banana", "cherry", "orange"]
```
<br/>

#### 🔸Shift

Removes the first element from an array.

```javascript
let fruits = ["apple", "banana", "orange"];
fruits.shift();
console.log(fruits); // ["banana", "orange"]
```
<br/>

#### 🔹Unshift

Adds one or more elements to the beginning of an array.

```javascript
let fruits = ["banana", "orange"];
fruits.unshift("apple");
console.log(fruits); // ["apple", "banana", "orange"]
```
---

#### 🔸Slice
Returns a shallow copy of a portion of an array.
To output a new array from the original array without modifying the array. In this case the output will start from the startIndex and stop at the endIndex - startIndex.

```javascript
myArray.slice(startIndex, endLength)
```

```javascript
let fruits = ["apple", "banana", "orange", "grape"];
let sliced = fruits.slice(1, 3);
console.log(sliced); // ["banana", "orange"]
```

From the example above the output is `["banana", "orange"]` in which the startIndex is 1 and the counting start from there to the endIndex which is 3 - the startIndex which is 1. This will be equal to 2 which will be the length of where it stops. At the end, it will output 2 items.

#### 🔹Splice
Changes the contents of an array by removing or replacing existing elements.

```javascript
let fruits = ["apple", "banana", "orange"];
fruits.splice(1, 1, "grape");
console.log(fruits); // ["apple", "grape", "orange"]
```

---

#### 🔸ForEach

Executes a function for each element in the array

```javascript
let fruits = ["apple", "banana", "orange"];
fruits.splice(1, 1, "grape");
console.log(fruits); // ["apple", "grape", "orange"]
``` 
---

### 🔹IndexOf

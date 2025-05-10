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

## ☆ Introduction to javascript

<br/>

<img src="/images/javascript.svg" alt="javascript"/>

---
## 📌 Topic: JAVASCRIPT
### 👩🏽‍💻 Circle 15 Presentation  
---


## 📚 Javascript

Javascript is a programming language that was initially built for client-side execution, it is used to build web pages and web applications. This language makes a static web page to be dynamic and interactive. JavaScript is therefore executed in the browser.

Traditionally JavaScript is used for client-side only since it is an open source project, developers were able to think, modify it and integrate Nodejs for it to serve as a server-side.

JavaScript was created by a wonderful programmer, **Brendan Eich** in 1995, he then was a programmer at Netscape and he developed it in 10days. At that time JavaScript was called **"Mocha"**, before it latter became what is called now.

To add interactivity to a web page, JavaScript significantly should be added to the web page or part of the web page where we want it. When users come across forms on a web page, they have no idea that adding JavaScript to the web page has made they to be able to fill the form and may also get a feedback message that the form have been submitted.

---

### 📌File structure
JavaScript language is mostly written using a code editor. Each file created for JavaScript must be written in a `.js` extension for proper execution. The file name can be called `main.js`, `index.js` or `script.js.`

### Implementation
There are different ways of implementing JavaScript depending what you want to do with it.

For a client-side execution: JavaScript can be used along it HTML and CSS. It can be implemented internally that is by adding the script tag `<script> </script>`inside the HTML file. It will enhance the manipulation of the html tags to modify the content.
It can also be implemented externally by isolating its logic in a whole new file with a .js extension and hence imported in the HTML file for execution.
`<script src='./main.js'></script>`.

For Server side extension: it is only implemented in the .js file extension which can run using the command

```javascript
node server.js
```

This command will work if you have saved the file as `server.js` and vice versa.
---

## 📝Data types
Data is the kind of information that the program possesses.

<img src="./images/data_types.svg" alt="data types" width="500"/>

They are two type of data; **Primitive** and **Composite** data types.

- **Primitive** data type is the set of individual data type that make up a sentence or statement.

There are different types of primitive data types

- String: This includes letters, words, or sentences which are denoted starting with single quotes ('') double quotes ("") or backticks(``).

```javascript
let greeting =  "Hello World";
var community = 'It is Dev Community'; 
var fullName = `Hi, I am ${name}`;
```

---

- Number: This represents number; integer and floating point. Examples are 5, 10, 9.6.

```javascript
var age = 30
const simpleInterest = 30.9
```

- Boolean: This represents logical values; true and false.

```javascript
const isOpen = false;
var isExpanded = true;
```

- Undefined: This represents unassigned variable. It is when a variable is declared but not assigned to a value.

```javascript
var greeting;
```

- Null: This represents the absence of value.

```javascript
let unSpecific = null;
```

---

- **Non-primitive or Composite data type**

This is the collection of primitive data types. There are three types of composite data types; arrays and object.

- a. Array: An array is the collection of values. It can numbers, string and other data types as values. They are special kind of object where the key is not visible until it is accessed.

```javascript
let fruits = ["apple", "banana"];
```

<br/>

- b. Objects: An object is a stand alone entity. They are true representation of data that exist in key-value pair where key is the variable. It is denoted using curly bracket {}.

```javascript
const student = {
name: "Motunrayo", 
age: 30, 
language: "Yoruba" 
}
```
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

<br/>

#### 🔹IndexOf

To find the index of a particular element of the array.

```javascript
let numbers = [1, 2, 3 , 4 ,5]
console.log(numbers.indexOf(4)) // 3
```

This output 3 which is the position of number 4 of the array when we start indexing from one.

``` javascript
let numbers = [1, 2, 3 , 4 ,5] 
console.log(numbers.indexOf("zero")) //-1
```

---

## DOM Manipulation
# JavaScript Syllabus

---

## Table of content

# Table of Contents

- [Temario JavaScript ### Jon Mircha](#temario-javascript-jon-mircha)
- [1. Introduction & Basic Fundamentals](#1-introduction-and-basic-fundamentals)
  - [1.1 Variables: var 🥊VS🥊 let](#11-variables-var-vs-let)
  - [1.2 Constants (const)](#12-constants-const)
  - [1.3 Strings](#13-strings)
  - [1.4 Template Strings](#14-template-strings)
  - [1.5 Numbers](#15-numbers)
  - [1.6 Booleans](#16-booleans)
  - [1.7 undefined, null & NaN](#17-undefined-null-and-nan)
- [2. Functions](#2-functions)
  - [2.1 Function Declarations](#21-function-declarations)
  - [2.2 REST Parameters & Spread Operator](#22-rest-parameters-and-spread-operator)
  - [2.3 Immediately Invoked Function Expressions (IIFE)](#23-immediately-invoked-function-expressions-iife)
  - [2.4 Arrow Functions](#24-arrow-functions)
  - [2.5 Static Methods, Getters and Setters](#25-static-methods-getters-and-setters)
  - [2.6 Higher-Order Functions](#26-higher-order-functions)
- [3. Arrays & Objects](#3-arrays-and-objects)
  - [3.1 Arrays](#31-arrays)
  - [3.2 Objects](#32-objects)
  - [3.3 Destructuring](#33-destructuring)
  - [3.4 Object Literals](#34-object-literals)
  - [3.5 Prototypes](#35-prototypes)
  - [3.6 Prototypal Inheritance](#36-prototypal-inheritance)
  - [3.7 Classes & Inheritance](#37-classes-and-inheritance)
  - [3.8 Dynamic Object Properties](#38-dynamic-object-properties)
- [4. Operators & Conditionals](#4-operators-and-conditionals)
  - [4.1 Types of Operators](#41-types-of-operators)
  - [4.2 Conditionals](#42-conditionals)
  - [4.3 Loops](#43-loops)
  - [4.4 break & continue](#44-break-and-continue)
  - [4.5 Short-Circuit Evaluation](#45-short-circuit-evaluation)
  - [4.6 alert, confirm, and prompt](#46-alert-confirm-and-prompt)
- [5. Error Handling](#5-error-handling)
  - [5.1 Error Handling](#51-error-handling)
  - [5.2 try / catch](#52-try-catch)
  - [5.3 throw](#53-throw)
- [6. Special Objects & Methods](#6-special-objects-and-methods)
  - [6.1 console Object](#61-console-object)
  - [6.2 Date Object](#62-date-object)
  - [6.3 Math Object](#63-math-object)
  - [6.4 Regular Expressions](#64-regular-expressions)
- [7. Advanced Functions](#7-advanced-functions)
  - [7.1 this Keyword](#71-this-keyword)
  - [7.2 call, apply, bind](#72-call-apply-bind)
  - [7.3 JSON](#73-json)
- [8. Modules & Logic Projects](#8-modules-and-logic-projects)
  - [8.1 ES Modules (import / export)](#81-es-modules-import--export)
- [9. Timers & Asynchronous JavaScript](#9-timers-and-asynchronous-javascript)
  - [9.1 Timers (setTimeout, setInterval)](#91-timers-settimeout-setinterval)
  - [9.2 Asynchronous JavaScript & Event Loop](#92-asynchronous-javascript-and-event-loop)
  - [9.3 Callbacks](#93-callbacks)
  - [9.4 Promises](#94-promises)
  - [9.5 async / await](#95-async--await)
  - [9.6 Symbols](#96-symbols)
- [10. Data Structures](#10-data-structures)
  - [10.1 Sets](#101-sets)
  - [10.2 Maps](#102-maps)
  - [10.3 WeakSets & WeakMaps](#103-weaksets-and-weakmaps)
  - [10.4 Iterables & Iterators](#104-iterables-and-iterators)
  - [10.5 Generators](#105-generators)
  - [10.6 Proxies](#106-proxies)
- [11. DOM (Document Object Model)](#11-dom-document-object-model)
  - [11.1 DOM Introduction](#111-dom-introduction)
  - [11.2 Nodes, Elements & Selectors](#112-nodes-elements--selectors)
  - [11.3 Attributes & Data-Attributes](#113-attributes--data-attributes)
  - [11.4 Styles & CSS Variables](#114-styles--css-variables)
  - [11.5 CSS Classes](#115-css-classes)
  - [11.6 Text & HTML](#116-text--html)
  - [11.7 DOM Traversing](#117-dom-traversing)
  - [11.8 Creating Elements & Fragments](#118-creating-elements--fragments)
  - [11.9 HTML Templates](#119-html-templates)
  - [11.10 Modifying Elements](#1110-modifying-elements)
  - [11.11 Event Listeners](#1111-event-listeners)
  - [11.12 Events with Parameters & Removing Events](#1112-events-with-parameters--removing-events)
  - [11.13 Event Flow (Bubbling & Capturing)](#1113-event-flow-bubbling--capturing)
  - [11.14 stopPropagation & preventDefault](#1114-stoppropagation--preventdefault)
  - [11.15 Event Delegation](#1115-event-delegation)
- [12. BOM (Browser Object Model)](#12-bom-browser-object-model)
  - [12.1 Properties & Events](#121-properties--events)
- [13. AJAX (Asynchronous JavaScript and XML)](#13-ajax-asynchronous-javascript-and-xml)
  - [13.1 AJAX Introduction](#131-ajax-introduction)
  - [13.2 XMLHttpRequest Object](#132-xmlhttprequest-object)
  - [13.3 Fetch API](#133-fetch-api)
  - [13.4 Fetch API + async / await](#134-fetch-api--async--await)
  - [13.5 Axios Library](#135-axios-library)
  - [13.6 Axios + async / await](#136-axios--async--await)
- [14. REST API (Representational State Transfer)](#14-rest-api-representational-state-transfer)
  - [14.1 Introduction to REST API](#141-introduction-to-rest-api)
  - [14.2 JSON Server (Local Fake API)](#142-json-server-local-fake-api)
  - [14.3 Consuming REST Data](#143-consuming-rest-data)
  - [14.4 CRUD (Create, Read, Update, Delete)](#144-crud-create-read-update-delete)
  - [14.5 CRUD with AJAX (Part 1 & 2)](#145-crud-with-ajax-part-1--2)
  - [14.6 CRUD with Fetch (Part 1 & 2)](#146-crud-with-fetch-part-1--2)
  - [14.7 CRUD with Axios (Part 1 & 2)](#147-crud-with-axios-part-1--2)
- [15. WordPress REST API](#15-wordpress-rest-api)
  - [15.1 WordPress REST API + Fetch (1/5 to 5/5)](#151-wordpress-rest-api--fetch-15-to-55)
  - [15.2 Infinite Scroll](#152-infinite-scroll)
- [16. SPA (Single Page Application)](#16-spa-single-page-application)
  - [16.1 SPA Introduction](#161-spa-introduction)
  - [16.2 Project Structure (assets, helpers, components)](#162-project-structure-assets-helpers-components)
  - [16.3 REST API Connection Helper](#163-rest-api-connection-helper)
  - [16.4 AJAX Requests Helper](#164-ajax-requests-helper)
  - [16.5 First UI Components](#165-first-ui-components)
  - [16.6 Header Component](#166-header-component)
  - [16.7 Dynamic Rendering](#167-dynamic-rendering)
  - [16.8 Routing (Router)](#168-routing-router)
  - [16.9 App Refactoring & Async Routing](#169-app-refactoring-and-async-routing)
  - [16.10 Current Post View](#1610-current-post-view)
  - [16.11 Internal Search](#1611-internal-search)
  - [16.12 Current Search View](#1612-current-search-view)
  - [16.13 Infinite Scroll & Higher-Order Components](#1613-infinite-scroll-and-higher-order-components)
  - [16.14 Styled Components & Single File Components](#1614-styled-components-and-single-file-components)
- [17. Reactivity](#17-reactivity)

  - [17.1 Reactivity Introduction](#171-reactivity-introduction)
  - [17.2 Non-Reactive DOM Manipulation](#172-non-reactive-dom-manipulation)
  - [17.3 UI Based on State](#173-ui-based-on-state)
  - [17.4 Reactive State](#174-reactive-state)
  - [17.5 Immutable State](#175-immutable-state)
  - [17.6 Components with State](#176-components-with-state)
  - [17.7 Component Library](#177-component-library)

    20.1 [Introduction to Redux with Vanilla JS](#201-introduction-to-redux-with-vanilla-js)

---

## **1. Introduction & Basic Fundamentals**

### **1.1 Variables: var 🥊VS🥊 let**

#### **Explanation**

In JavaScript, variables are like containers where you store data.
Both var and let are used to create variables, but they have different rules:

- var – the old way (before 2015). It has function scope, meaning it is available everywhere inside the function where it’s declared, or globally if outside a function. It can also be redeclared and updated, which sometimes causes bugs.

- let – the modern way (introduced in ES6, 2015). It has block scope, meaning it only exists inside the { } where it’s declared. It can be updated, but cannot be redeclared in the same scope.

💡 Tip: Always prefer let (or const) instead of var to avoid unexpected behavior.

#### **Real-life use cases**

- Temporary variables that will change, like counters, loops, or temporary storage for calculations → use let.

- Old code maintenance → you might still see var in older projects, so you must understand it to read legacy code.

- Debugging scope problems → knowing the difference helps avoid using variables accidentally outside their intended block.

#### **Examples**

Example 1 – var leaks outside the block:

```js
if (true) {
  var name = "Kevin";
}
console.log(name); // ✅ "Kevin" (accessible outside the block)
```

Example 2 – let stays inside the block:

```js
if (true) {
  let age = 28;
}
console.log(age); // ❌ ReferenceError: age is not defined
```

Example 3 – Redeclaring with var vs let:

```js
var city = "Guatemala";
var city = "Antigua"; // ✅ Allowed

let country = "Guatemala";
let country = "Mexico"; // ❌ Error: Identifier 'country' has already been declared
```

### **1.2 Constants (const)**

#### **Explanation**

const is used to declare variables that cannot be reassigned after their initial value is set.
However, it does not make the value itself immutable — for example, if it’s an object or array, you can still change its contents, just not reassign it to something else.

Think of const like a permanent label on a box:

- You can’t take the label off and put it on a different box (reassign).

- But you can still open the box and change what’s inside (modify properties or elements).

💡 Tip: Use const by default unless you know you’ll need to change the value, then use let.

#### **Real-life use cases**

- Configuration values that should never change (e.g., API URLs, tax rates).

- References to functions that won’t be reassigned.

- Avoiding accidental reassignments in large projects.

#### **Examples**

Example 1 – Cannot reassign a const:

```js
const pi = 3.1416;
pi = 3; // ❌ TypeError: Assignment to constant variable
```

Example 2 – You can modify objects and arrays:

```js
const user = { name: "Kevin", age: 28 };
user.age = 29; // ✅ Allowed
console.log(user); // { name: "Kevin", age: 29 }
```

Example 3 – Good practice with constants:

```js
const API_URL = "https://api.example.com";
const TAX_RATE = 0.15;

let price = 100;
let total = price + price * TAX_RATE;

console.log(total); // 115
```

### **1.3 Strings**

#### **Explanation**

A string is a sequence of characters (letters, numbers, symbols, spaces) used to represent text in JavaScript.
You can create a string using:

- Single quotes 'Hello'

- Double quotes "Hello"

- Backticks `Hello` (template strings, we’ll see in 1.4)

Strings are immutable — you can’t change individual characters directly, but you can create a new string with modifications.

#### **Real-life use cases**

- Displaying messages to the user.

- Storing names, addresses, or any text data.

- Manipulating text (search, replace, formatting).

- Building URLs or HTML dynamically.

#### **Examples**

Example 1 – Creating strings:

```js
let single = "Hello";
let double = "World";
console.log(single + " " + double); // "Hello World"
```

Example 2 – Accessing characters:

```js
let word = "JavaScript";
console.log(word[0]); // "J"
console.log(word.length); // 10
```

Example 3 – Common string methods:

```js
let message = "  Hello Kevin  ";
console.log(message.trim()); // "Hello Kevin" (removes spaces)
console.log(message.toUpperCase()); // "  HELLO KEVIN  "
console.log(message.includes("Kevin")); // true
```

### **1.4 Template Strings**

#### **Explanation**

Template strings (or template literals) are strings written with backticks ` instead of quotes.
They allow you to:

- Insert variables and expressions directly inside the string using ${ }.

- Write multi-line strings without using \n.

- Make your code more readable when combining text and variables.

#### **Real-life use cases**

- Creating dynamic messages (e.g., greetings, status updates).

- Building HTML in JavaScript without lots of + concatenations.

- Formatting strings that include calculated values or data from APIs.

#### **Examples**

Example 1 – Variables inside a string:

```js
let name = "Kevin";
let age = 28;

console.log(`My name is ${name} and I am ${age} years old.`);
// "My name is Kevin and I am 28 years old."
```

Example 2 – Expressions inside ${ }:

```js
let price = 50;
let tax = 0.15;

console.log(`Total price: $${price + price * tax}`);
// "Total price: $57.5"
```

Example 3 – Multi-line strings:

```js
let poem = `Roses are red,
Violets are blue,
JavaScript is fun,
And so are you.`;

console.log(poem);
```

### **1.5 Numbers**

#### **Explanation**

In JavaScript, numbers represent both integers (whole numbers) and floating-point numbers (decimals) — there’s no separate type for them like in some other languages.
JavaScript uses the IEEE 754 standard, so numbers are stored in 64-bit floating-point format, which sometimes causes small precision issues (e.g., 0.1 + 0.2 is not exactly 0.3).

#### **Real-life use cases**

- Doing mathematical calculations (prices, taxes, measurements).

- Storing counts, IDs, or quantities.

- Working with dates (timestamps are numbers).

- Performing operations in games, timers, or animations.

#### **Examples**

Example 1 – Integers and decimals:

```js
let apples = 5; // integer
let price = 1.99; // decimal
console.log(apples, price); // 5 1.99
```

Example 2 – Mathematical operations:

```js
let a = 10;
let b = 3;

console.log(a + b); // 13
console.log(a - b); // 7
console.log(a * b); // 30
console.log(a / b); // 3.333...
console.log(a % b); // 1 (remainder)
```

Example 3 – Precision issue:

```js
console.log(0.1 + 0.2); // 0.30000000000000004
```

To fix this, you can round:

```js
console.log(Number((0.1 + 0.2).toFixed(2))); // 0.3
```

### **1.6 Booleans**

#### **Explanation**

A boolean is a data type that can only be true or false.
They are mainly used in conditions to decide what parts of the code should run.
In JavaScript, many values can be implicitly converted to true or false — we call them truthy and falsy values.

Falsy values in JavaScript:

- false
- 0
- "" (empty string)
- null
- undefined
- NaN

Everything else is considered truthy.

#### **Real-life use cases**

- Checking if a user is logged in (isLoggedIn = true).

- Validating forms (isValid = false).

- Controlling game logic (isGameOver = false).

- Enabling or disabling buttons in an app.

#### **Examples**

Example 1 – Basic usage:

```js
let isOnline = true;
let hasPremium = false;

if (isOnline) {
  console.log("User is online.");
} else {
  console.log("User is offline.");
}
```

Example 2 – Using boolean expressions:

```js
let age = 20;
let canVote = age >= 18; // true
console.log(canVote); // true
```

Example 3 – Truthy and falsy:

```js
if ("Hello") {
  console.log("This is truthy!"); // ✅ Runs because "Hello" is not empty
}

if (0) {
  console.log("This will NOT run"); // ❌ Doesn't run because 0 is falsy
} else {
  console.log("This is falsy!"); // ✅ Runs because 0 is falsy
}
```

### **1.7 undefined, null & NaN**

#### **Explanation**

These are special values in JavaScript that represent different “empty” or “invalid” situations:

- undefined → Means a variable exists but has no value assigned yet.

- null → Means the variable has an intentional empty value (you set it to nothing on purpose).

- NaN → Stands for "Not a Number". It appears when a calculation fails to produce a valid number.

#### **Real-life use cases**

- undefined: A function that doesn’t explicitly return anything will return undefined.

- null: Resetting a variable when data is removed (e.g., when a user logs out).

- NaN: Detecting invalid math operations, like parsing text that’s not a number.

#### **Examples**

Example 1 – undefined:

```js
let name;
console.log(name); // undefined

function greet() {
  console.log("Hello!");
}
console.log(greet()); // Logs "Hello!" and then undefined (no return value)
```

Example 2 – null:

```js
let user = { name: "Kevin" };
user = null; // intentional reset
console.log(user); // null
```

Example 3 – NaN:

```js
let result = "hello" * 2;
console.log(result); // NaN

console.log(isNaN(result)); // true (checks if it's NaN)
```

## **2. Functions**

### **2.1 Function Declarations**

#### **Explanation**

A function declaration is a way to define a reusable block of code in JavaScript that performs a specific task.
It uses the function keyword followed by:

- A name (identifier) for the function.

- A list of parameters inside parentheses () (optional).

- A block of code inside curly braces {} that will run when the function is called.

Key points about function declarations:

- They are hoisted, meaning you can call them before they are defined in your code.

- They must have a name (unlike some function expressions).

- They make code organized and reusable.

#### **Real-life use cases**

- Reusability – For actions that repeat, like formatting dates or validating inputs.

- Organization – Breaks complex tasks into smaller, readable pieces.

- Maintainability – If the logic changes, you only update it in one place.

#### **Examples**

Example 1: Simple Greeting

```js
function greetUser(name) {
  console.log(`Hello, ${name}!`);
}

greetUser("Kevin"); // Output: Hello, Kevin!
```

✅ This avoids repeating the same console.log every time you want to greet someone.

Example 2: Calculate the Area of a Rectangle

```js
function calculateArea(width, height) {
  return width * height;
}

console.log(calculateArea(5, 3)); // Output: 15
```

✅ Useful when building apps that deal with geometry, graphics, or layout calculations.

Example 3: Hoisting

```js
sayHi(); // Output: Hi there!

function sayHi() {
  console.log("Hi there!");
}
```

✅ You can call sayHi() before defining it because function declarations are hoisted.

Hoisting is the behavior where variable and function declarations are moved to the top of their scope by the JavaScript engine before the code is executed.

It’s important to note:

- Only declarations are hoisted, not initializations/assignments.

- Functions declared with the function keyword are fully hoisted (you can call them before they appear in the code).

- Variables declared with var are hoisted but initialized as undefined.

- let and const are hoisted too, but they are in a temporal dead zone until the line of code where they are declared — so accessing them before that will throw an error.

The TDZ is the period between when a variable is hoisted and when it is initialized in the code.
During this time, if you try to access the variable, JavaScript will throw a ReferenceError.

### **2.2 REST Parameters & Spread Operator**

#### **Explanation**

**Rest Parameters (...)**

- Rest parameters let you collect multiple arguments into a single array inside a function.

- You write them with ... before the parameter name.

- They are useful when you don’t know in advance how many arguments will be passed to a function.

**Spread Operator (...)**

- Spread takes an array (or object) and expands it into individual values.

- It’s like unpacking things from a box.

- You use it when you need to pass multiple values, but you already have them in an array.

#### **Real-life use cases**

**Rest Parameters — When making a function that needs any number of arguments, like:**

- Calculators

- Math helpers

- String concatenation

**Spread Operator — When you:**

- Copy arrays or objects without modifying the original

- Merge arrays

- Pass array values as function arguments

#### **Examples**

Example 1: Rest Parameters for Flexible Functions

```js
function greetAll(...names) {
  names.forEach((name) => console.log(`Hello, ${name}!`));
}

greetAll("Alice", "Bob", "Charlie");
// Hello, Alice!
// Hello, Bob!
// Hello, Charlie!
```

Example 2: Spread Operator to Merge Arrays

```js
const fruits = ["apple", "banana"];
const moreFruits = ["orange", "grape"];

const allFruits = [...fruits, ...moreFruits];
console.log(allFruits);
// ["apple", "banana", "orange", "grape"]
```

Example 3: Spread Operator to Pass Arguments

```js
const numbers = [4, 7, 1];
console.log(Math.max(...numbers)); // 7
```

### **2.3 Immediately Invoked Function Expressions (IIFE)**

#### **Explanation**

An Immediately Invoked Function Expression (IIFE) is a JavaScript function that runs as soon as it is defined.
Instead of creating a function and calling it later, you wrap it in parentheses and immediately execute it.

Key points:

- It’s useful when you want code to run right away without leaving variables in the global scope.

- It helps avoid name conflicts between variables.

- It’s often used in older JavaScript patterns for encapsulation.

The syntax is:

```js
(function () {
  // code here
})();
```

The () after the function executes it immediately.

#### **Real-life use cases**

- Avoiding global variable pollution – Keeping variables private so they don’t conflict with other code.

- Initializing code only once – Running setup code when the page loads.

- Creating isolated modules – Organizing code in self-contained blocks.

#### **Examples**

Example 1 – Basic IIFE

```js
(function () {
  console.log("I run immediately!");
})();
```

Example 2 – IIFE with parameters

```js
(function (name) {
  console.log(`Hello, ${name}!`);
})("Kevin");
```

Example 3 – Avoiding global variables

```js
(function () {
  const secret = "hidden";
  console.log(secret); // works here
})();

console.log(secret); // ❌ Error: secret is not defined
```

### **2.4 Arrow Functions**

#### **Explanation**

Arrow functions are a shorter way to write functions in JavaScript, introduced in ES6.
They have a cleaner syntax, and unlike normal functions, they do not have their own this, arguments, super, or new.target. Instead, they take these from the place where they were created (lexical scope).

Key points:

- Shorter syntax → less code to write.

- Automatically return a value if written in one line without {}.

- Useful when you don’t want to change this (e.g., inside callbacks).

- Cannot be used as constructors (new won’t work).

#### **Real-life use cases**

- Writing short, one-line functions (e.g., mapping or filtering arrays).

- Keeping this from the outer scope in event handlers or callbacks.

- Cleaner syntax in async code like fetch() calls.

#### **Examples**

Example 1

```js
// Example 1: Short function for simple return
const double = (num) => num * 2;
console.log(double(4)); // 8
```

Example 2

```js
// Example 2: Arrow function in array methods
const numbers = [1, 2, 3];
const squares = numbers.map((n) => n * n);
console.log(squares); // [1, 4, 9]
```

Example 2

```js
// Example 3: Keeping 'this' in callbacks
function Timer() {
  this.seconds = 0;
  setInterval(() => {
    this.seconds++;
    console.log(this.seconds);
  }, 1000);
}
new Timer(); // increments seconds every second
```

### **2.5 Static Methods, Getters and Setters**

#### **Explanation**

Static methods, getters, and setters are special types of methods in JavaScript classes.

- Static methods belong to the class itself, not to instances (objects) created from the class. You call them directly on the class.

- Getters allow you to define a method that behaves like a property when you access it. It’s a way to read a value.

- Setters allow you to define a method that runs when you assign a value to a property. It’s a way to control or validate setting values.

#### **Real-life use cases**

- Static methods are great for utility functions related to the class but that don’t need an instance, like creating instances from JSON or performing calculations.

- Getters are useful to create computed properties, for example, combining first and last names into a full name.

- Setters help validate or sanitize data before saving it in a property.

#### **Examples**

Example 1 – Static method

```js
class MathHelper {
  static add(a, b) {
    return a + b;
  }
}

console.log(MathHelper.add(3, 7)); // 10
```

Example 2 – Getter

```js
class Person {
  constructor(firstName, lastName) {
    this.firstName = firstName;
    this.lastName = lastName;
  }

  get fullName() {
    return `${this.firstName} ${this.lastName}`;
  }
}

const p = new Person("Kevin", "Burrión");
console.log(p.fullName); // Kevin Burrión
```

Example 3 – Setter

```js
class Rectangle {
  constructor(width, height) {
    this.width = width;
    this.height = height;
  }

  set width(value) {
    if (value <= 0) {
      console.log("Width must be positive.");
      return;
    }
    this._width = value;
  }

  get width() {
    return this._width;
  }
}

const rect = new Rectangle(10, 5);
rect.width = -3; // Width must be positive.
console.log(rect.width); // 10 (unchanged)
```

### **2.6 Higher-Order Functions**

#### **Explanation**

Higher-order functions are functions that can take other functions as arguments, or return functions as results.

They allow you to write more flexible, reusable, and concise code.

In JavaScript, many built-in array methods like .map(), .filter(), and .reduce() are examples of using higher-order functions because they take functions as parameters.

#### **Real-life use cases**

- Processing arrays (filtering, transforming, reducing data).

- Implementing callbacks and event handlers.

- Creating functions that generate other functions dynamically (function factories).

- Composing functions in functional programming.

#### **Examples**

Example 1 – Function as argument

```js
function greet(name) {
  return `Hello, ${name}!`;
}

function welcomeUser(func, userName) {
  console.log(func(userName));
}

welcomeUser(greet, "Kevin"); // Hello, Kevin!
```

Example 2 – Array .map() with a function

```js
const numbers = [1, 2, 3];
const doubled = numbers.map((num) => num * 2);
console.log(doubled); // [2, 4, 6]
```

Example 3 – Function returning another function

```js
function multiplier(factor) {
  return function (num) {
    return num * factor;
  };
}

const double = multiplier(2);
console.log(double(5)); // 10
```

## **3. Arrays & Objects**

### **3.1 Arrays**

#### **Explanation**

An array in JavaScript is an ordered collection of values, where each value is stored in an index starting from 0.

Arrays can hold any type of data — numbers, strings, objects, even other arrays — and can be dynamically resized.

They are one of the most commonly used data structures in JavaScript for storing and manipulating lists of items.

Key points:

- Index-based access (first element is index 0).

- Dynamic length (you can add/remove items at any time).

- Have built-in methods like .push(), .pop(), .map(), .filter(), etc.

#### **Real-life use cases**

- Storing lists of data like products in an e-commerce site, names in a contact list, or scores in a game.

- Iterating through collections to apply an action to each element.

- Filtering and transforming data from APIs or databases.

- Implementing queues or stacks in algorithms.

- Grouping related values under a single variable for easier management.

#### **Examples**

Example 1 – Basic creation and access

```js
const fruits = ["Apple", "Banana", "Cherry"];
console.log(fruits[0]); // "Apple"
console.log(fruits[2]); // "Cherry"
```

Example 2 – Adding and removing items

```js
const numbers = [1, 2, 3];
numbers.push(4); // Add at the end
numbers.unshift(0); // Add at the start
console.log(numbers); // [0, 1, 2, 3, 4]

numbers.pop(); // Remove last
numbers.shift(); // Remove first
console.log(numbers); // [1, 2, 3]
```

Example 3 – Looping through arrays

```js
const colors = ["Red", "Green", "Blue"];
colors.forEach((color) => console.log(color));
// Red
// Green
// Blue
```

Example 4 – Transforming with map()

```js
const prices = [10, 20, 30];
const withTax = prices.map((price) => price * 1.15);
console.log(withTax); // [11.5, 23, 34.5]
```

Example 5 – Filtering

```js
const ages = [15, 18, 22, 30];
const adults = ages.filter((age) => age >= 18);
console.log(adults); // [18, 22, 30]
```

### **3.2 Objects**

#### **Explanation**

An object in JavaScript is a collection of key–value pairs, where:

- Keys (also called properties) are strings (or Symbols).

- Values can be any data type — strings, numbers, arrays, other objects, or even functions.

Objects are used to represent structured data and real-world entities. They allow grouping related properties and behavior into a single unit.

Key points:

- Objects are unordered (property order is not guaranteed, unlike arrays).

- You can access properties with dot notation (obj.key) or bracket notation (obj["key"]).

- Properties can be added, updated, or removed at any time.

- Methods are just functions stored as object properties.

#### **Real-life use cases**

- Representing entities like users, products, books, orders.

- Configuration settings for applications.

- Grouping related data from APIs or forms.

- Encapsulating behavior (methods) inside the object itself.

- Data transfer between frontend and backend (JSON format is based on objects).

#### **Examples**

Example 1 – Creating and accessing an object

```js
const user = {
  name: "Alice",
  age: 25,
  isAdmin: true,
};

console.log(user.name); // "Alice"
console.log(user["age"]); // 25
```

Example 2 – Adding, updating, and deleting properties

```js
const car = { brand: "Toyota" };
car.model = "Corolla"; // add
car.brand = "Honda"; // update
delete car.model; // remove

console.log(car); // { brand: "Honda" }
```

Example 3 – Object with methods

```js
const calculator = {
  add: function (a, b) {
    return a + b;
  },
  multiply(a, b) {
    // short method syntax
    return a * b;
  },
};

console.log(calculator.add(2, 3)); // 5
console.log(calculator.multiply(4, 5)); // 20
```

Example 4 – Nested objects

```js
const person = {
  name: "Bob",
  address: {
    city: "New York",
    zip: 10001,
  },
};

console.log(person.address.city); // "New York"
```

Example 5 – Using objects to group related data

```js
const product = {
  id: 1,
  name: "Laptop",
  price: 999.99,
  specs: {
    cpu: "Intel i7",
    ram: "16GB",
    storage: "512GB SSD",
  },
};

console.log(`${product.name} costs $${product.price}`);
```

### **3.3 Destructuring**

#### **Explanation**

Destructuring is a JavaScript syntax that allows you to extract values from arrays or properties from objects and assign them to variables in a concise way.

Instead of accessing each item or property individually, destructuring lets you do it in one clean statement.

There are two main types:

- Array destructuring — unpack values from arrays.

- Object destructuring — extract properties from objects by name.

Key points:

- Makes code shorter and more readable.

- You can assign default values if a property or element is missing.

- You can rename variables when destructuring objects.

#### **Real-life use cases**

- Getting values from function returns (when returning multiple values as arrays or objects).

- Extracting specific properties from large objects or API responses.

- Swapping variables without a temporary variable (with arrays).

- Cleaner code when dealing with nested data structures.

- Simplifying parameter handling in functions that receive objects.

#### **Examples**

Example 1 – Array destructuring

```js
const rgb = [255, 200, 0];
const [red, green, blue] = rgb;

console.log(red); // 255
console.log(green); // 200
console.log(blue); // 0
```

Example 2 – Object destructuring

```js
const user = {
  name: "Maria",
  age: 30,
  city: "London",
};

const { name, city } = user;
console.log(name); // "Maria"
console.log(city); // "London"
```

Example 3 – Renaming and default values

```js
const user = {
  name: "John",
  age: 22,
};

const { name: userName, city = "Unknown" } = user;
console.log(userName); // "John"
console.log(city); // "Unknown" (default because city is missing)
```

Example 4 – Swapping variables with array destructuring

```js
let a = 1,
  b = 2;
[a, b] = [b, a];
console.log(a); // 2
console.log(b); // 1
```

Example 5 – Destructuring function parameters

```js
function greet({ name, age }) {
  console.log(`Hello ${name}, you are ${age} years old.`);
}

const person = { name: "Anna", age: 28 };
greet(person); // Hello Anna, you are 28 years old.
```

### **3.4 Object Literals**

#### **Explanation**

Object literals are a concise way to create objects using a simple syntax with curly braces {}.
In ES6, object literals got some new features to make creating objects easier and more readable:

- Property shorthand: when the property name is the same as the variable name, you can omit the value.

- Method shorthand: you can define methods without the function keyword.

- Computed property names: you can use expressions inside square brackets [] to define dynamic property names.

These improvements reduce boilerplate code and improve clarity.

#### **Real-life use cases**

- Creating objects quickly from variables with the same name.

- Defining methods inside objects in a clean, compact way.

- Using dynamic keys when the property name depends on a variable or expression.

- Building configuration objects or data structures for applications.

#### **Examples**

Example 1 – Property shorthand

```js
const name = "Kevin";
const age = 28;

const user = {
  name, // same as name: name
  age, // same as age: age
};

console.log(user); // { name: "Kevin", age: 28 }
```

Example 2 – Method shorthand

```js
const calculator = {
  add(a, b) {
    return a + b;
  },
  multiply(a, b) {
    return a * b;
  },
};

console.log(calculator.add(2, 3)); // 5
console.log(calculator.multiply(4, 5)); // 20
```

Example 3 – Computed property names

```js
const propName = "score";
const player = {
  [propName]: 100,
};

console.log(player.score); // 100
```

Example 4 – Dynamic method names

```js
const method = "sayHello";
const obj = {
  [method]() {
    return "Hello!";
  },
};

console.log(obj.sayHello()); // "Hello!"
```

### **3.5 Prototypes**

#### **Explanation**

In JavaScript, every object has a hidden property called a prototype. This prototype is another object that the original object inherits properties and methods from. This is part of how JavaScript implements inheritance.

When you try to access a property or method on an object, JavaScript first looks at the object itself. If it doesn’t find it there, it looks up the prototype chain to see if the property exists in its prototype, and keeps going up until it either finds the property or reaches the end of the chain (null).

This allows objects to share common behavior without duplicating code.

#### **Real-life use cases**

- Sharing methods among many objects without recreating them each time.

- Implementing inheritance and extending objects with shared behavior.

- Creating custom objects that build upon built-in types like arrays or functions.

- Understanding how JavaScript’s classes work under the hood (they use prototypes).

#### **Examples**

Example 1 – Basic prototype chain

```js
const animal = {
  speak() {
    console.log("Animal sound");
  },
};

const dog = Object.create(animal);
dog.bark = function () {
  console.log("Woof!");
};

dog.speak(); // "Animal sound" (inherited from prototype)
dog.bark(); // "Woof!" (own method)
```

Example 2 – Checking prototype

```js
console.log(Object.getPrototypeOf(dog) === animal); // true
```

Example 3 – Using constructor function and prototype

```js
function Person(name) {
  this.name = name;
}

Person.prototype.sayHi = function () {
  console.log(`Hi, I'm ${this.name}`);
};

const alice = new Person("Alice");
alice.sayHi(); // "Hi, I'm Alice"
```

Example 4 – Overriding inherited method

```js
const cat = Object.create(animal);
cat.speak = function () {
  console.log("Meow!");
};

cat.speak(); // "Meow!" (overrides prototype method)
```

### **3.6 Prototypal Inheritance**

#### **Explanation**

Prototypal inheritance is a feature in JavaScript where objects inherit properties and methods directly from other objects, instead of classes like in some other languages.

In JavaScript, every object has a prototype object. When you access a property or method on an object, if it’s not found on that object, JavaScript looks up the prototype chain to find it.

This allows one object to inherit behavior from another, enabling code reuse and creating relationships between objects.

#### **Real-life use cases**

- Creating new objects based on existing ones with shared behavior.

- Extending functionality of built-in objects or custom objects.

- Implementing inheritance without classes (especially before ES6 classes existed).

- Sharing methods and properties efficiently among many instances.

#### **Examples**

Example 1 – Creating an object that inherits from another

```js
const person = {
  greet() {
    console.log(`Hello, I'm ${this.name}`);
  },
};

const student = Object.create(person);
student.name = "Kevin";
student.study = function () {
  console.log("Studying...");
};

student.greet(); // Hello, I'm Kevin
student.study(); // Studying...
```

Example 2 – Setting prototype with constructor functions

```js
function Animal(name) {
  this.name = name;
}

Animal.prototype.speak = function () {
  console.log(`${this.name} makes a sound`);
};

function Dog(name) {
  Animal.call(this, name);
}

Dog.prototype = Object.create(Animal.prototype);
Dog.prototype.constructor = Dog;

Dog.prototype.bark = function () {
  console.log(`${this.name} barks`);
};

const dog = new Dog("Buddy");
dog.speak(); // Buddy makes a sound
dog.bark(); // Buddy barks
```

Example 3 – Using ES6 classes (syntactic sugar for prototypal inheritance)

```js
class Person {
  constructor(name) {
    this.name = name;
  }
  greet() {
    console.log(`Hello, I'm ${this.name}`);
  }
}

class Student extends Person {
  study() {
    console.log("Studying...");
  }
}

const student = new Student("Maria");
student.greet(); // Hello, I'm Maria
student.study(); // Studying...
```

### **3.7 Classes & Inheritance**

#### **Explanation**

JavaScript classes are a cleaner, more modern way to create objects and set up inheritance.
They are actually syntactic sugar over the older prototype-based inheritance model — meaning they make it easier to write and read, but behind the scenes, they still use prototypes.

With inheritance, you can create a child class that automatically gets all the properties and methods of a parent class, and you can also add or override methods for custom behavior.

#### **Real-life use cases**

- Modeling related entities:
  For example, a User class and an Admin class where Admin inherits from User.

- Games:
  A generic Character class could have shared methods like attack(), and child classes like Warrior or Mage can have special attacks.

- UI components:
  A base Component class can define shared behavior, and child classes like Button or Form extend it with specific logic.

- APIs:
  A base ApiClient can have request logic, and child classes like UserApi or ProductApi can extend it.

#### **Examples**

Example 1 – Basic Class

```js
class Person {
  constructor(name) {
    this.name = name;
  }

  greet() {
    console.log(`Hello, I'm ${this.name}`);
  }
}

const kevin = new Person("Kevin");
kevin.greet(); // Hello, I'm Kevin
```

Example 2 – Inheritance with extends

```js
class Person {
  constructor(name) {
    this.name = name;
  }

  greet() {
    console.log(`Hello, I'm ${this.name}`);
  }
}

class Student extends Person {
  study() {
    console.log(`${this.name} is studying...`);
  }
}

const maria = new Student("Maria");
maria.greet(); // Hello, I'm Maria
maria.study(); // Maria is studying...
```

Example 3 – Overriding a Method

```js
class Person {
  constructor(name) {
    this.name = name;
  }

  greet() {
    console.log(`Hello, I'm ${this.name}`);
  }
}

class Teacher extends Person {
  greet() {
    console.log(`Good morning, class! I'm Professor ${this.name}`);
  }
}

const john = new Teacher("John");
john.greet(); // Good morning, class! I'm Professor John
```

Example 4 – Using super
super lets you call the parent class constructor or methods.

```js
class Animal {
  constructor(name) {
    this.name = name;
  }

  makeSound() {
    console.log("Some generic animal sound");
  }
}

class Dog extends Animal {
  constructor(name, breed) {
    super(name); // calls Animal's constructor
    this.breed = breed;
  }

  makeSound() {
    super.makeSound(); // calls parent method
    console.log("Woof! Woof!");
  }
}

const rex = new Dog("Rex", "German Shepherd");
rex.makeSound();
// Some generic animal sound
// Woof! Woof!
```

### **3.8 Dynamic Object Properties**

#### **Explanation**

Dynamic object properties in JavaScript let you define or access object keys using variables or expressions rather than fixed strings.

Normally, you write:

```js
const obj = { name: "Kevin" };
```

But with dynamic properties, you can do:

```js
const key = "name";
const obj = { [key]: "Kevin" };
```

Here, the [ ] around key mean:

> “Take the value of the variable key and use it as the property name.”

This is especially useful when:

- Property names are determined at runtime (e.g., user input, API data).

- You need computed keys (based on logic, concatenation, or expressions).

#### **Real-life use cases**

- Building objects from user input
  If a form has fields whose names you don’t know beforehand, you can store them dynamically.

- Mapping API data
  API responses may have unpredictable keys — dynamic properties let you map them easily.

- Creating property names from loops
  For example, "item1", "item2", "item3" generated automatically in a loop.

- Storing values in objects by computed criteria
  For instance, obj["score_" + playerId].

#### **Examples**

Example 1 – Using a variable as a key

```js
const propName = "age";
const person = {
  name: "Kevin",
  [propName]: 25,
};

console.log(person); // { name: "Kevin", age: 25 }
```

Example 2 – Computed property names in expressions

```js
const index = 1;
const obj = {
  ["item" + index]: "Apple",
  ["item" + (index + 1)]: "Banana",
};

console.log(obj); // { item1: "Apple", item2: "Banana" }
```

Example 3 – Creating object keys in a loop

```js
const scores = {};
for (let i = 1; i <= 3; i++) {
  scores[`player${i}`] = i * 10;
}

console.log(scores); // { player1: 10, player2: 20, player3: 30 }
```

Example 4 – From dynamic user input

```js
function addProperty(obj, key, value) {
  obj[key] = value;
}

const settings = {};
addProperty(settings, "theme", "dark");
addProperty(settings, "language", "English");

console.log(settings); // { theme: "dark", language: "English" }
```

Example 5 – API data mapping

```js
const apiData = { id: 101, name: "Laptop", price: 1200 };
const fieldToStore = "price";

const productInfo = {
  id: apiData.id,
  [fieldToStore]: apiData[fieldToStore],
};

console.log(productInfo); // { id: 101, price: 1200 }
```

## **4. Operators & Conditionals**

### **4.1 Types of Operators**

#### **Explanation**

In JavaScript, operators are special symbols (or keywords) that perform operations on values (called operands).

Think of them as the glue or tools that allow you to:

- Assign values
- Compare data
- Perform math
- Combine strings
- Control logic

JavaScript groups operators into different types:

1. Arithmetic Operators
   Perform mathematical operations.
   Examples:

- \+ → Addition
- \- → Subtraction
- \* → Multiplication
- / → Division
- % → Modulus (remainder)
- \*\* → Exponentiation

2. Assignment Operators
   Assign values to variables.
   Examples:

- = → Assign
- += → Add and assign
- \-= → Subtract and assign
- \*= → Multiply and assign
- /= → Divide and assign

3. Comparison Operators
   Compare values and return true or false.
   Examples:

- == → Equal (loose comparison, converts types)
- === → Strict equal (no type conversion)
- != → Not equal (loose)
- !== → Strict not equal
- < , > , <= , >= → Less/greater comparisons

4. Logical Operators
   Combine or invert boolean values.
   Examples:

- && → AND (true if both are true)
- || → OR (true if at least one is true)
- ! → NOT (inverts boolean)

5. String Operators

- \- → Concatenate strings
- += → Append string

6. Unary Operators
   Work with a single operand.
   Examples:

- typeof → Get data type
- ! → Logical NOT
- ++ → Increment
- \-- → Decrement

7. Ternary Operator
   A compact form of if...else:

```js
condition ? valueIfTrue : valueIfFalse;
```

8. Spread / Rest Operators

- Spread (...) → Expand arrays/objects
- Rest (...) → Collect remaining elements into an array

#### **Real-life use cases**

- Arithmetic operators → Calculating totals, discounts, statistics.
- Assignment operators → Updating scores, counters, settings.
- Comparison operators → Validating user input or checking conditions.
- Logical operators → Combining multiple checks (e.g., login validation).
- String operators → Formatting messages, building templates.
- Unary operators → Type checking, simple increments/decrements.
- Ternary operator → Choosing a value in one line (like choosing light/dark theme).
- Spread/rest → Merging arrays, cloning objects, destructuring arguments.

#### **Examples**

Example 1 – Arithmetic

```js
let price = 100;
let tax = 20;
let total = price + tax;
console.log(total); // 120
```

Example 2 – Assignment

```js
let count = 5;
count += 3;
console.log(count); // 8
```

Example 3 – Comparison

```js
console.log(5 == "5"); // true  (loose)
console.log(5 === "5"); // false (strict)
```

Example 4 – Logical

```js
let isMember = true;
let hasCoupon = false;
console.log(isMember || hasCoupon); // true
```

Example 5 – String concatenation

```js
let first = "Hello";
let last = "World";
console.log(first + " " + last); // Hello World
```

Example 6 – Unary

```js
let num = 5;
num++;
console.log(num); // 6
```

Example 7 – Ternary

```js
let age = 20;
let status = age >= 18 ? "Adult" : "Minor";
console.log(status); // Adult
```

Example 8 – Spread

```js
const arr1 = [1, 2];
const arr2 = [3, 4];
const combined = [...arr1, ...arr2];
console.log(combined); // [1, 2, 3, 4]
```

### **4.2 Conditionals**

#### **Explanation**

Conditionals in JavaScript allow you to execute different pieces of code depending on whether certain conditions are true or false.

They are like decision-making checkpoints in your program:

> “If this happens, do this. Otherwise, do that.”

JavaScript provides several ways to write conditionals:

1. if Statement
   Executes code if a condition is true.

```js
if (condition) {
  // Code runs if condition is true
}
```

2. if...else Statement
   Adds an alternative block of code when the condition is false.

```js
if (condition) {
  // Runs if condition is true
} else {
  // Runs if condition is false
}
```

3. if...else if...else Chain
   Allows multiple conditions in sequence.

```js
if (condition1) {
  // Runs if condition1 is true
} else if (condition2) {
  // Runs if condition2 is true
} else {
  // Runs if none are true
}
```

4. switch Statement
   Good for checking one value against multiple possible matches.

```js
switch (expression) {
  case value1:
    // Runs if expression === value1
    break;
  case value2:
    // Runs if expression === value2
    break;
  default:
  // Runs if no match is found
}
```

5. Ternary Operator
   A compact if...else for assigning values.

```js
condition ? valueIfTrue : valueIfFalse;
```

#### **Real-life use cases**

- Validating form inputs (check if a field is empty before submission).

- User authentication (check if user is logged in before showing private content).

- Feature toggles (enable or disable certain functionality based on a flag).

- Game development (react differently if player health is above or below a threshold).

- Dynamic UI changes (switch themes or layouts based on screen size).

#### **Examples**

Example 1 – Basic if

```js
let temperature = 30;
if (temperature > 25) {
  console.log("It's hot outside!");
}
```

Example 2 – if...else

```js
let isLoggedIn = false;
if (isLoggedIn) {
  console.log("Welcome back!");
} else {
  console.log("Please log in.");
}
```

Example 3 – if...else if...else

```js
let score = 85;

if (score >= 90) {
  console.log("Grade: A");
} else if (score >= 75) {
  console.log("Grade: B");
} else {
  console.log("Grade: C");
}
```

Example 4 – switch

```js
let day = "Monday";

switch (day) {
  case "Monday":
    console.log("Start of the work week!");
    break;
  case "Friday":
    console.log("Almost weekend!");
    break;
  default:
    console.log("Midweek vibes");
}
```

Example 5 – Ternary

```js
let age = 17;
let status = age >= 18 ? "Adult" : "Minor";
console.log(status); // Minor
```

### **4.3 Loops**

#### **Explanation**

Loops in JavaScript let you repeat a block of code multiple times until a certain condition is met.

Instead of copying and pasting the same code over and over, loops let you run it automatically.

Think of it like:

> “Do this thing again and again... until I say stop.”

JavaScript has several loop types:

1. for Loop
   Runs code a fixed number of times.

```js
for (initialization; condition; increment) {
  // code to run
}
```

- initialization → Set starting point (like let i = 0).
- condition → Keeps loop running while true.
- increment → Changes the counter after each loop.

2. while Loop
   Repeats while the condition is true.

```js
while (condition) {
  // code to run
}
```

(Careful: if the condition never becomes false, you get an infinite loop.)

3. do...while Loop
   Runs the code at least once before checking the condition.

```js
do {
  // code to run
} while (condition);
```

4. for...of Loop
   Loops through iterable objects like arrays, strings, etc.

```js
for (let value of iterable) {
  // code to run
}
```

5. for...in Loop
   Loops through object keys (property names).

```js
for (let key in object) {
  // code to run
}
```

#### **Real-life use cases**

- Iterating over arrays (e.g., displaying a product list).

- Processing user input (e.g., checking each character in a string).

- Updating UI elements dynamically (e.g., applying a style to each item in a menu).

- Searching through data (e.g., finding a match in a dataset).

- Performing repetitive tasks (e.g., sending multiple requests in sequence).

#### **Examples**

Example 1 – for loop

```js
for (let i = 1; i <= 5; i++) {
  console.log(`Step ${i}`);
}
```

Example 2 – while loop

```js
let count = 3;
while (count > 0) {
  console.log(`Countdown: ${count}`);
  count--;
}
```

Example 3 – do...while loop

```js
let number = 0;
do {
  console.log(`Number is: ${number}`);
  number++;
} while (number < 3);
```

Example 4 – for...of loop

```js
let fruits = ["apple", "banana", "cherry"];
for (let fruit of fruits) {
  console.log(fruit);
}
```

Example 5 – for...in loop

```js
let person = { name: "Kevin", age: 25, country: "USA" };
for (let key in person) {
  console.log(`${key}: ${person[key]}`);
}
```

### **4.4 break & continue**

#### **Explanation**

- break and continue are control statements used inside loops to change how they behave.

- break immediately stops the entire loop and jumps out of it.

- continue skips the current iteration and moves to the next one without running the rest of the code inside the loop for that iteration.

These statements help you control the flow inside loops more precisely.

#### **Real-life use cases**

- Use break when you find what you are looking for in a loop and want to stop searching.

- Use continue to skip unwanted cases but keep looping through the rest.

- Useful in filtering, searching, or skipping invalid data inside loops.

#### **Examples**

Example 1 — Using break to stop a loop early:

```js
for (let i = 1; i <= 10; i++) {
  if (i === 5) {
    break; // Stop loop when i is 5
  }
  console.log(i);
}
// Output: 1 2 3 4
```

Example 2 — Using continue to skip an iteration:

```js
for (let i = 1; i <= 5; i++) {
  if (i === 3) {
    continue; // Skip when i is 3
  }
  console.log(i);
}
// Output: 1 2 4 5
```

Example 3 — Combining both:

```js
for (let i = 1; i <= 10; i++) {
  if (i % 2 === 0) {
    continue; // Skip even numbers
  }
  if (i > 7) {
    break; // Stop loop when i is greater than 7
  }
  console.log(i);
}
// Output: 1 3 5 7
```

### **4.5 Short-Circuit Evaluation**

#### **Explanation**

Short-circuit evaluation happens when JavaScript stops evaluating a logical expression as soon as the result is determined.

There are two main logical operators that use short-circuiting:

- && (AND): If the left side is false, JavaScript skips checking the right side because the whole expression will be false.

- || (OR): If the left side is true, JavaScript skips checking the right side because the whole expression will be true.

This behavior can be used to write shorter code or provide default values.

#### **Real-life use cases**

- Providing default values when a variable might be null or undefined.

- Running code only if a condition is true (like a guard clause).

- Preventing errors by checking if an object or property exists before accessing it.

- Making conditional assignments or calls more concise.

#### **Examples**

Example 1 — Using || to provide a default value:

```js
const userName = null;
const displayName = userName || "Guest";
console.log(displayName); // "Guest"
```

Example 2 — Using && to run code only if a condition is true:

```js
const isLoggedIn = true;
isLoggedIn && console.log("Welcome back!"); // Prints "Welcome back!"
```

Example 3 — Combining both:

```js
const config = null;
const settings = (config && config.settings) || "default settings";
console.log(settings); // "default settings"
```

### **4.6 alert, confirm, and prompt**

#### **Explanation**

alert, confirm, and prompt are built-in JavaScript functions that show dialog boxes to the user in the browser:

- alert(message): Shows a simple message with an OK button. It’s used to display information.

- confirm(message): Shows a message with OK and Cancel buttons. Returns true if OK is clicked, false if Cancel.

- prompt(message, default): Shows a message with a text input field and OK/Cancel buttons. Returns the text entered or null if Cancel.

These functions pause the script until the user interacts with the dialog.

#### **Real-life use cases**

- alert: Inform the user about important information or warnings.

- confirm: Ask the user to confirm actions like deleting data.

- prompt: Get simple input from the user like their name or age.

- Useful for quick debugging or simple user interactions without building custom UI.

#### **Examples**

Example 1 — Using alert:

```js
alert("Welcome to our website!");
```

Example 2 — Using confirm:

```js
const deleteConfirmed = confirm("Are you sure you want to delete this file?");
if (deleteConfirmed) {
  console.log("File deleted.");
} else {
  console.log("Action canceled.");
}
```

Example 3 — Using prompt:

```js
const name = prompt("What is your name?", "Guest");
console.log(`Hello, ${name}!`);
```

## **5. Error Handling**

### **5.1 Error Handling**

#### **Explanation**

Error handling in JavaScript is about anticipating and managing errors in your code so your program doesn’t crash unexpectedly.
An error can happen for many reasons — invalid data, network issues, missing files, etc.

JavaScript provides tools to handle these situations, mainly with try, catch, and finally.

- try: The code you think might throw an error goes here.

- catch: If an error happens in the try block, the code in catch will run, allowing you to react gracefully.

- finally: Runs after try/catch no matter what (error or no error) — often used for cleanup.

There are also runtime errors (like ReferenceError, TypeError) and custom errors you can create yourself.

#### **Real-life use cases**

- Handling network request failures in web apps.

- Preventing form submission if data is invalid.

- Providing friendly error messages to the user instead of showing raw JavaScript errors.

- Wrapping critical logic so an error in one place doesn’t crash the entire application.

#### **Examples**

Example 1 — Basic try/catch

```js
try {
  let result = riskyOperation(); // might throw an error
  console.log(result);
} catch (error) {
  console.log("Something went wrong:", error.message);
}
```

Example 2 — Using finally

```js
try {
  console.log("Starting process...");
  throw new Error("Unexpected failure");
} catch (error) {
  console.log("Error:", error.message);
} finally {
  console.log("Cleaning up...");
}
```

Example 3 — Custom error throwing

```js
function divide(a, b) {
  if (b === 0) {
    throw new Error("Cannot divide by zero");
  }
  return a / b;
}

try {
  console.log(divide(4, 0));
} catch (error) {
  console.log("Math error:", error.message);
}
```

### **5.2 try / catch**

#### **Explanation**

try and catch are JavaScript statements used together to handle errors gracefully.

- The code inside the try block is executed normally.

- If an error (exception) occurs in the try block, JavaScript stops executing it and jumps to the catch block.

- The catch block receives the error object and lets you handle or respond to the error instead of crashing the program.

This way, you can avoid unexpected crashes and provide meaningful feedback or fallback behavior.

#### **Real-life use cases**

- Handling errors when making network requests (e.g., API calls).

- Parsing JSON strings that might be invalid.

- Working with user input that might cause errors.

- Catching errors in complex calculations or file operations in Node.js.

#### **Examples**

Example 1 — Basic try/catch:

```js
try {
  const data = JSON.parse('{"name": "Kevin"}'); // valid JSON
  console.log(data.name);
} catch (error) {
  console.log("Invalid JSON:", error.message);
}
```

Example 2 — Catching a syntax error:

```js
try {
  eval('alert("Hello)'); // missing closing quote, throws error
} catch (error) {
  console.log("Eval failed:", error.message);
}
```

Example 3 — Handling a possible runtime error:

```js
function divide(a, b) {
  try {
    if (b === 0) {
      throw new Error("Cannot divide by zero");
    }
    return a / b;
  } catch (error) {
    return error.message;
  }
}

console.log(divide(10, 0)); // "Cannot divide by zero"
```

### **5.3 throw**

#### **Explanation**

The throw statement in JavaScript is used to create and send an error manually.
It allows you to “throw” (raise) your own custom errors when something unexpected happens in your code.

When you use throw, the normal flow stops immediately, and JavaScript looks for a nearby try...catch block to handle the error.
If no catch is found, the program will crash and show an error message.

#### **Real-life use cases**

- Validating input and throwing errors if data is invalid.

- Stopping code execution when a required condition isn’t met.

- Creating meaningful error messages in libraries or APIs.

- Handling exceptional cases where continuing would cause bugs.

#### **Examples**

Example 1 — Throwing a simple error:

```js
function checkAge(age) {
  if (age < 18) {
    throw new Error("You must be at least 18 years old.");
  }
  return "Access granted";
}

try {
  console.log(checkAge(15));
} catch (error) {
  console.log("Error:", error.message);
}
```

Example 2 — Throwing a custom error object:

```js
class ValidationError extends Error {
  constructor(message) {
    super(message);
    this.name = "ValidationError";
  }
}

function validateEmail(email) {
  if (!email.includes("@")) {
    throw new ValidationError("Invalid email address.");
  }
  return "Email is valid";
}

try {
  validateEmail("invalidEmail.com");
} catch (error) {
  console.log(error.name + ": " + error.message);
}
```

Example 3 — Throwing different types of errors:

```js
throw "This is a string error"; // Throws a string (not recommended)
throw 404; // Throws a number (not recommended)
throw new Error("Something went wrong"); // Recommended way
```

## **6. Special Objects & Methods**

### **6.1 console Object**

#### **Explanation**

The console object in JavaScript is a built-in tool that lets you log information, debug your code, and measure performance directly in your browser’s developer console or terminal (if you’re using Node.js).

It’s not part of the JavaScript language specification itself — it’s provided by the environment where JavaScript runs (browser or Node.js).

The most common methods are:

- console.log() → Shows general messages.

- console.error() → Displays error messages (often in red).

- console.warn() → Shows warnings (often in yellow).

- console.table() → Displays tabular data in a table format.

- console.time() & console.timeEnd() → Measure how long code takes to run.

- console.clear() → Clears the console output.

#### **Real-life use cases**

- Debugging: Printing variables and values while developing to understand how your code is behaving.

- Error tracking: Logging errors with console.error to quickly find problems.

- Performance testing: Measuring how long a function or loop takes to run.

- Data visualization: Using console.table to easily see arrays or objects in a readable table.

Temporary logging: Adding logs while developing, then removing them before production.

#### **Examples**

Example 1 – Basic logging

```js
console.log("Hello, World!");
console.log("User age:", 25);
```

Example 2 – Errors and warnings

```js
console.error("This is an error message.");
console.warn("This is a warning.");
```

Example 3 – Displaying data in a table

```js
const users = [
  { name: "Kevin", age: 25 },
  { name: "Maria", age: 30 },
];

console.table(users);
```

Example 4 – Measuring execution time

```js
console.time("loopTime");

for (let i = 0; i < 1000000; i++) {
  /* some work */
}

console.timeEnd("loopTime");
```

Example 5 – Clearing the console

```js
console.clear();
console.log("Console is now cleared.");
```

### **6.2 Date Object**

#### **Explanation**

The Date object in JavaScript is used to work with dates and times.
It lets you create, read, update, and format date/time values.

Some important facts:

- Dates in JavaScript start counting from January 1, 1970 (the "Unix Epoch") in UTC.

- Months are zero-based (January = 0, February = 1, etc.).

- The Date object works with both local time and UTC.

Common ways to create a date:

```js
new Date(); // current date and time
new Date("2025-08-13"); // from a date string
new Date(2025, 7, 13, 15, 30); // year, month(0-11), day, hours, minutes
```

Common methods:

- Getters: .getFullYear(), .getMonth(), .getDate(), .getDay(), .getHours(), .getMinutes(), .getSeconds().

- Setters: .setFullYear(), .setMonth(), .setDate(), etc.

- Formatting: .toDateString(), .toISOString(), .toLocaleString().

#### **Real-life use cases**

- Showing the current date and time (in apps, websites, and clocks).

- Scheduling events (like reminders, meetings, or countdowns).

- Calculating time differences (age, delivery ETA, countdown timers).

- Formatting dates for the user’s region (different countries have different formats).

- Timestamps for logging and tracking events.

#### **Examples**

Example 1 – Current date and time

```js
const now = new Date();
console.log(now); // Full date and time
```

Example 2 – Creating a specific date

```js
const birthday = new Date(1998, 0, 15); // January 15, 1998
console.log(birthday.toDateString()); // Thu Jan 15 1998
```

Example 3 – Getting date parts

```js
const today = new Date();
console.log(today.getFullYear()); // 2025
console.log(today.getMonth()); // 7 (August)
console.log(today.getDate()); // 13
console.log(today.getDay()); // 3 (Wednesday)
```

Example 4 – Formatting

```js
const date = new Date();
console.log(date.toLocaleDateString()); // Format depends on your region
console.log(date.toISOString()); // 2025-08-13T...
```

Example 5 – Time difference

```js
const start = new Date("2025-08-01");
const end = new Date("2025-08-13");
const diffMs = end - start; // milliseconds
const diffDays = diffMs / (1000 * 60 * 60 * 24);
console.log(`Difference: ${diffDays} days`); // Difference: 12 days
```

### **6.3 Math Object**

#### **Explanation**

The Math object in JavaScript is a built-in utility that contains:

- Mathematical constants (like Math.PI for π).

- Functions for calculations (square root, power, trigonometry, rounding, random numbers, etc.).

Important notes:

- Math is not a constructor — you don’t create it with new Math().

- All properties and methods are static — you call them directly like Math.sqrt(25), not from an instance.

#### **Real-life use cases**

- Games: generating random positions, speeds, or scores.

- Finance: rounding currency values to two decimals.

- Data processing: scaling or normalizing numbers.

- Graphics & animations: calculating angles, distances, and positions.

- Probability simulations: dice rolls, card shuffling, etc.

#### **Examples**

Example 1 – Basic Math constants & functions

```js
console.log(Math.PI); // 3.141592653589793 (π)
console.log(Math.E); // 2.718281828459045 (Euler's number)
console.log(Math.sqrt(16)); // 4
console.log(Math.pow(2, 3)); // 8 (2³)
```

Example 2 – Rounding numbers

```js
console.log(Math.round(4.6)); // 5 (nearest integer)
console.log(Math.floor(4.9)); // 4 (always down)
console.log(Math.ceil(4.1)); // 5 (always up)
```

Example 3 – Random numbers

```js
// Random number between 0 and 1
console.log(Math.random());

// Random integer between 1 and 10
console.log(Math.floor(Math.random() * 10) + 1);
```

Example 4 – Absolute value and sign

```js
console.log(Math.abs(-5)); // 5
console.log(Math.sign(-10)); // -1 (negative)
console.log(Math.sign(0)); // 0
console.log(Math.sign(10)); // 1 (positive)
```

Example 5 – Trigonometry

```js
console.log(Math.sin(Math.PI / 2)); // 1  (sin 90°)
console.log(Math.cos(Math.PI)); // -1 (cos 180°)
```

### **6.4 Regular Expressions**

#### **Explanation**

Regular Expressions (RegEx) are patterns used to match, search, and manipulate text in strings.
They are like mini-programming languages inside JavaScript that let you define a set of rules to look for specific patterns in text — for example, validating an email, finding numbers, replacing certain words, or checking formats.

In JavaScript, a regular expression can be created in two ways:

Literal syntax:

```js
const regex = /pattern/flags;
```

Constructor function:

```js
const regex = /pattern/flags;
```

Common Flags:

- g → global (find all matches)

- i → case-insensitive

- m → multiline

Common Patterns:

- \d → digit (0–9)

- \w → word character (letters, numbers, underscore)

- \s → whitespace

- . → any character (except newline)

- \+ → one or more times

- \* → zero or more times

- ? → zero or one time

- {n} → exactly n times

- {n,} → at least n times

- {n,m} → between n and m times

- ^ → start of string

- $ → end of string

#### **Real-life use cases**

- Form validation (emails, phone numbers, passwords)

- Searching text (find all occurrences of a word)

- Replacing certain words or characters

- Extracting information (dates, hashtags, IDs)

- Checking formats (credit card numbers, postal codes)

#### **Examples**

Example 1 – Testing a string

```js
const regex = /hello/i; // case-insensitive
console.log(regex.test("Hello World")); // true
```

Example 2 – Matching all numbers

```js
const text = "I have 2 cats and 3 dogs.";
const numbers = text.match(/\d+/g);
console.log(numbers); // ["2", "3"]
```

Example 3 – Replacing text

```js
const sentence = "I love cats. Cats are great!";
const result = sentence.replace(/cats/gi, "dogs");
console.log(result); // "I love dogs. Dogs are great!"
```

Example 4 – Validating an email

```js
const emailRegex = /^[\w.-]+@[\w.-]+\.\w+$/;
console.log(emailRegex.test("user@example.com")); // true
console.log(emailRegex.test("invalid-email")); // false
```

Example 5 – Extracting hashtags

```js
const post = "Loving the weather! #sunny #beach";
const hashtags = post.match(/#\w+/g);
console.log(hashtags); // ["#sunny", "#beach"]
```

## **7. Advanced Functions**

### **7.1 this Keyword**

#### **Explanation**

The this keyword in JavaScript refers to the context in which a function is called. Its value depends on how the function is invoked, not where it is defined.

Key points:

- In a method of an object, this refers to the object itself.

- In a regular function, this refers to the global object (window in browsers) or undefined in strict mode.

- In an arrow function, this takes its value from the surrounding lexical scope, not from where it’s called.

- In a class constructor, this refers to the instance being created.

Real-life use cases

#### **Real-life use cases**

- Accessing object properties within methods.

- Sharing behavior across multiple instances in classes.

- Using arrow functions in callbacks to preserve the outer this.

#### **Examples**

Example 1 – Object method

```js
const person = {
  name: "Kevin",
  greet() {
    console.log(`Hello, I'm ${this.name}`);
  },
};

person.greet(); // Hello, I'm Kevin
```

Example 2 – Regular function vs strict mode

```js
function showThis() {
  console.log(this);
}

showThis(); // window (in browser) or undefined in strict mode
```

Example 3 – Arrow function using outer this

```js
const timer = {
  seconds: 0,
  start() {
    setInterval(() => {
      this.seconds++;
      console.log(this.seconds);
    }, 1000);
  },
};

timer.start(); // increments seconds every second
```

### **7.2 call, apply, bind**

#### **Explanation**

The call, apply, and bind methods are used to control the value of this inside a function.

call() – calls a function with a given this value and arguments listed individually.

apply() – calls a function with a given this value and arguments provided as an array.

bind() – creates a new function with this permanently set to a specific value.

These methods are helpful when you want a function to use a specific object as its context, regardless of how or where it is called.

#### **Real-life use cases**

Borrowing methods from one object for another object.

Using array-like objects (like arguments) with array methods.

Preserving this in callbacks or event handlers.

#### **Examples**

Example 1 – call()

```js
function greet(greeting) {
  console.log(`${greeting}, I'm ${this.name}`);
}

const person = { name: "Kevin" };

greet.call(person, "Hello"); // Hello, I'm Kevin
```

Example 2 – apply()

```js
function introduce(age, job) {
  console.log(`I'm ${this.name}, ${age} years old, and I work as a ${job}.`);
}

const person = { name: "Maria" };

introduce.apply(person, [28, "developer"]);
// I'm Maria, 28 years old, and I work as a developer.
```

Example 3 – bind()

```js
const student = { name: "John" };

function sayName() {
  console.log(`My name is ${this.name}`);
}

const boundSayName = sayName.bind(student);
boundSayName(); // My name is John
```

### **7.3 JSON**

#### **Explanation**

JSON stands for JavaScript Object Notation. It’s a format to store and exchange data between systems (like servers and browsers).

- In JavaScript, you can convert objects to JSON strings and parse JSON strings back to objects.

- This is useful because JSON is text-based, easy to send over networks, and widely supported.

Key points:

- JSON.stringify(obj) → converts a JavaScript object to a JSON string.

- JSON.parse(jsonString) → converts a JSON string back to a JavaScript object.

- JSON can only store data, not undefined, functions or methods.

#### **Real-life use cases**

- API communication → When your JavaScript code sends/receives data from a server.

- Saving settings → Storing user preferences in a file or localStorage.

- Data export/import → Sending data from one system to another.

- Configuration files → Many tools use .json files to store settings (e.g., package.json in Node.js).

#### **Examples**

Example 1 – Converting object to JSON

```js
const user = { name: "Kevin", age: 25 };
const jsonString = JSON.stringify(user);
console.log(jsonString); // '{"name":"Kevin","age":25}'
```

Example 2 – Parsing JSON to object

```js
const data = '{"name":"Maria","age":30}';
const userObj = JSON.parse(data);
console.log(userObj.name); // "Maria"
```

Example 3 – Nested data

```js
const company = {
  name: "Tech Corp",
  employees: [
    { name: "John", role: "Developer" },
    { name: "Sara", role: "Designer" },
  ],
};
console.log(JSON.stringify(company));
// '{"name":"Tech Corp","employees":[{"name":"John","role":"Developer"},{"name":"Sara","role":"Designer"}]}'
```

Example 4 – Sending JSON in fetch

```js
fetch("https://api.example.com/users", {
  method: "POST",
  headers: { "Content-Type": "application/json" },
  body: JSON.stringify({ name: "John", age: 28 }),
})
  .then((response) => response.json())
  .then((data) => console.log(data));
```

## **8. Modules & Logic Projects**

### **8.1 ES Modules (import / export)**

#### **Explanation**

In JavaScript, ES Modules let you split your code into smaller, reusable files.
Instead of putting everything in one giant script, you can export functions, variables, or classes from one file and import them into another.

It’s necessary to add type="module" to the \<script> tag that loads the main JavaScript file — the file from which the app will start importing/exporting other modules.

👉 Think of it like:

- Export = "I want to share this code with other files."

- Import = "I want to use code that was shared from another file."

This keeps code organized, easier to maintain, and reusable.

#### **Real-life use cases**

- Breaking a big project into smaller modules (e.g., utils.js, api.js, auth.js).

- Sharing reusable functions (e.g., formatDate, calculateTax).

- Organizing code for larger apps (React, Vue, Node.js all use modules).

- Keeping logic separated by responsibility (e.g., one file for math functions, another for DOM manipulation).

#### **Examples**

Example 1 – Exporting functions from a file

📂 math.js

```js
Example 1 – Exporting functions from a file

📂 math.js
```

📂 main.js

```js
import { add, subtract } from "./math.js";

console.log(add(5, 3)); // 8
console.log(subtract(10, 4)); // 6
```

Example 2 – Exporting a single default

📂 logger.js

```js
export default function log(message) {
  console.log("Log:", message);
}
```

📂 app.js

```js
import log from "./logger.js";

log("Hello Modules!"); // Log: Hello Modules!
```

Example 3 – Renaming imports

📂 utils.js

```js
export function greet(name) {
  return `Hello, ${name}!`;
}
```

📂 main.js

```js
import { greet as sayHello } from "./utils.js";

console.log(sayHello("Kevin")); // Hello, Kevin!
```

Example 4 – Import everything

📂 tools.js

```js
export function hammer() {
  return "🔨 Hammering...";
}

export function saw() {
  return "🪚 Sawing...";
}
```

📂 workshop.js

```js
📂 workshop.js
```

With ES Modules, your code becomes like a LEGO set: you build small pieces separately and then connect them together.

### **8.2 Ways to export/import in ES Modules**

#### **Explanation**

There are three main ways to export and import in ES Modules: named exports, default exports, and a combination of both.

- Named Exports

  - You can export multiple values from a module.

  - Importing must use the same names (or rename them using as).

- Default Export

  - A module can have only one default export.

  - Importing can use any name you choose.

- Combining Named + Default

  - You can have one default export and multiple named exports in the same file.

#### **Real-life use cases**

- Named exports:

  - When a file has multiple functions, constants, or utilities.

  - Example: utils.js with formatDate, calculateTax, validateEmail.

- Default export:

  - When a file mainly exports one main thing, like a class, component, or main function.

  - Example: User.js exporting a User class.

- Combining both:

  - When you want to export a main thing plus some helper functions.

  - Example: math.js exports a default calculate function plus helpers like add and subtract.

#### **Examples**

Example 1 – Named exports

📂 math.js

```js
export function add(a, b) {
  return a + b;
}
export function subtract(a, b) {
  return a - b;
}
```

📂 main.js

```js
import { add, subtract } from "./math.js";

console.log(add(2, 3)); // 5
console.log(subtract(5, 2)); // 3
```

Example 2 – Default export

📂 logger.js

```js
export default function log(message) {
  console.log(message);
}
```

📂 app.js

```js
import myLogger from "./logger.js"; // name can be anything

myLogger("Hello world!"); // Hello world!
```

Example 3 – Renaming named imports

📂 math.js

```js
export function add(a, b) {
  return a + b;
}
export function subtract(a, b) {
  return a - b;
}
```

📂 main.js

```js
import { add as sum, subtract as minus } from "./math.js";

console.log(sum(2, 3)); // 5
console.log(minus(5, 2)); // 3
```

Example 4 – Combining named + default exports

📂 utils.js

```js
export default function farewell(name) {
  return `Goodbye, ${name}!`;
}

export function greet(name) {
  return `Hello, ${name}!`;
}
```

📂 main.js

```js
import sayGoodbye, { greet } from "./utils.js";

console.log(greet("Kevin")); // Hello, Kevin!
console.log(sayGoodbye("Kevin")); // Goodbye, Kevin!
```

## **9. Timers & Asynchronous JavaScript**

### **9.1 Timers (setTimeout, setInterval)**

#### **Explanation**

In JavaScript, timers let you schedule code to run in the future or repeatedly over time.
There are two main timer functions:

- setTimeout(callback, delay)
  Runs the callback function once after the given delay (in milliseconds).

- setInterval(callback, delay)
  Runs the callback function repeatedly, every delay milliseconds, until you stop it.

Both return an ID (a number) that you can use with clearTimeout() or clearInterval() to stop them.

#### **Real-life use cases**

- Showing a notification message and hiding it after a few seconds.

- Creating a simple clock or countdown.

- Running repeated tasks, like auto-saving data every few minutes.

- Delaying an action, e.g., waiting before retrying a failed request.

- Animations (though now requestAnimationFrame is preferred).

#### **Examples**

Example 1 – setTimeout (run once after delay)

```js
console.log("Start");

setTimeout(() => {
  console.log("This runs after 2 seconds");
}, 2000);

console.log("End");
// Output order:
// Start
// End
// This runs after 2 seconds
```

Example 2 – setInterval (run repeatedly)

```js
let count = 0;

const intervalId = setInterval(() => {
  count++;
  console.log(`Count: ${count}`);

  if (count === 5) {
    clearInterval(intervalId); // stop after 5 times
    console.log("Stopped!");
  }
}, 1000);

// Prints:
// Count: 1
// Count: 2
// ...
// Count: 5
// Stopped!
```

Example 3 – clearTimeout (cancel before execution)

```js
const timeoutId = setTimeout(() => {
  console.log("You won't see this!");
}, 3000);

clearTimeout(timeoutId); // cancels the timeout
```

### **9.2 Asynchronous JavaScript & Event Loop**

#### **Explanation**

JavaScript is single-threaded → it can only do one thing at a time.
But… JavaScript can handle multiple tasks without blocking, thanks to asynchronous code and the event loop.

Key ideas:

- Synchronous code runs line by line (blocking).

- Asynchronous code runs later, without blocking the main thread.

- The event loop is the mechanism that decides when asynchronous tasks (like timers, network requests, or events) should run after the synchronous code finishes.

How it works:

- JavaScript executes all synchronous code first (call stack).

- Async tasks (like setTimeout, HTTP requests, DOM events) are sent to the Web APIs (provided by the browser).

- When they are ready, they go into the callback queue (or microtask queue for Promises).

- The event loop checks: if the call stack is empty → it pushes callbacks/microtasks into it.

#### **Real-life use cases**

- Loading data from an API without freezing the UI.

- Running timers (delays, intervals).

- Handling user events (clicks, keypresses) without blocking other tasks.

- Running animations while waiting for something else in the background.

- Writing responsive, smooth apps that don’t "freeze" during long operations.

#### **Examples**

Example 1 – Synchronous vs Asynchronous

```js
console.log("Start");

setTimeout(() => {
  console.log("This is async");
}, 2000);

console.log("End");

// Output:
// Start
// End
// This is async
```

The async task (setTimeout) runs after synchronous code finishes.

Example 2 – Event Loop with API call (simulation)

```js
console.log("1: Start");

setTimeout(() => {
  console.log("2: Timeout done");
}, 0);

Promise.resolve().then(() => {
  console.log("3: Promise resolved");
});

console.log("4: End");

// Output order:
// 1: Start
// 4: End
// 3: Promise resolved   <-- microtask (Promises run before timeouts)
// 2: Timeout done
```

👉 Promises (microtasks) run before timers (macrotasks).

Example 3 – Without async, it blocks

```js
console.log("Start");

for (let i = 0; i < 1e9; i++) {} // heavy loop

console.log("End");
// The browser is frozen until the loop finishes
```

### **9.3 Callbacks**

#### **Explanation**

A callback is a function passed as an argument to another function, which is then executed later.
It’s one of the first ways JavaScript handled asynchronous code before Promises and async/await.

👉 Key points:

- Callbacks let us say: “Do this first, then call this function when you’re done.”

- They are commonly used with timers, event listeners, or async tasks (like reading files, API requests).

- Downside: when callbacks are nested too much → you get “callback hell” (very messy code).

#### **Real-life use cases**

- Running code after a delay (setTimeout).

- Handling user events (clicks, inputs, keypresses).

- Making API requests and then doing something with the response.

- Animations: run step 2 only when step 1 finishes.

#### **Examples**

Example 1 – Basic callback

```js
function greet(name, callback) {
  console.log(`Hello, ${name}!`);
  callback(); // Run the callback
}

function sayBye() {
  console.log("Goodbye!");
}

greet("Kevin", sayBye);
// Output:
// Hello, Kevin!
// Goodbye!
```

Example 2 – Callback with setTimeout

```js
console.log("Start");

setTimeout(() => {
  console.log("This runs after 2 seconds");
}, 2000);

console.log("End");

// Output:
// Start
// End
// This runs after 2 seconds
```

Example 3 – Event listener with callback

```js
document.body.addEventListener("click", function () {
  console.log("Body was clicked!");
});
```

Example 4 – Callback hell (bad practice)

```js
setTimeout(() => {
  console.log("Step 1");
  setTimeout(() => {
    console.log("Step 2");
    setTimeout(() => {
      console.log("Step 3");
    }, 1000);
  }, 1000);
}, 1000);

// Output (each step 1 second apart):
// Step 1
// Step 2
// Step 3
```

### **9.4 Promises**

#### **Explanation**

A Promise in JavaScript is an object that represents the result of an asynchronous operation — it can either:

- ✅ Fulfilled (resolved) → the async task finished successfully.

- ❌ Rejected → the async task failed (an error happened).

- ⏳ Pending → still waiting for the result.

A Promise allows you to write cleaner asynchronous code compared to callbacks, avoiding “callback hell”.

👉 Syntax:

- .then() → runs when the promise is resolved.

- .catch() → runs when the promise is rejected (error).

- .finally() → runs always, no matter what.

#### **Real-life use cases**

- Fetching data from an API (e.g., get user info).

- Reading files in Node.js.

- Waiting for a timer or animation to finish.

- Database queries in the backend.

#### **Examples**

Example 1 – Creating a Promise

```js
const myPromise = new Promise((resolve, reject) => {
  let success = true; // try changing to false

  if (success) {
    resolve("The task was successful!");
  } else {
    reject("Something went wrong...");
  }
});

myPromise
  .then((message) => console.log(message)) // success
  .catch((error) => console.error(error)) // failure
  .finally(() => console.log("Done!"));
```

Example 2 – Promise with setTimeout

```js
function wait(ms) {
  return new Promise((resolve) => {
    setTimeout(() => resolve(`Waited ${ms}ms`), ms);
  });
}

wait(2000).then((msg) => console.log(msg));

// Output after 2s: "Waited 2000ms"
```

Example 3 – Fetch API with Promises

```js
fetch("https://jsonplaceholder.typicode.com/posts/1")
  .then((response) => response.json()) // convert to JSON
  .then((data) => console.log(data)) // handle data
  .catch((error) => console.error("Error:", error));
```

Example 4 – Promise.all

```js
const p1 = Promise.resolve("First");
const p2 = new Promise((resolve) => setTimeout(() => resolve("Second"), 1000));

Promise.all([p1, p2]).then((results) => console.log(results));

// Output after 1s: ["First", "Second"]
```

### **9.5 async / await**

#### **Explanation**

- async / await is syntactic sugar (a simpler way) to work with Promises in JavaScript.

- Instead of chaining .then() and .catch(), you can write code that looks synchronous but actually handles asynchronous tasks.

- async makes a function return a Promise.

- await pauses the execution of the function until the Promise resolves (or rejects).

It makes your code easier to read, write, and debug compared to long .then() chains.

#### **Real-life use cases**

- Fetching data from an API: Instead of .then() chains, you just await the response.

- Reading files asynchronously in Node.js.

- Waiting for multiple operations (like loading user data, posts, and comments) before continuing.

- Cleaner error handling with try...catch instead of .catch().

#### **Examples**

Example 1 – Basic async function

```js
async function greet() {
  return "Hello, world!";
}

greet().then((message) => console.log(message));
// Output: Hello, world!
```

- Even if you just return a string, an async function automatically wraps it in a Promise.

- That’s why we need .then() to get the value (unless we await inside another async function).

Example 2 – Using await

```js
function delayedMessage() {
  return new Promise((resolve) => {
    setTimeout(() => resolve("This took 2 seconds"), 2000);
  });
}

async function showMessage() {
  console.log("Waiting...");
  const msg = await delayedMessage(); // pauses until resolved
  console.log(msg);
}

showMessage();
// Output:
// Waiting...
// (after 2 seconds) This took 2 seconds
```

👉 await tells JavaScript: “Pause here until the Promise is done.”

Example 3 – Error handling with try...catch

```js
function getUserData() {
  return new Promise((_, reject) => {
    setTimeout(() => reject("User not found"), 1500);
  });
}

async function fetchUser() {
  try {
    const user = await getUserData();
    console.log(user);
  } catch (error) {
    console.log("Error:", error);
  }
}

fetchUser();
// Output (after 1.5s): Error: User not found
```

👉 try...catch replaces .catch() for cleaner error handling.

Example 4 – Multiple awaits

```js
function wait(ms) {
  return new Promise((resolve) => setTimeout(resolve, ms));
}

async function runSteps() {
  console.log("Step 1");
  await wait(1000);
  console.log("Step 2");
  await wait(1000);
  console.log("Step 3");
}

runSteps();
// Output with 1s pause between steps
```

### **9.6 Symbols**

#### **Explanation**

A Symbol is a primitive data type in JavaScript (like string, number, boolean, etc.).
It was introduced in ES6 (ES2015).

- Symbols are unique and immutable identifiers.

- Even if two Symbols have the same description, they are still different.

- They are often used as object keys when you want to avoid conflicts with other keys.

👉 Think of a Symbol as a secret key: nobody else can accidentally use the same one, because every Symbol is unique.

#### **Real-life use cases**

- Avoiding property name collisions

  - If different parts of your code (or third-party libraries) use objects, a Symbol ensures that property names don’t clash.

- Creating "hidden" object properties

  - Properties with Symbols are not shown in normal loops (for...in, Object.keys()), but they still exist.

- Defining special behaviors

  - JavaScript uses some built-in Symbols like Symbol.iterator to make objects iterable.

#### **Examples**

Example 1 – Creating Symbols

```js
const sym1 = Symbol("id");
const sym2 = Symbol("id");

console.log(sym1 === sym2); // false -> unique, even with same description
```

Example 2 – Using Symbols as object keys

```js
const id = Symbol("id");

const user = {
  name: "Alice",
  [id]: 123, // Symbol key
};

console.log(user.name); // Alice
console.log(user[id]); // 123
```

Example 3 – Hidden properties

```js
const secret = Symbol("secret");

const person = {
  name: "Bob",
  age: 25,
  [secret]: "This is hidden",
};

// Normal keys
console.log(Object.keys(person)); // ["name", "age"]

// Symbol keys
console.log(Object.getOwnPropertySymbols(person)); // [ Symbol(secret) ]
```

Example 4 – Built-in Symbols

```js
const numbers = [1, 2, 3];

console.log(typeof numbers[Symbol.iterator]);
// function -> Arrays are iterable because they have Symbol.iterator
```

## **10. Data Structures**

### **10.1 Sets**

#### **Explanation**

A Set in JavaScript is a special collection that stores unique values.
That means:

- No duplicates allowed.

- The values can be of any type: numbers, strings, objects, etc.

- Order matters: elements are stored in the order you insert them.

Key properties:

- new Set() → creates a set.

- .add(value) → adds a new value.

- .delete(value) → removes a value.

- .has(value) → checks if a value exists.

- .size → number of elements in the set.

- .clear() → removes all values.

- Sets are iterable → you can use for...of or spread ....

#### **Real-life use cases**

- Remove duplicates from an array

  - Very common: arrays may contain duplicates, but you only want unique values.

- Fast membership check

  - Sets are faster than arrays when you just want to know: "Does this value exist?".

- Store unique IDs

  - When you need to make sure the same ID (user, product, etc.) is not added twice.

- Track visited elements
  - In algorithms (like graphs, searches, crawling), Sets are used to track which elements were already visited.

#### **Examples**

Example 1: Basic usage

```js
const mySet = new Set();

mySet.add(1);
mySet.add(2);
mySet.add(2); // duplicate → ignored

console.log(mySet); // Set {1, 2}
console.log(mySet.has(1)); // true
console.log(mySet.size); // 2
```

Example 2: Remove duplicates from an array

```js
const numbers = [1, 2, 2, 3, 4, 4, 5];
const uniqueNumbers = [...new Set(numbers)];

console.log(uniqueNumbers); // [1, 2, 3, 4, 5]
```

Example 3: Iterating a Set

```js
const colors = new Set(["red", "green", "blue"]);

for (const color of colors) {
  console.log(color);
}
// red
// green
// blue
```

Example 4: Store objects

```js
const user1 = { id: 1 };
const user2 = { id: 2 };
const user3 = { id: 1 }; // different object in memory, even if id is the same

const users = new Set([user1, user2, user3]);

console.log(users.size); // 3
```

👉 Unlike arrays, Sets don’t check "deep equality".
user1 and user3 are two different objects in memory, so both are stored.

### **10.2 Maps**

#### **Explanation**

A Map in JavaScript is a special data structure that stores key-value pairs, just like objects.
But unlike objects:

- Keys can be of any type (not just strings or symbols).
  → You can use numbers, objects, even functions as keys.

- Maps remember the order in which keys were inserted.

- Maps have built-in methods like .set(), .get(), .has(), .delete(), .clear(), .size.

- They are more efficient than objects when working with lots of dynamic key-value pairs.

#### **Real-life use cases**

- Caching results: Store API results for a specific user or query.

- Tracking metadata: Use objects or DOM elements as keys.

- Frequency counting: Count how many times an item appears.

- Associating IDs with objects: Example, storing user sessions.

#### **Examples**

Example 1: Basic usage

```js
const map = new Map();

// Add key-value pairs
map.set("name", "Alice");
map.set("age", 25);
map.set(100, "one hundred"); // number as key
map.set(true, "Yes!"); // boolean as key

// Retrieve values
console.log(map.get("name")); // Alice
console.log(map.get(100)); // one hundred

// Check existence
console.log(map.has("age")); // true
```

Example 2: Objects as keys

```js
const user1 = { id: 1 };
const user2 = { id: 2 };

const userRoles = new Map();
userRoles.set(user1, "admin");
userRoles.set(user2, "editor");

console.log(userRoles.get(user1)); // admin
console.log(userRoles.get(user2)); // editor
```

Example 3: Iterating a Map

```js
const fruits = new Map([
  ["apple", 2],
  ["banana", 5],
  ["orange", 3],
]);

for (const [fruit, quantity] of fruits) {
  console.log(fruit, quantity);
}
// apple 2
// banana 5
// orange 3
```

Example 4: Frequency counter (real use case)

```js
const words = ["apple", "banana", "apple", "orange", "banana", "apple"];
const counter = new Map();

for (const word of words) {
  counter.set(word, (counter.get(word) || 0) + 1);
}

console.log(counter);
// Map(3) { 'apple' => 3, 'banana' => 2, 'orange' => 1 }
```

### **10.3 WeakSets & WeakMaps**

#### **Explanation**

- WeakSet: A collection of objects, where each object can only appear once. Unlike normal sets, the references are weak, which means if there are no other references to an object, it can be garbage collected.

- WeakMap: Similar to a Map, but the keys must be objects and they are weakly referenced, allowing garbage collection if the key object is no longer needed.

Key points:

- Cannot iterate over WeakSet or WeakMap (no for..of or .keys()/.values()), because they are designed for memory management, not enumeration.

- Useful when you want to associate data with objects without preventing them from being garbage collected.

#### **Real-life use cases**

- Storing metadata about DOM elements without preventing them from being removed.

- Caching information about objects temporarily.

- Tracking objects without creating memory leaks.

#### **Examples**

Example 1 – WeakSet

```js
let obj1 = { name: "Kevin" };
let obj2 = { name: "Maria" };

const weakSet = new WeakSet();
weakSet.add(obj1);
weakSet.add(obj2);

console.log(weakSet.has(obj1)); // true

obj1 = null; // obj1 can now be garbage collected
```

Example 2 – WeakMap

```js
let user = { id: 1 };

const weakMap = new WeakMap();
weakMap.set(user, "Logged in");

console.log(weakMap.get(user)); // "Logged in"

user = null; // user object can be garbage collected
```

### **10.4 Iterables & Iterators**

#### **Explanation**

- Iterable:
  An object is iterable if it can be looped over with for...of. Examples: arrays, strings, maps, sets.
  An iterable must have a method called Symbol.iterator that returns an iterator.

- Iterator:
  An object that defines a sequence and can return one value at a time.
  It has a method .next() that returns:

```js
{ value: <something>, done: <true|false> }

```

- value: the current item in the sequence.

- done: tells if the sequence is finished.

Basically:

- Iterable = something you can loop over.

- Iterator = the thing that actually does the stepping through items.

#### **Real-life use cases**

- Custom data structures:
  If you make your own collection (like a linked list), you can make it iterable so you can use for...of with it.

- Controlled iteration:
  Useful when you don’t want to return all data at once, but instead step through it (e.g., reading files line by line).

- Lazy evaluation:
  Instead of generating a big list, you generate values one by one only when needed (like streaming results from a server).

#### **Examples**

Example 1: Built-in iterable

```js
const arr = [10, 20, 30];

// Get the iterator manually
const iterator = arr[Symbol.iterator]();

console.log(iterator.next()); // { value: 10, done: false }
console.log(iterator.next()); // { value: 20, done: false }
console.log(iterator.next()); // { value: 30, done: false }
console.log(iterator.next()); // { value: undefined, done: true }
```

Example 2: Custom iterable object

```js
const myIterable = {
  data: [1, 2, 3],
  [Symbol.iterator]() {
    let index = 0;
    const data = this.data;

    return {
      next() {
        if (index < data.length) {
          return { value: data[index++], done: false };
        } else {
          return { value: undefined, done: true };
        }
      },
    };
  },
};

for (const num of myIterable) {
  console.log(num); // 1, 2, 3
}
```

Example 3: Lazy iteration

```js
function range(start, end) {
  return {
    [Symbol.iterator]() {
      let current = start;
      return {
        next() {
          if (current <= end) {
            return { value: current++, done: false };
          }
          return { done: true };
        },
      };
    },
  };
}

for (const num of range(1, 5)) {
  console.log(num); // 1, 2, 3, 4, 5
}
```

### **10.5 Generators**

#### **Explanation**

A generator is a special function in JavaScript that can pause and resume its execution.
You create one with function* (notice the *).

- Instead of returning values with return, it uses yield.

- Each time the generator is called with .next(), it runs until the next yield.

- It produces an iterator automatically, so you don’t need to manually write [Symbol.iterator].

👉 Generators are a shortcut for building iterators.

#### **Real-life use cases**

- Lazy sequences
  Instead of generating a huge list (e.g., 1 to 1,000,000), a generator produces numbers one by one only when needed.

- Controlling flow
  Generators can pause, wait for something, and then continue — useful in async programming patterns.

- Custom data streams
  Perfect for simulating infinite sequences (like random numbers, sensor data, etc.).

#### **Examples**

Example 1: Basic generator

```js
function* myGenerator() {
  yield 1;
  yield 2;
  yield 3;
}

const gen = myGenerator();

console.log(gen.next()); // { value: 1, done: false }
console.log(gen.next()); // { value: 2, done: false }
console.log(gen.next()); // { value: 3, done: false }
console.log(gen.next()); // { value: undefined, done: true }
```

Example 2: Loop with generator

```js
function* countUpTo(n) {
  for (let i = 1; i <= n; i++) {
    yield i;
  }
}

for (const num of countUpTo(5)) {
  console.log(num); // 1, 2, 3, 4, 5
}
```

Example 3: Infinite generator (lazy sequence)

```js
function* infiniteCounter() {
  let i = 0;
  while (true) {
    yield i++;
  }
}

const counter = infiniteCounter();

console.log(counter.next().value); // 0
console.log(counter.next().value); // 1
console.log(counter.next().value); // 2
// ... goes forever
```

Example 4: Passing values back

```js
function* greet() {
  const name = yield "What is your name?";
  yield `Hello, ${name}!`;
}

const gen = greet();
console.log(gen.next().value); // "What is your name?"
console.log(gen.next("Maria").value); // "Hello, Maria!"
```

➡️ You can even send values back into the generator!

✅ Key idea: Generators simplify creating custom iterators.
They let you write cleaner, pauseable code with yield.

### **10.6 Proxies**

#### **Explanation**

A Proxy in JavaScript is like a middleman (or guard) that sits in front of an object and intercepts operations on it (like reading, writing, deleting properties).

You create one with:

```js
const proxy = new Proxy(target, handler);
```

- target → the original object you want to protect or extend.

- handler → an object with “traps” (functions that intercept operations).

Think of traps as hooks:

- get → runs when reading a property

- set → runs when writing to a property

- deleteProperty → runs when deleting a property

- … and more.

#### **Real-life use cases**

- Validation → Check if values being set are valid.

- Default values → Return a fallback when a property doesn’t exist.

- Debugging / Logging → Track when properties are accessed or modified.

- Protection → Prevent deleting or changing certain properties.

- Dynamic properties → Create properties “on the fly” without storing them.

#### **Examples**

Example 1: Basic logging proxy

```js
const user = { name: "Kevin", age: 25 };

const proxy = new Proxy(user, {
  get(target, prop) {
    console.log(`Getting ${prop}`);
    return target[prop];
  },
  set(target, prop, value) {
    console.log(`Setting ${prop} = ${value}`);
    target[prop] = value;
    return true; // must return true
  },
});

console.log(proxy.name); // Logs: Getting name → "Kevin"
proxy.age = 30; // Logs: Setting age = 30
```

Example 2: Default values

```js
const data = { name: "Alice" };

const proxy = new Proxy(data, {
  get(target, prop) {
    return prop in target ? target[prop] : "Not Found";
  },
});

console.log(proxy.name); // Alice
console.log(proxy.age); // Not Found
```

Example 3: Validation

```js
const person = {};

const proxy = new Proxy(person, {
  set(target, prop, value) {
    if (prop === "age" && typeof value !== "number") {
      throw new Error("Age must be a number!");
    }
    target[prop] = value;
    return true;
  },
});

proxy.age = 25; // ✅ Works
// proxy.age = "hi"; // ❌ Error: Age must be a number!
```

Example 4: Read-only object

```js
const settings = { theme: "dark" };

const proxy = new Proxy(settings, {
  set() {
    console.log("You can't modify this object!");
    return false; // prevents setting
  },
});

proxy.theme = "light"; // Logs: You can't modify this object!
console.log(proxy.theme); // dark
```

✅ Key idea: Proxies give you superpowers to control how objects behave without touching the object itself.

## **11. DOM (Document Object Model)**

### **11.1 DOM Introduction**

#### **Explanation**

- DOM stands for Document Object Model.

- When a webpage loads, the browser takes the HTML and converts it into a tree-like structure made of nodes (objects).

- This structure is live — meaning JavaScript can read and change it dynamically.

- Each HTML element (like \<div>, \<p>, \<button>) becomes a node in the DOM tree.

👉 In short: The DOM is the bridge between HTML (structure) and JavaScript (logic).

#### **Real-life use cases**

- Changing the text of a button when clicked ("Send" → "Sending...").

- Adding new items to a shopping cart list without refreshing the page.

- Showing or hiding a modal window (pop-up).

- Changing styles dynamically (e.g., dark mode).

#### **Examples**

Example 1 — The HTML

```js
<!DOCTYPE html>
<html>
  <body>
    <h1 id="title">Hello World</h1>
    <button id="btn">Click me</button>

    <script>
      // We'll add JS here
    </script>
  </body>
</html>
```

Example 2 — Accessing the DOM

```js
const title = document.getElementById("title");
console.log(title); // <h1 id="title">Hello World</h1>
```

Example 3 — Changing the DOM

```js
const btn = document.getElementById("btn");

btn.addEventListener("click", () => {
  title.textContent = "You clicked the button!";
});
```

Visualization (simplified DOM tree for this page)

```js
Document
 └── html
      ├── head
      └── body
           ├── h1 (#title)
           ├── button (#btn)
           └── script
```

- DOM = representation of HTML as objects.

- JavaScript can read and modify the DOM.

- That’s how we make interactive web pages.

### **11.2 Nodes, Elements & Selectors**

#### **Explanation**

The DOM is made of nodes. But not all nodes are the same.

- Nodes → The general term. Every piece of the DOM (elements, text, attributes, comments) is a node.

- Elements → A special type of node that represents an HTML tag (\<div>, \<p>, \<button>).

- Text nodes → Represent the actual text inside elements.

- Attribute nodes → Represent things like id="title" or class="btn".

👉 So:

- All elements are nodes.

- But not all nodes are elements.

#### **Real-life use cases**

- Get a specific element (document.getElementById("title")).

- Select multiple elements (document.querySelectorAll(".item")).

- Loop through nodes to apply styles or change content.

#### **Examples**

Example 1 — Node Types

```js
<body>
  <h1 id="title">Hello</h1>
</body>
```

```js
Document
 └── html
      └── body
           └── h1 (element node)
                └── "Hello" (text node)
```

Example 2 — Selectors

```js
<ul>
  <li class="item">Apple</li>
  <li class="item">Banana</li>
  <li class="item">Orange</li>
</ul>
```

JavaScript ways to select:

```js
// Select by ID
const title = document.getElementById("title");

// Select first match
const firstItem = document.querySelector(".item");
console.log(firstItem.textContent); // Apple

// Select all matches (NodeList)
const allItems = document.querySelectorAll(".item");
allItems.forEach((item) => console.log(item.textContent));
```

Example 3 — Nodes vs Elements

```js
const list = document.querySelector("ul");

console.log(list.childNodes);
// NodeList → includes text nodes (line breaks, spaces, etc.)

console.log(list.children);
// HTMLCollection → only element nodes (<li>)
```

✅ childNodes = everything (text, comments, elements).
✅ children = only elements.

### **11.3 Attributes & Data-Attributes**

#### **Explanation**

Attributes are extra information inside HTML elements that describe them or define their behavior. Examples include:

- id → unique identifier for the element.

- class → used for styling or selecting multiple elements.

- src → source of an image or script.

- href → link URL.

- alt → alternative text for images.

Data-attributes are custom attributes that start with data- (like data-id or data-category). They allow you to store extra information in HTML that JavaScript can use, without affecting the page visually. You access them via the dataset property in JavaScript.

#### **Real-life use cases**

- Storing product IDs or categories in e-commerce websites.

- Storing user info, like selected theme or preferences.

- Passing element-specific information to event handlers, like which button was clicked.

- Adding metadata for interactive elements, like tabs, sliders, or modals.

#### **Examples**

Basic attributes:

```js
<img id="profilePic" src="avatar.jpg" alt="User Avatar">

-----

const img = document.getElementById("profilePic");

// Get attributes
console.log(img.getAttribute("src")); // "avatar.jpg"

// Set attributes
img.setAttribute("alt", "New User Avatar");

// Remove attributes
img.removeAttribute("alt");

```

Data-attributes:

```js
<div id="product" data-id="123" data-category="books">
  JavaScript Guide
</div>

-----

const product = document.getElementById("product");

// Accessing data-attributes
console.log(product.dataset.id);        // "123"
console.log(product.dataset.category);  // "books"

// Modifying data-attributes
product.dataset.id = "456";
product.dataset.category = "programming";

// Removing a data-attribute
product.removeAttribute("data-category");
```

Buttons in a shopping cart

```js
<button class="buy-btn" data-product-id="101">Buy</button>
<button class="buy-btn" data-product-id="102">Buy</button>

-----

const buttons = document.querySelectorAll(".buy-btn");
buttons.forEach(btn => {
  btn.addEventListener("click", () => {
    alert("Buying product with ID: " + btn.dataset.productId);
  });
});
```

Here, each button carries its own data-product-id, so JavaScript knows exactly which product was clicked.

### **11.4 Styles & CSS Variables**

#### **Explanation**

Every HTML element has a style property in JavaScript that lets you modify its CSS directly.

- Inline styles applied with JavaScript override external CSS rules (they have higher priority).

- You can set CSS properties using camelCase instead of hyphens.

  - Example: background-color → element.style.backgroundColor.

CSS Variables (also called custom properties) are reusable values defined in CSS with the -- prefix.
They are very useful when you want consistent theming across a site (e.g., light/dark mode).

- You define them in CSS inside a selector (often :root for global scope).

- You use them with the function var(--variableName).

- You can read and update them with JavaScript using getPropertyValue and setProperty.

#### **Real-life use cases**

- Dynamically changing the color of a button when hovered or clicked.

- Switching between light mode and dark mode with a toggle.

- Adjusting font size or spacing for accessibility.

- Reusing the same color palette across a project with variables (instead of repeating hex codes everywhere).

#### **Examples**

Changing styles with JavaScript:

```js
<p id="text">Hello, world!</p>;

const text = document.getElementById("text");

// Apply inline styles
text.style.color = "blue";
text.style.fontSize = "20px";
text.style.backgroundColor = "lightyellow";
```

Using CSS variables:

```js
<style>
  :root {
    --main-bg: white;
    --main-color: black;
  }

  body {
    background-color: var(--main-bg);
    color: var(--main-color);
  }
</style>

<button id="toggle">Toggle Theme</button>

-----

const root = document.documentElement; // <html> element
const toggleBtn = document.getElementById("toggle");

toggleBtn.addEventListener("click", () => {
  // Get current background color variable
  let currentBg = getComputedStyle(root).getPropertyValue("--main-bg").trim();

  if (currentBg === "white") {
    root.style.setProperty("--main-bg", "black");
    root.style.setProperty("--main-color", "white");
  } else {
    root.style.setProperty("--main-bg", "white");
    root.style.setProperty("--main-color", "black");
  }
});
```

This creates a dark/light mode switch using CSS variables updated by JavaScript.

### **11.5 CSS Classes**

#### **Explanation**

In HTML and CSS, the class attribute is used to group elements and apply the same styles to them.

In JavaScript, we can manipulate classes dynamically using the classList property of an element.

Main classList methods:

- .add("className") → adds a class.

- .remove("className") → removes a class.

- .toggle("className") → adds the class if not present, removes it if present.

- .contains("className") → checks if the element has a specific class.

- .replace("oldClass", "newClass") → replaces a class.

This is very useful for interactive UI elements like menus, tabs, themes, or animations.

#### **Real-life use cases**

- Show/hide menus or modals with a class toggle.

- Add an “active” class to the currently selected tab or button.

- Switch between dark and light themes.

- Animate elements by adding/removing classes connected to CSS animations.

#### **Examples**

Basic usage:

```js
<p id="text" class="highlight">Hello!</p>

<style>
  .highlight {
    color: blue;
    font-weight: bold;
  }

  .hidden {
    display: none;
  }
</style>

-----

const text = document.getElementById("text");

// Add a class
text.classList.add("hidden"); // <p> will disappear

// Remove a class
text.classList.remove("highlight"); // text loses blue/bold style

// Toggle a class
text.classList.toggle("hidden"); // adds/removes depending on state

// Check if it has a class
console.log(text.classList.contains("hidden")); // true or false
```

Practical example: Hamburger menu

```js
<button id="menuBtn">☰ Menu</button>
<nav id="menu" class="menu hidden">
  <a href="#">Home</a>
  <a href="#">About</a>
  <a href="#">Contact</a>
</nav>

<style>
  .menu {
    background: lightgray;
    padding: 10px;
  }
  .hidden {
    display: none;
  }
</style>

-----

const menuBtn = document.getElementById("menuBtn");
const menu = document.getElementById("menu");

menuBtn.addEventListener("click", () => {
  menu.classList.toggle("hidden");
});
```

Here, clicking the button toggles the menu’s visibility by adding/removing the hidden class.

### **11.6 Text & HTML**

#### **Explanation**

When working with the DOM, you often need to read or change the content inside an element.

JavaScript gives you different properties for this:

- textContent → gets/sets only the text inside an element.

  - It ignores HTML tags.

  - It returns all the text, even if it’s hidden with CSS.

- innerText → similar to textContent, but:

  - It respects CSS (it won’t return hidden text).

  - Slightly slower because it has to calculate styles.

- innerHTML → gets/sets HTML code inside an element.

  - You can insert or replace HTML elements.

  - ⚠️ Be careful: using innerHTML with user input can create security risks (XSS attacks).

#### **Real-life use cases**

- Updating a message or notification on a page.

- Creating interactive content, like inserting lists or tables dynamically.

- Changing button labels (e.g., "Play" → "Pause").

- Building content dynamically from an API (e.g., product listings).

#### **Examples**

Using textContent

```js
<p id="message">Hello <strong>World</strong>!</p>

-----

const msg = document.getElementById("message");

console.log(msg.textContent); // "Hello World!"
msg.textContent = "New plain text"; // Replaces everything with plain text
```

Using innerText

```js
<p id="status" style="display:none">Hidden text</p>

-----

const status = document.getElementById("status");

console.log(status.textContent); // "Hidden text" (ignores CSS)
console.log(status.innerText);   // "" (empty, because text is hidden)
```

Using innerHTML

```js
<div id="container">Old content</div>

-----

const container = document.getElementById("container");

// Replace HTML
container.innerHTML = "<h2>New <em>HTML</em> content!</h2>";

// Append HTML
container.innerHTML += "<p>Another paragraph</p>";
```

Practical Example: Updating a shopping cart

```js
<p id="cart">Cart: 0 items</p>
<button id="addBtn">Add Item</button>

-----

const cart = document.getElementById("cart");
const addBtn = document.getElementById("addBtn");

let count = 0;

addBtn.addEventListener("click", () => {
  count++;
  cart.textContent = `Cart: ${count} items`;
});
```

Here, every time the button is clicked, textContent updates the cart count.

### **11.7 DOM Traversing**

#### **Explanation**

DOM traversing means navigating through the structure of the DOM (Document Object Model) to find or move between related elements.

Every element in the DOM has relationships:

- Parent → the element that contains another element.

- Children → elements inside another element.

- Siblings → elements at the same level (inside the same parent).

JavaScript provides different properties and methods to move through these relationships:

- Parent nodes:

  - element.parentNode

  - element.parentElement

- Child nodes:

  - element.childNodes → includes text nodes, comments, etc.

  - element.children → only element nodes (cleaner for most cases).

  - element.firstChild, element.lastChild

  - element.firstElementChild, element.lastElementChild

- Siblings:

  - element.previousSibling, element.nextSibling

  - element.previousElementSibling, element.nextElementSibling

#### **Real-life use cases**

- Finding the parent element of a button to update its section.

- Getting the first/last item in a list.

- Moving between tabs, slides, or menu items by navigating siblings.

- Creating dynamic lists where you need to access children to update values.

#### **Examples**

Basic HTML structure:

```js
<div id="parent">
  <p id="first">First paragraph</p>
  <p id="second">Second paragraph</p>
  <p id="third">Third paragraph</p>
</div>
```

Accessing parent:

```js
const second = document.getElementById("second");

console.log(second.parentNode.id); // "parent"
console.log(second.parentElement.id); // "parent"
```

Accessing children:

```js
const parent = document.getElementById("parent");

console.log(parent.children); // HTMLCollection of <p> elements
console.log(parent.firstElementChild.textContent); // "First paragraph"
console.log(parent.lastElementChild.textContent); // "Third paragraph"
```

Accessing siblings:

```js
const second = document.getElementById("second");

console.log(second.previousElementSibling.textContent); // "First paragraph"
console.log(second.nextElementSibling.textContent); // "Third paragraph"
```

Practical Example: Highlighting the next item in a list

```js
<ul id="list">
  <li class="active">Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
<button id="nextBtn">Next</button>

<style>
  .active {
    background: yellow;
  }
</style>

-----

const nextBtn = document.getElementById("nextBtn");
const list = document.getElementById("list");

nextBtn.addEventListener("click", () => {
  const current = list.querySelector(".active");
  const next = current.nextElementSibling;

  if (next) {
    current.classList.remove("active");
    next.classList.add("active");
  }
});
```

Here, clicking Next moves the highlight to the next sibling in the list.

### **11.8 Creating Elements & Fragments**

#### **Explanation**

Sometimes you need to add new elements dynamically with JavaScript (instead of hardcoding them in HTML).

- Creating Elements:

  - Use document.createElement("tagName") to create a new element.

  - Use element.appendChild() or element.append() to add it to the DOM.

  - You can also set attributes, classes, and text before inserting it.

- Document Fragments:

  - A DocumentFragment is a lightweight container for DOM nodes.

  - It doesn’t get rendered itself but can hold multiple elements.

  - Adding many nodes one by one directly to the DOM is slow (because each insertion causes a reflow/repaint).

  - Using a fragment allows you to add everything at once → faster performance.

#### **Real-life use cases**

- Adding a new chat message in a messaging app.

- Building lists or tables dynamically from API data.

- Generating menus, dropdowns, or forms with JavaScript.

- Inserting many items at once (e.g., products in an online store) efficiently with a fragment.

#### **Examples**

Creating and appending a single element:

```js
<div id="container"></div>

-----

const container = document.getElementById("container");

// Create a new paragraph
const p = document.createElement("p");
p.textContent = "This is a new paragraph!";
p.classList.add("highlight");

// Add it to the container
container.appendChild(p);
```

Creating multiple elements with a loop:

```js
<ul id="list"></ul>

-----

const list = document.getElementById("list");

for (let i = 1; i <= 3; i++) {
  const li = document.createElement("li");
  li.textContent = "Item " + i;
  list.appendChild(li);
}

-----

<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

Using a Document Fragment (efficient way):

```js
<ul id="bigList"></ul>

-----

const bigList = document.getElementById("bigList");
const fragment = document.createDocumentFragment();

for (let i = 1; i <= 1000; i++) {
  const li = document.createElement("li");
  li.textContent = "Item " + i;
  fragment.appendChild(li);
}

// Append all at once
bigList.appendChild(fragment);
```

Here, instead of re-rendering 1000 times, the browser updates the DOM once, making it much faster.

### **11.9 HTML Templates**

#### **Explanation**

The \<template> element in HTML is a way to define reusable chunks of HTML that don’t render immediately when the page loads.

- A \<template> is invisible in the DOM until you use it.

- Inside the template, you can put HTML elements, text, or even scripts.

- With JavaScript, you can clone the template’s content and insert it into the page as many times as you need.

This is very useful when you need to repeat the same structure (like a card, list item, or modal) but with different data.

Key points:

- Templates are declared with \<template> tags in HTML.

- Access the content with .content.

- Clone it with document.importNode(template.content, true).

- Append it where you want.

#### **Real-life use cases**

- Product cards in an online shop.

- Chat message bubbles in a messaging app.

- Dynamic tables or lists from API data.

- Reusable modal dialogs or tooltips.

#### **Examples**

Defining and using a template:

```js
<template id="cardTemplate">
  <div class="card">
    <h3 class="title"></h3>
    <p class="description"></p>
  </div>
</template>

<div id="cardsContainer"></div>

-----

const template = document.getElementById("cardTemplate");
const container = document.getElementById("cardsContainer");

const data = [
  { title: "Card 1", description: "This is the first card." },
  { title: "Card 2", description: "This is the second card." },
  { title: "Card 3", description: "This is the third card." }
];

data.forEach(item => {
  // Clone template content
  const clone = document.importNode(template.content, true);

  // Fill with data
  clone.querySelector(".title").textContent = item.title;
  clone.querySelector(".description").textContent = item.description;

  // Append to container
  container.appendChild(clone);
});
```

Resulting HTML in the DOM:

```js
<div id="cardsContainer">
  <div class="card">
    <h3 class="title">Card 1</h3>
    <p class="description">This is the first card.</p>
  </div>
  <div class="card">
    <h3 class="title">Card 2</h3>
    <p class="description">This is the second card.</p>
  </div>
  <div class="card">
    <h3 class="title">Card 3</h3>
    <p class="description">This is the third card.</p>
  </div>
</div>
```

### **11.10 Modifying Elements **

#### **Explanation**

There are two main "eras" of DOM modification in JavaScript:

**Classic DOM Methods**

These methods were used before newer, cleaner APIs existed. They still work today and are very common in older code:

- parent.removeChild(child) → removes a child from its parent.

- parent.appendChild(newNode) → adds a node at the end of a parent.

- parent.insertBefore(newNode, referenceNode) → inserts a node before another.

- parent.replaceChild(newNode, oldNode) → replaces an existing node.

- node.cloneNode(deep) → clones a node (true = with children, false = only the node itself).

**Modern, Flexible Methods**

The DOM now has more convenient methods and positions to make insertion easier:

- Methods:

  - element.insertAdjacentElement(position, newElement) → insert an element at a position.

  - element.insertAdjacentHTML(position, htmlString) → insert raw HTML.

  - element.insertAdjacentText(position, text) → insert plain text.

  - document.importNode(node, deep) → import/clones nodes from another document (useful with \<template>).

- Positions (used with insertAdjacent...):

  - "beforebegin" → before the element itself.

  - "afterbegin" → inside the element, at the start.

  - "beforeend" → inside the element, at the end.

  - "afterend" → after the element itself.

#### **Real-life use cases**

**Classic DOM Methods**

- Removing list items in a to-do list (removeChild).

- Replacing a product card with updated info (replaceChild).

- Duplicating elements (e.g., for repeating forms) with cloneNode.

**Modern, Flexible Methods**

- Inserting ads or banners before/after content (insertAdjacentHTML).

- Adding new chat messages at the top or bottom of a chat window (afterbegin / beforeend).

- Quickly rendering HTML strings from an API response.

- Importing \<template> content with importNode.

#### **Examples**

**Classic DOM Methods**

```js
<ul id="list">
  <li id="item1">Item 1</li>
  <li id="item2">Item 2</li>
</ul>

-----

const list = document.getElementById("list");
const item1 = document.getElementById("item1");
const item2 = document.getElementById("item2");

// Remove a child
list.removeChild(item1);

// Replace a child
const newItem = document.createElement("li");
newItem.textContent = "New Item";
list.replaceChild(newItem, item2);

// Clone a node
const clone = newItem.cloneNode(true);
list.appendChild(clone);
```

**Modern, Flexible Methods**

```js
<div id="box">Hello</div>

-----

const box = document.getElementById("box");

// Insert HTML before the box
box.insertAdjacentHTML("beforebegin", "<p>Before the box</p>");

// Insert at the beginning inside the box
box.insertAdjacentHTML("afterbegin", "<span>Start → </span>");

// Insert at the end inside the box
box.insertAdjacentHTML("beforeend", "<span> ← End</span>");

// Insert after the box
box.insertAdjacentHTML("afterend", "<p>After the box</p>");

Resulting DOM:

<p>Before the box</p>
<div id="box">
  <span>Start → </span>
  Hello
  <span> ← End</span>
</div>
<p>After the box</p>
```

Using importNode with a template:

```js
<template id="tpl">
  <li>Template Item</li>
</template>

<ul id="list"></ul>

-----

const tpl = document.getElementById("tpl");
const list = document.getElementById("list");

// Import template content
const clone = document.importNode(tpl.content, true);
list.appendChild(clone);
```

### **11.11 Event Listeners**

#### **Explanation**

An event listener is a function that runs when something happens on a web page (an “event”).

- Common events:

  - Click ("click")

  - Mouse events ("mouseover", "mouseout")

  - Keyboard events ("keydown", "keyup")

  - Form events ("submit", "change")

  - Window events ("scroll", "resize")

The main method is:

```js
element.addEventListener(eventType, callback, options);
```

- eventType → string like "click".

- callback → function to run when the event happens.

- options (optional) → e.g. { once: true } (listener runs only once).

There’s also an older style:

```js
element.onclick = function() { ... }
```

but addEventListener is preferred because:

- You can attach multiple listeners to the same element.

- You can remove them with removeEventListener.

- More flexible (options like once, capture, etc.).

#### **Real-life use cases**

- Buttons: Open/close a modal when clicked.

- Forms: Validate input before submitting.

- Keyboard: Trigger shortcuts (Ctrl + S).

- Scrolling: Show a “Back to top” button.

- Animations: Run code when a transition ends.

#### **Examples**

Basic example (modern way):

```js
<button id="btn">Click Me</button>

-----

const btn = document.getElementById("btn");

btn.addEventListener("click", () => {
  alert("Button clicked!");
});
```

With multiple listeners:

```js
btn.addEventListener("click", () => console.log("First listener"));
btn.addEventListener("click", () => console.log("Second listener"));
```

✅ Both listeners run when the button is clicked.
(With btn.onclick = ... you could only have one function!)

Removing a listener:

```js
function greet() {
  alert("Hello!");
}

btn.addEventListener("click", greet);

// Later, remove it
btn.removeEventListener("click", greet);
```

Using options:

```js
btn.addEventListener(
  "click",
  () => {
    alert("Runs only once!");
  },
  { once: true }
);
```

✅ After the first click, the listener is automatically removed.

### **11.12 Events with Parameters & Removing Events**

#### **Explanation**

When adding event listeners, you sometimes need to pass parameters to the function.
But if you write:

```js
btn.addEventListener("click", myFunction("Hello"));
```

❌ This won’t work as expected, because myFunction("Hello") runs immediately instead of waiting for the click.

✅ Correct way → Use an anonymous function (or arrow function) to wrap your function call:

```js
btn.addEventListener("click", () => myFunction("Hello"));
```

Removing Events
You can remove an event listener using:

```js
element.removeEventListener(event, handler);
```

⚠️ But it only works if:

- The same function reference is used in addEventListener and removeEventListener.

- Anonymous functions cannot be removed, because they don’t have a reference.

#### **Real-life use cases**

- Events with parameters:

  - Pass a product ID to a "Buy" button.

  - Pass the username when clicking a profile link.

- Removing events:

  - Stop listening after a condition is met (e.g., only allow a button to be clicked - once).

  - Remove scroll listeners after a page finishes loading (for performance).

  - Detach listeners when elements are destroyed in a Single Page App (SPA).

#### **Examples**

Passing parameters to event handlers:

```js
<button id="btn1">Say Hello</button>
<button id="btn2">Say Goodbye</button>

-----
function greet(message) {
  alert(message);
}

document.getElementById("btn1")
  .addEventListener("click", () => greet("Hello!"));

document.getElementById("btn2")
  .addEventListener("click", () => greet("Goodbye!"));
```

Removing an event listener (correct way):

```js
<button id="btn">Click Me</button>

-----

function sayHi() {
  console.log("Hi!");
}

const btn = document.getElementById("btn");

// Add event listener
btn.addEventListener("click", sayHi);

// Remove event listener after 3 seconds
setTimeout(() => {
  btn.removeEventListener("click", sayHi);
  console.log("Listener removed");
}, 3000);
```

👉 If you click after 3 seconds, nothing happens.

Incorrect way (does not work):

```js
btn.addEventListener("click", () => console.log("Hi!"));
btn.removeEventListener("click", () => console.log("Hi!")); // ❌ won't work
```

### **11.13 Event Flow (Bubbling & Capturing)**

#### **Explanation**

When an event occurs on a DOM element (like a click), it doesn’t just stay on that element — it flows through the DOM tree. This flow happens in three phases:

- Capturing Phase (trickling down)

  - The event starts at the document root and travels down through ancestors to the - target element.

- Target Phase

  - The event reaches the element that was actually clicked.

- Bubbling Phase (trickling up)

  - The event then travels up through ancestors back to the document root.

By default, event listeners listen during the bubbling phase. But you can make a listener react during the capturing phase by setting:

```js
element.addEventListener("click", handler, { capture: true });
```

#### **Real-life use cases**

- Bubbling (default):

  - Attach one listener to a parent element and handle events for all its children (event delegation).

  - Example: Clicks on items in a <ul> list handled by a single listener on \<ul>.

- Capturing:

  - Rarely used, but useful when a parent needs to react before the target element.

  - Example: Logging every click in a container before child elements handle it.

#### **Examples**

HTML:

```js
<div id="parent" style="padding:20px; background:#eee;">
  Parent
  <button id="child">Child</button>
</div>
```

Bubbling (default):

```js
const parent = document.getElementById("parent");
const child = document.getElementById("child");

parent.addEventListener("click", () => console.log("Parent clicked"));
child.addEventListener("click", () => console.log("Child clicked"));

-----

✅ Click the button → Output:

Child clicked
Parent clicked
```

(child first, then bubbles up to parent)

Capturing phase:

```js
parent.addEventListener("click", () => console.log("Parent capturing"), {
  capture: true,
});

-----

✅ Click the button → Output:

Parent capturing
Child clicked
```

(parent handles event before child)

Stop propagation example:

```js
child.addEventListener("click", (event) => {
  console.log("Child clicked only");
  event.stopPropagation(); // stops bubbling
});
```

Now the parent listener does not run when clicking the child.

### **11.14 stopPropagation & preventDefault**

#### **Explanation**

These are two important methods of the Event object that control event behavior:

**event.stopPropagation()**

- Stops the event from traveling further through the DOM.

- Useful to prevent parent elements from reacting to the same event.

- Example: If a button is inside a \<div> with a click listener, calling stopPropagation() on the button click stops the div’s listener from running.

**event.preventDefault()**

- Prevents the default action the browser would normally take.

- Useful when you want to override standard behaviors.

- Examples:

  - Clicking a link (\<a>) normally navigates → preventDefault() stops navigation.

  - Submitting a form → preventDefault() stops the page from reloading.

#### **Real-life use cases**

**stopPropagation():**

- Nested menus or buttons where only the child action should run.

- Avoid triggering global click listeners accidentally.

**preventDefault():**

- Custom form validation before submission.

- Single-page apps: prevent link navigation and handle routing with JavaScript.

- Custom controls that replace default browser behavior (like custom sliders, drag-and-drop, etc.).

#### **Examples**

HTML

```js
<div id="parent" style="padding:20px; background:#eee;">
  Parent
  <button id="child">Child</button>
</div>

<form id="myForm">
  <input type="text" placeholder="Enter name">
  <button type="submit">Submit</button>
</form>

<a href="https://example.com" id="myLink">Go to example.com</a>

```

stopPropagation Example:

```js
const parent = document.getElementById("parent");
const child = document.getElementById("child");

parent.addEventListener("click", () => console.log("Parent clicked"));
child.addEventListener("click", (event) => {
  console.log("Child clicked");
  event.stopPropagation(); // stops bubbling
});

-----

✅ Click the button → Output:

Child clicked
```

Parent does not log anything because bubbling is stopped.

preventDefault Example (form):

```js
const form = document.getElementById("myForm");

form.addEventListener("submit", (event) => {
  event.preventDefault(); // stops page reload
  console.log("Form submission intercepted");
});
```

preventDefault Example (link):

```js
const link = document.getElementById("myLink");

link.addEventListener("click", (event) => {
  event.preventDefault(); // stops navigation
  alert("Link clicked, but not navigating!");
});
```

### **11.15 Event Delegation**

#### **Explanation**

Event delegation is a technique where you attach a single event listener to a parent element to handle events on its child elements, instead of adding separate listeners to each child.

- Works because of event bubbling: events triggered on children bubble up to the parent.

- You can then check which child triggered the event using event.target.

Benefits:

- Less memory usage (fewer listeners).

- Dynamically added elements are automatically handled.

- Cleaner and more maintainable code.

#### **Real-life use cases**

- A <ul> with many <li> items — one listener on <ul> instead of each <li>.

- Dynamic lists where new items are added later.

- Tables with many rows — one listener on <table> handles clicks for all <tr>.

- Forms with many buttons or inputs — handle all clicks with a single listener.

#### **Examples**

HTML:

```js
<ul id="menu">
  <li data-id="1">Item 1</li>
  <li data-id="2">Item 2</li>
  <li data-id="3">Item 3</li>
</ul>
```

JavaScript – Event Delegation:

```js
const menu = document.getElementById("menu");

menu.addEventListener("click", (event) => {
  const clickedItem = event.target; // element that was actually clicked

  if (clickedItem.tagName === "LI") {
    alert("You clicked item with ID: " + clickedItem.dataset.id);
  }
});
```

✅ Click any <li> → The parent <ul> listener handles it.

If you add more <li> later, you don’t need to add new listeners.

Dynamically adding items example:

```js
const newItem = document.createElement("li");
newItem.textContent = "Item 4";
newItem.dataset.id = "4";
menu.appendChild(newItem); // still handled by the parent listener
```

## **12. BOM (Browser Object Model)**

### **12.1 Properties & Events**

#### **Explanation**

The Browser Object Model (BOM) is everything the browser gives us to interact with the window (outside the document/DOM).

The window object is the global object in the browser. It contains:

- Properties → Information about the browser window.

- Events → Special events triggered by the browser (not by DOM elements).

Common BOM Properties

- window.innerWidth / window.innerHeight → Viewport size.

- window.outerWidth / window.outerHeight → Entire browser window size.

- window.location → Current URL information.

- window.navigator → Info about the browser, device, OS.

- window.history → Browsing history.

- window.screen → Screen resolution info.

Common BOM Events

- resize → Fires when the window is resized.

- scroll → Fires when the user scrolls.

- load → Fires when the page has fully loaded.

- beforeunload → Fires when the user tries to leave the page.

- online / offline → Fires when the network connection changes.

#### **Real-life use cases**

- Detect window resizing for responsive UI adjustments.

- Detect if the user is online/offline and show a warning.

- Use beforeunload to warn users if they try to close a page with unsaved work.

- Detect scroll position for infinite scrolling.

- Use navigator to detect browser/device features.

#### **Examples**

Detecting window resize:

```js
window.addEventListener("resize", () => {
  console.log(`Width: ${window.innerWidth}, Height: ${window.innerHeight}`);
});
```

Detecting scroll:

```js
window.addEventListener("scroll", () => {
  console.log("You scrolled to:", window.scrollY);
});
```

Online / Offline detection:

```js
window.addEventListener("online", () => console.log("Back online!"));
window.addEventListener("offline", () => console.log("You are offline!"));
```

Before unload (ask confirmation before leaving):

```js
window.addEventListener("beforeunload", (event) => {
  event.preventDefault();
  event.returnValue = ""; // Needed for some browsers
});
```

### **12.2 Methods**

#### **Explanation**

The Browser Object Model (BOM) provides useful methods (functions of the window object) that let us interact with the browser itself.

Here are the most common categories:

A. Popup Methods

- alert(message) → Shows a simple alert box.

- confirm(message) → Shows a confirmation box with OK / Cancel (returns true or false).

- prompt(message, default) → Shows an input box to get user text.

B. Window Control Methods

- open(url, name, specs) → Opens a new browser window or tab.

- close() → Closes the current window (only works if opened with JS).

- print() → Opens the print dialog.

C. Timing Methods

- setTimeout(function, delay) → Runs a function once after delay milliseconds.

- setInterval(function, delay) → Runs a function repeatedly every delay milliseconds.

- clearTimeout(id) / clearInterval(id) → Cancels the timers.

#### **Real-life use cases**

- Popup methods:

  - confirm() before deleting important data.

  - prompt() to quickly ask for small input.

- Window control:

  - print() to allow printing invoices or tickets.

  - open() to show help pages or authentication in a popup.

- Timing methods:

  - setTimeout() to delay animations or messages.

  - setInterval() to update clocks, counters, or fetch live data.

#### **Examples**

Popup methods:

```js
alert("Hello, welcome!");

if (confirm("Do you want to continue?")) {
  console.log("User clicked OK");
} else {
  console.log("User clicked Cancel");
}

const name = prompt("What is your name?", "Anonymous");
console.log("User's name is:", name);
```

Window control:

```js
// Opens Google in a new tab
const newWindow = window.open("https://google.com", "_blank");

// Print page
document.getElementById("printBtn").addEventListener("click", () => {
  window.print();
});
```

Timing methods:

```js
// Runs once after 2 seconds
setTimeout(() => console.log("This runs after 2 seconds"), 2000);

// Runs every second
const intervalId = setInterval(() => console.log("Tick..."), 1000);

// Stop after 5 seconds
setTimeout(() => clearInterval(intervalId), 5000);
```

### **12.3 URL, History, and Navigator Objects**

#### **Explanation**

A. location (URL Object)

The window.location object gives info about the current URL and lets you redirect or reload the page.

Common properties/methods:

- location.href → Full URL.

- location.protocol → http: or https:.

- location.hostname → Domain (e.g., example.com).

- location.pathname → Path after domain (e.g., /about).

- location.search → Query string (e.g., ?id=10).

- location.hash → Fragment identifier (e.g., #section2).

- location.reload() → Reloads the page.

- location.assign(url) → Navigate to a new page.

- location.replace(url) → Navigate, but without saving history.

B. history Object

The window.history object lets you navigate through browser history.

Common methods:

- history.back() → Go to previous page.

- history.forward() → Go to next page.

- history.go(n) → Go n steps in history (-1 = back, 1 = forward).

- history.pushState(state, title, url) → Add a new entry to history (used in SPAs).

- history.replaceState(state, title, url) → Replace the current entry.

C. navigator Object

The navigator object gives info about the browser, OS, and device.

Common properties:

- navigator.userAgent → Browser info (string).

- navigator.language → Current language.

- navigator.onLine → true if online, false if offline.

- navigator.geolocation → API to get user location (with permission).

- navigator.clipboard → Read/write clipboard (modern browsers).

#### **Real-life use cases**

- location: Redirect users after login, reload page, parse query strings (?id=123).

- history: Build single-page apps (SPAs) with client-side routing.

- navigator: Detect if the user is online/offline, get location for maps, copy text to clipboard.

#### **Examples**

Location object:

```js
console.log(location.href); // Full URL
console.log(location.hostname); // Domain
console.log(location.pathname); // Path

// Redirect to another page
// location.href = "https://example.com";

// Reload page
// location.reload();
```

History object:

```js
// Go back one page
document.getElementById("backBtn").addEventListener("click", () => {
  history.back();
});

// Move 2 steps forward (if possible)
history.go(2);

// Add new state to history (SPA technique)
history.pushState({ page: 1 }, "Title 1", "?page=1");
```

Navigator object:

```js
console.log(navigator.userAgent); // Browser details
console.log(navigator.language); // e.g., "en-US"

// Online/offline detection
if (!navigator.onLine) {
  alert("You are offline!");
}

// Clipboard API (modern browsers)
navigator.clipboard.writeText("Hello World").then(() => {
  console.log("Text copied!");
});
```

## **13. AJAX (Asynchronous JavaScript and XML)**

### **13.1 AJAX Introduction**

#### **Explanation**

AJAX stands for Asynchronous JavaScript And XML.
It’s a technique that allows web pages to request data from a server without reloading the page.

Key points:

- Asynchronous → The page keeps working while data is being fetched.

- Data formats → Originally XML, but today JSON is most common.

- Purpose → Improve user experience with dynamic content updates.

#### **Real-life use cases**

- Search suggestions → Google’s autocomplete fetches suggestions as you type.

- Live form validation → Check if a username/email already exists without reloading.

- Infinite scroll → Load more posts automatically when scrolling down.

- Dashboards → Fetch real-time stock prices, weather, or analytics.

- Chat apps → Load new messages without refreshing the page.

#### **Examples**

Without AJAX (old style):
Every action → Reloads the entire page to get new data. Slow and inefficient.

With AJAX (modern style):
The page loads once, and then requests data dynamically.

```js
// Basic example using Fetch API (modern AJAX)
fetch("https://jsonplaceholder.typicode.com/posts/1")
  .then((response) => response.json())
  .then((data) => {
    console.log("Post Title:", data.title);
  })
  .catch((error) => console.error("Error:", error));
```

✅ The request happens in the background, and only the needed content is updated.

### **13.2 XMLHttpRequest Object**

#### **Explanation**

Before fetch() (modern AJAX), the classic way to do AJAX was the XMLHttpRequest (XHR) object.

- It lets you send HTTP requests and receive responses asynchronously.

- Despite the name, it works with any type of data (not only XML).

- Still supported in all browsers (for legacy code), but fetch() is preferred today.

#### **Real-life use cases**

- Old websites built before fetch() existed.

- Projects that need IE support (since fetch() doesn’t work in IE).

- Handling file uploads with progress events (XHR supports .upload.onprogress, fetch doesn’t yet without extra APIs).

#### **Examples**

Basic GET Request:

```js
// Step 1: Create the request object
const xhr = new XMLHttpRequest();

// Step 2: Initialize request (method, URL, async=true)
xhr.open("GET", "https://jsonplaceholder.typicode.com/posts/1", true);

// Step 3: Define what happens when response arrives
xhr.onload = function () {
  if (xhr.status === 200) {
    const data = JSON.parse(xhr.responseText); // response is plain text → parse JSON
    console.log("Post Title:", data.title);
  } else {
    console.error("Request failed. Status:", xhr.status);
  }
};

// Step 4: Handle network errors
xhr.onerror = function () {
  console.error("Network Error");
};

// Step 5: Send the request
xhr.send();
```

POST Request (sending data):

```js
const xhr = new XMLHttpRequest();
xhr.open("POST", "https://jsonplaceholder.typicode.com/posts", true);
xhr.setRequestHeader("Content-Type", "application/json;charset=UTF-8");

xhr.onload = function () {
  if (xhr.status === 201) {
    // 201 Created
    console.log("New Post:", JSON.parse(xhr.responseText));
  }
};

xhr.send(
  JSON.stringify({
    title: "Hello World",
    body: "This is my first AJAX POST!",
    userId: 1,
  })
);
```

### **13.3 Fetch API**

#### **Explanation**

The Fetch API is the modern way to make HTTP requests in JavaScript.
It replaces the older XMLHttpRequest (XHR) with a cleaner, promise-based syntax.

Key differences from XHR:

- Uses Promises → easier to read and chain.

- Supports modern features like async/await.

- Cleaner API with built-in methods like .json(), .text(), .blob(), etc.

#### **Real-life use cases**

- Fetching data from REST APIs (posts, users, weather, etc.).

- Submitting forms to a server without reloading.

- Downloading resources (images, files, PDFs).

- Loading extra content (infinite scroll, live search).

#### **Examples**

GET Request

```js
fetch("https://jsonplaceholder.typicode.com/posts/1")
  .then((response) => {
    if (!response.ok) throw new Error(`HTTP error! Status: ${response.status}`);
    return response.json(); // parse JSON body
  })
  .then((data) => {
    console.log("Post Title:", data.title);
  })
  .catch((error) => console.error("Fetch error:", error));
```

POST Request

```js
fetch("https://jsonplaceholder.typicode.com/posts", {
  method: "POST",
  headers: {
    "Content-Type": "application/json",
  },
  body: JSON.stringify({
    title: "Hello World",
    body: "This is my first Fetch POST!",
    userId: 1,
  }),
})
  .then((response) => response.json())
  .then((data) => console.log("New Post:", data))
  .catch((error) => console.error("Error:", error));
```

Other Response Types

```js
// Get plain text
fetch("file.txt")
  .then((res) => res.text())
  .then((text) => console.log(text));

// Get image as Blob
fetch("image.png")
  .then((res) => res.blob())
  .then((blob) => {
    const imgURL = URL.createObjectURL(blob);
    document.body.innerHTML = `<img src="${imgURL}">`;
  });
```

### **13.4 Fetch API + async / await**

#### **Explanation**

The Fetch API works with Promises, but chaining .then() can get messy.
With async/await, your code looks synchronous while still being asynchronous.

- async → marks a function as asynchronous (it returns a Promise).

- await → pauses execution until the Promise resolves (inside async functions only).

- Makes AJAX code easier to read and maintain.

#### **Real-life use cases**

- APIs that require multiple requests in sequence (e.g., get user → then fetch posts).

- Cleaner code in projects with lots of AJAX calls (like dashboards, chat apps).

- Error handling with try...catch instead of .catch().

#### **Examples**

GET Request (async/await)

```js
async function getPost() {
  try {
    const res = await fetch("https://jsonplaceholder.typicode.com/posts/1");

    if (!res.ok) throw new Error(`HTTP Error: ${res.status}`);

    const data = await res.json(); // parse body as JSON
    console.log("Post Title:", data.title);
  } catch (err) {
    console.error("Fetch error:", err);
  }
}

getPost();
```

POST Request (async/await)

```js
async function createPost() {
  try {
    const res = await fetch("https://jsonplaceholder.typicode.com/posts", {
      method: "POST",
      headers: { "Content-Type": "application/json" },
      body: JSON.stringify({
        title: "Async/Await Example",
        body: "This was created with async/await!",
        userId: 1,
      }),
    });

    if (!res.ok) throw new Error(`HTTP Error: ${res.status}`);

    const data = await res.json();
    console.log("New Post:", data);
  } catch (err) {
    console.error("Error:", err);
  }
}

createPost();
```

Multiple Requests in Sequence

```js
async function getUserAndPosts() {
  try {
    const userRes = await fetch("https://jsonplaceholder.typicode.com/users/1");
    const user = await userRes.json();

    const postsRes = await fetch(
      `https://jsonplaceholder.typicode.com/users/${user.id}/posts`
    );
    const posts = await postsRes.json();

    console.log("User:", user.name);
    console.log(
      "Posts:",
      posts.map((p) => p.title)
    );
  } catch (err) {
    console.error("Error:", err);
  }
}

getUserAndPosts();
```

### **13.5 Axios Library**

#### **Explanation**

Axios is a popular third-party JavaScript library for making HTTP requests (AJAX).
It’s built on top of XMLHttpRequest, but with a simpler API and extra features that fetch() doesn’t provide out of the box.

Key advantages over Fetch:

- Automatically parses JSON (no need for response.json()).

- Better error handling (treats 404/500 as errors, unlike fetch).

- Built-in support for request/response interceptors.

- Supports older browsers (including IE11).

- Simplifies things like timeouts, canceling requests, uploading files.

#### **Real-life use cases**

- Many frontend frameworks (React, Vue, Angular) often use Axios for API calls.

- Projects needing consistent error handling.

- Apps requiring request headers in every call (e.g., authentication tokens).

- File uploads/downloads with progress monitoring.

#### **Examples**

Install Axios

```js
npm install axios

```

Or include via CDN:

```js
<script src="https://cdn.jsdelivr.net/npm/axios/dist/axios.min.js"></script>
```

GET Request

```js
axios
  .get("https://jsonplaceholder.typicode.com/posts/1")
  .then((response) => {
    console.log("Post Title:", response.data.title);
  })
  .catch((error) => {
    console.error("Axios error:", error);
  });
```

✅ Notice:

No response.json(), Axios already gives response.data as JS object.

POST Request

```js
axios
  .post("https://jsonplaceholder.typicode.com/posts", {
    title: "Axios Example",
    body: "This post was created with Axios!",
    userId: 1,
  })
  .then((response) => {
    console.log("New Post:", response.data);
  })
  .catch((error) => console.error("Error:", error));
```

Adding Headers (e.g., auth token)

```js
axios
  .get("https://jsonplaceholder.typicode.com/users", {
    headers: {
      Authorization: "Bearer my-secret-token",
    },
  })
  .then((res) => console.log(res.data));
```

Global Defaults

```js
axios.defaults.baseURL = "https://jsonplaceholder.typicode.com";
axios.defaults.headers.common["Authorization"] = "Bearer my-token";

// Now baseURL is used automatically
axios.get("/posts/1").then((res) => console.log(res.data));
```

Interceptors (Modify Requests/Responses Globally)

```js
axios.interceptors.request.use((config) => {
  console.log("Request sent at:", new Date().toISOString());
  return config;
});

axios.interceptors.response.use((response) => {
  console.log("Response received with status:", response.status);
  return response;
});
```

### **13.6 Axios + async / await**

#### **Explanation**

Axios already works with Promises, so it fits perfectly with async/await.
Using async/await makes your code look synchronous while still being asynchronous.

Benefits:

- Cleaner and easier-to-read code.

- Use try...catch for error handling instead of .catch().

- Works seamlessly with request/response interceptors.

#### **Real-life use cases**

- Fetching data from an API in a React or Vue component.

- Posting data to a server with minimal code.

- Multiple dependent requests (get user → get user posts).

- Any situation where .then() chaining becomes messy.

#### **Examples**

GET Request

```js
async function getUser() {
  try {
    const response = await axios.get(
      "https://jsonplaceholder.typicode.com/users/1"
    );
    console.log("User name:", response.data.name);
  } catch (error) {
    console.error("Error fetching user:", error.message);
  }
}

getUser();
```

POST Request

```js
async function createPost() {
  try {
    const response = await axios.post(
      "https://jsonplaceholder.typicode.com/posts",
      {
        title: "Async/Await Axios",
        body: "Created with async/await",
        userId: 1,
      }
    );

    console.log("New Post ID:", response.data.id);
  } catch (error) {
    console.error("Error creating post:", error.message);
  }
}

createPost();
```

Multiple Requests Sequentially

```js
async function getUserAndPosts() {
  try {
    const userRes = await axios.get(
      "https://jsonplaceholder.typicode.com/users/1"
    );
    const user = userRes.data;

    const postsRes = await axios.get(
      `https://jsonplaceholder.typicode.com/users/${user.id}/posts`
    );
    const posts = postsRes.data;

    console.log("User:", user.name);
    console.log(
      "Posts:",
      posts.map((p) => p.title)
    );
  } catch (error) {
    console.error("Error:", error.message);
  }
}

getUserAndPosts();
```

## **14. REST API (Representational State Transfer)**

### **14.1 Introduction to REST API**

#### **Explanation**

REST (Representational State Transfer) is a set of rules for building web APIs.
An API (Application Programming Interface) is like a menu in a restaurant: it tells you what you can order (do), and the server (kitchen) gives you the result (food).

In REST:

- Resources = Data (like users, posts, products).

- Each resource has a URL (like /users or /posts).

- You interact with resources using HTTP methods:

| HTTP Method | Action (CRUD)    | Example                            |
| ----------- | ---------------- | ---------------------------------- |
| **GET**     | Read             | `/users` → get all users           |
| **POST**    | Create           | `/users` → add a new user          |
| **PUT**     | Update (replace) | `/users/1` → replace user 1        |
| **PATCH**   | Update (partial) | `/users/1` → update part of user 1 |
| **DELETE**  | Delete           | `/users/1` → remove user 1         |

This is why REST is often explained as CRUD operations:

- Create → POST

- Read → GET

- Update → PUT/PATCH

- Delete → DELETE

#### **Real-life use cases**

- Web apps: Your app fetches users, posts, comments, products from a REST API.

- Mobile apps: The app calls a REST API to get data (like tweets, weather, etc.).

- Integrations: Payment APIs (Stripe, PayPal), Maps APIs, or social APIs (Twitter, GitHub).

#### **Examples**

Example REST API: https://jsonplaceholder.typicode.com

✅ GET (Read all posts)

```js
fetch("https://jsonplaceholder.typicode.com/posts")
  .then((res) => res.json())
  .then((data) => console.log("Posts:", data));
```

✅ GET (Read one post)

```js
fetch("https://jsonplaceholder.typicode.com/posts/1")
  .then((res) => res.json())
  .then((data) => console.log("Single Post:", data));
```

✅ POST (Create new post)

```js
fetch("https://jsonplaceholder.typicode.com/posts", {
  method: "POST",
  body: JSON.stringify({
    title: "My new post",
    body: "Hello world",
    userId: 1,
  }),
  headers: {
    "Content-type": "application/json; charset=UTF-8",
  },
})
  .then((res) => res.json())
  .then((data) => console.log("Created:", data));
```

✅ PUT (Update post)

```js
fetch("https://jsonplaceholder.typicode.com/posts/1", {
  method: "PUT",
  body: JSON.stringify({
    id: 1,
    title: "Updated Post",
    body: "Updated content",
    userId: 1,
  }),
  headers: {
    "Content-type": "application/json; charset=UTF-8",
  },
})
  .then((res) => res.json())
  .then((data) => console.log("Updated:", data));
```

✅ DELETE (Remove post)

```js
fetch("https://jsonplaceholder.typicode.com/posts/1", {
  method: "DELETE",
}).then(() => console.log("Post deleted"));
```

### **14.2 JSON Server (Local Fake API)**

#### **Explanation**

When we’re learning about REST APIs, we often need a server with data to test our GET, POST, PUT, and DELETE requests. But…
👉 Creating a real backend takes time and is harder when you’re just learning.

That’s where JSON Server comes in.

- JSON Server is a simple tool that turns a plain JSON file into a REST API.

- It gives you endpoints like /users, /posts, /products automatically.

- You can perform CRUD operations without coding the backend.

It’s like having a fake API running locally on your computer.

#### **Real-life use cases**

- Practicing AJAX/Fetch/Axios without needing a real backend.

- Prototyping frontend apps (React, Vue, Vanilla JS) with realistic API calls.

- Testing REST API concepts like pagination, filtering, searching.

#### **Examples**

Step 1: Install JSON Server

```js
npm install -g json-server

```

Step 2: Create a file db.json

```js
{
  "users": [
    { "id": 1, "name": "Alice", "age": 25 },
    { "id": 2, "name": "Bob", "age": 30 }
  ],
  "posts": [
    { "id": 1, "title": "Hello World", "content": "My first post!" }
  ]
}

```

Step 3: Run JSON Server

```js
json-server --watch db.json --port 3000

```

✅ Now you have a REST API running at http://localhost:3000

- GET http://localhost:3000/users → list of users

- GET http://localhost:3000/posts/1 → single post

- POST http://localhost:3000/users → create new user

- PUT http://localhost:3000/users/1 → update user

- DELETE http://localhost:3000/posts/1 → delete post

4. Fetch Example

```js
// GET all users
fetch("http://localhost:3000/users")
  .then((res) => res.json())
  .then((data) => console.log("Users:", data));

// POST new user
fetch("http://localhost:3000/users", {
  method: "POST",
  body: JSON.stringify({ name: "Charlie", age: 22 }),
  headers: { "Content-Type": "application/json" },
})
  .then((res) => res.json())
  .then((data) => console.log("User added:", data));
```

### **14.3 Consuming REST Data**

#### **Explanation**

“Consuming REST Data” means requesting and using data from a REST API in your application.

- A REST API exposes endpoints (URLs) where you can get or send data.

- Consuming the data usually involves:

  - Sending a request (GET, POST, etc.) to the API.

  - Receiving a response (usually JSON).

  - Using that response in your app (render on page, store in a variable, etc.).

- Key points:

  - GET → read data

  - POST → create data

  - PUT/PATCH → update data

  - DELETE → remove data

- You can consume REST data using:

  - Fetch API

  - AJAX (XMLHttpRequest)

  - Axios

#### **Real-life use cases**

- Showing a list of blog posts from a CMS.

- Displaying user profiles from a social app.

- Fetching products in an e-commerce site.

- Any case where your app depends on external data.

#### **Examples**

Using Fetch API

```js
fetch("https://jsonplaceholder.typicode.com/posts")
  .then((response) => response.json()) // parse JSON
  .then((data) => {
    data.forEach((post) => {
      console.log("Title:", post.title);
    });
  })
  .catch((error) => console.error("Error:", error));
```

Using Axios

```js
axios
  .get("https://jsonplaceholder.typicode.com/posts")
  .then((res) => {
    res.data.forEach((post) => {
      console.log("Title:", post.title);
    });
  })
  .catch((err) => console.error("Error:", err));
```

### **14.4 CRUD (Create, Read, Update, Delete)**

#### **Explanation**

CRUD is an acronym for the four basic operations you can perform on data when working with databases or APIs:

- C → Create → Add new data (usually with POST).

- R → Read → Get existing data (usually with GET).

- U → Update → Change existing data (usually with PUT or PATCH).

- D → Delete → Remove existing data (usually with DELETE).

In REST APIs, each operation maps to an HTTP method:

| Operation | HTTP Method | Example Endpoint       |
| --------- | ----------- | ---------------------- |
| Create    | POST        | `/posts`               |
| Read      | GET         | `/posts` or `/posts/1` |
| Update    | PUT/PATCH   | `/posts/1`             |
| Delete    | DELETE      | `/posts/1`             |

#### **Real-life use cases**

- Social media app:

  - Create → post a new status.

  - Read → view your feed.

  - Update → edit a comment.

  - Delete → remove a photo.

- E-commerce site:

  - Create → add a product to cart.

  - Read → view your cart.

  - Update → change product quantity.

  - Delete → remove product from cart.

#### **Examples**

Create (POST)

```js
fetch("https://jsonplaceholder.typicode.com/posts", {
  method: "POST",
  headers: { "Content-Type": "application/json" },
  body: JSON.stringify({
    title: "New Post",
    body: "Hello world!",
    userId: 1,
  }),
})
  .then((res) => res.json())
  .then((data) => console.log("Created:", data));
```

Read (GET)

```js
fetch("https://jsonplaceholder.typicode.com/posts/1")
  .then((res) => res.json())
  .then((data) => console.log("Read:", data));
```

Update (PUT)

```js
fetch("https://jsonplaceholder.typicode.com/posts/1", {
  method: "PUT",
  headers: { "Content-Type": "application/json" },
  body: JSON.stringify({
    id: 1,
    title: "Updated Post",
    body: "New content here",
    userId: 1,
  }),
})
  .then((res) => res.json())
  .then((data) => console.log("Updated:", data));
```

Delete (DELETE)

```js
fetch("https://jsonplaceholder.typicode.com/posts/1", {
  method: "DELETE",
}).then(() => console.log("Deleted post with ID 1"));
```

### **14.5 CRUD with AJAX**

#### **Explanation**

In this section, you learn to perform CRUD operations (Create, Read, Update, Delete) using AJAX, which is based on the older XMLHttpRequest object.

- Before Fetch API and Axios, XMLHttpRequest was the standard way to make HTTP requests in JavaScript.

- Even though it’s less common today, understanding it is important because you’ll still see it in legacy code.

#### **Real-life use cases**

- Old projects built before Fetch existed (pre-2015).

- Libraries that internally still rely on XMLHttpRequest.

- Debugging legacy apps in companies that haven’t migrated to Fetch/Axios yet.

#### **Examples**

Read (GET)

```js
const xhr = new XMLHttpRequest();
xhr.open("GET", "https://jsonplaceholder.typicode.com/posts/1");
xhr.onload = () => {
  if (xhr.status === 200) {
    console.log("Read:", JSON.parse(xhr.responseText));
  }
};
xhr.send();
```

Create (POST)

```js
const xhr = new XMLHttpRequest();
xhr.open("POST", "https://jsonplaceholder.typicode.com/posts");
xhr.setRequestHeader("Content-Type", "application/json;charset=UTF-8");

xhr.onload = () => {
  if (xhr.status === 201) {
    console.log("Created:", JSON.parse(xhr.responseText));
  }
};

xhr.send(
  JSON.stringify({
    title: "New Post",
    body: "Hello AJAX!",
    userId: 1,
  })
);
```

Update (PUT)

```js
const xhr = new XMLHttpRequest();
xhr.open("PUT", "https://jsonplaceholder.typicode.com/posts/1");
xhr.setRequestHeader("Content-Type", "application/json;charset=UTF-8");

xhr.onload = () => {
  if (xhr.status === 200) {
    console.log("Updated:", JSON.parse(xhr.responseText));
  }
};

xhr.send(
  JSON.stringify({
    id: 1,
    title: "Updated Post",
    body: "Updated content here",
    userId: 1,
  })
);
```

Delete (DELETE)

```js
const xhr = new XMLHttpRequest();
xhr.open("DELETE", "https://jsonplaceholder.typicode.com/posts/1");
xhr.onload = () => {
  if (xhr.status === 200) {
    console.log("Deleted post with ID 1");
  }
};
xhr.send();
```

### **14.6 CRUD with Fetch**

#### **Explanation**

Now we move from AJAX (old style) to Fetch API (modern style).

- fetch() is a built-in JavaScript function (no need for external libraries).

- It returns a Promise, so you use .then() or async/await to handle responses.

- Much simpler and cleaner than XMLHttpRequest.

Fetch supports all CRUD operations by combining:

- HTTP methods: GET, POST, PUT, PATCH, DELETE.

- Headers (usually Content-Type: application/json).

- Request body (JSON.stringify() for objects).

#### **Real-life use cases**

- Single Page Applications (SPAs) that need to load data dynamically.

- Sending forms to servers without reloading the page.

- Consuming REST APIs from services like GitHub, Twitter, or your own backend.

#### **Examples**

Read (GET)

```js
fetch("https://jsonplaceholder.typicode.com/posts/1")
  .then((res) => res.json()) // parse response as JSON
  .then((data) => console.log("Read:", data))
  .catch((err) => console.error("Error:", err));
```

Create (POST)

```js
fetch("https://jsonplaceholder.typicode.com/posts", {
  method: "POST",
  headers: { "Content-Type": "application/json" },
  body: JSON.stringify({
    title: "New Post",
    body: "Hello Fetch!",
    userId: 1,
  }),
})
  .then((res) => res.json())
  .then((data) => console.log("Created:", data))
  .catch((err) => console.error("Error:", err));
```

Update (PUT)

```js
fetch("https://jsonplaceholder.typicode.com/posts/1", {
  method: "PUT",
  headers: { "Content-Type": "application/json" },
  body: JSON.stringify({
    id: 1,
    title: "Updated Post",
    body: "Updated content here",
    userId: 1,
  }),
})
  .then((res) => res.json())
  .then((data) => console.log("Updated:", data))
  .catch((err) => console.error("Error:", err));
```

Delete (DELETE)

```js
fetch("https://jsonplaceholder.typicode.com/posts/1", {
  method: "DELETE",
})
  .then(() => console.log("Deleted post with ID 1"))
  .catch((err) => console.error("Error:", err));
```

### **14.7 CRUD with Axios**

#### **Explanation**

Now we use Axios, a third-party library that simplifies HTTP requests.

Why Axios is popular:

- Automatically parses JSON (no need for .json()).

- Shorter and cleaner syntax than fetch().

- Built-in error handling.

- Supports interceptors (to add headers or log requests globally).

- Works in both browser and Node.js.

#### **Real-life use cases**

- Front-end frameworks (React, Vue, Angular) often use Axios for REST APIs.

- Projects with authentication → easily add Authorization headers.

- Complex apps that need global request handling (logging, retrying, tokens).

#### **Examples**

Read (GET)

```js
axios
  .get("https://jsonplaceholder.typicode.com/posts/1")
  .then((res) => console.log("Read:", res.data))
  .catch((err) => console.error("Error:", err));
```

Create (POST)

```js
axios
  .post("https://jsonplaceholder.typicode.com/posts", {
    title: "New Post",
    body: "Hello Axios!",
    userId: 1,
  })
  .then((res) => console.log("Created:", res.data))
  .catch((err) => console.error("Error:", err));
```

Update (PUT)

```js
axios
  .put("https://jsonplaceholder.typicode.com/posts/1", {
    id: 1,
    title: "Updated Post",
    body: "Updated content here",
    userId: 1,
  })
  .then((res) => console.log("Updated:", res.data))
  .catch((err) => console.error("Error:", err));
```

Delete (DELETE)

```js
axios
  .delete("https://jsonplaceholder.typicode.com/posts/1")
  .then(() => console.log("Deleted post with ID 1"))
  .catch((err) => console.error("Error:", err));
```

Async/await works beautifully with Axios:

```js
async function createPost() {
  try {
    const res = await axios.post("https://jsonplaceholder.typicode.com/posts", {
      title: "My Post",
      body: "Async/Await with Axios",
      userId: 1,
    });
    console.log("Created:", res.data);
  } catch (err) {
    console.error("Error:", err);
  }
}
createPost();
```

## **15. WordPress REST API**

### **15.1 WordPress REST API + Fetch**

#### **Explanation**

WordPress (WP) includes a built-in REST API.

- It exposes your site’s content (posts, pages, categories, users, etc.) in JSON format.

- You can interact with WordPress programmatically (read or write data).

- The API follows the same CRUD pattern you already learned (GET, POST, PUT, DELETE).

Default endpoint structure:

```js
https://your-wordpress-site.com/wp-json/wp/v2/{resource}
```

Examples of resources:

- /posts → blog posts

- /pages → static pages

- /comments → comments

- /users → authors and admins

#### **Real-life use cases**

- Headless WordPress: Use WP only as a backend, and build your frontend with React, Vue, or vanilla JS.

- Mobile apps: Fetch content from a WP site into iOS/Android apps.

- Custom dashboards: Display WP posts in your own admin panel.

- External integrations: e.g., pull blog posts into another website.

#### **Examples**

Read posts

```js
fetch("https://example.com/wp-json/wp/v2/posts")
  .then((res) => res.json())
  .then((data) => {
    data.forEach((post) => {
      console.log("Post:", post.title.rendered);
    });
  })
  .catch((err) => console.error("Error:", err));
```

Read a single post

```js
fetch("https://example.com/wp-json/wp/v2/posts/1")
  .then((res) => res.json())
  .then((post) => console.log("Single Post:", post.title.rendered))
  .catch((err) => console.error("Error:", err));
```

Create a new post (authenticated)

👉 Requires authentication (usually a WordPress user with a valid token).

```js
fetch("https://example.com/wp-json/wp/v2/posts", {
  method: "POST",
  headers: {
    "Content-Type": "application/json",
    Authorization: "Bearer YOUR_TOKEN_HERE",
  },
  body: JSON.stringify({
    title: "New Post from Fetch",
    content: "This is content created via the WordPress REST API!",
    status: "publish",
  }),
})
  .then((res) => res.json())
  .then((newPost) => console.log("Created:", newPost))
  .catch((err) => console.error("Error:", err));
```

### **15.2 Infinite Scroll**

#### **Explanation**

Infinite scroll is a technique where content (posts, products, images, etc.) automatically loads as the user scrolls down the page.

Instead of showing all items at once (which could be slow), the page:

- Loads the first batch of items.

- Detects when the user is near the bottom.

- Makes another API request (like to the WordPress REST API).

- Appends the new items.

- Repeats the process → giving an “endless feed” experience.

This is common on sites like Facebook, Instagram, or Twitter.

#### **Real-life use cases**

- Blogs: Automatically load more WordPress posts when scrolling.

- E-commerce stores: Show products without pagination.

- Social media apps: Endless feeds (posts, comments, messages).

- Image galleries: Load more images as needed.

#### **Examples**

Example with Fetch + IntersectionObserver

```js
<div id="posts"></div>
<div id="loadMore">Loading more posts...</div>

<script>
let page = 1;

async function loadPosts() {
  try {
    const res = await fetch(
      `https://jsonplaceholder.typicode.com/posts?_page=${page}&_limit=5`
    );
    const posts = await res.json();

    const container = document.getElementById("posts");
    posts.forEach(post => {
      const div = document.createElement("div");
      div.innerHTML = `<h3>${post.title}</h3><p>${post.body}</p>`;
      container.appendChild(div);
    });

    page++; // next page for future requests
  } catch (err) {
    console.error("Error loading posts:", err);
  }
}

// IntersectionObserver detects when #loadMore is visible
const observer = new IntersectionObserver(entries => {
  if (entries[0].isIntersecting) {
    loadPosts();
  }
});

observer.observe(document.getElementById("loadMore"));

// Load first batch
loadPosts();
</script>

```

The API should support pagination (?page=1&limit=10, etc.).

IntersectionObserver is the modern way (better than scroll events).

Be careful with performance: infinite scroll can overload if you don’t stop at some limit.

For WordPress, the REST API supports pagination via:

```js
https://example.com/wp-json/wp/v2/posts?page=2&per_page=5

```

## **16. SPA (Single Page Application)**

### **16.1 SPA Introduction**

#### **Explanation**

A Single Page Application (SPA) is a type of web app that:

- Loads a single HTML page (usually index.html).

- Dynamically updates the content with JavaScript.

- Doesn’t reload the page when navigating between sections.

Instead of asking the server for a new page every time, the SPA:

- Fetches data (via REST API or backend).

- Updates the DOM dynamically.

- Manages routing on the client side (using JS to simulate navigation).

Examples of SPAs:

- Gmail

- Twitter

- Trello

- Netflix

👉 The user experience is smoother and faster, because only the data changes, not the whole page.

#### **Real-life use cases**

- Dashboards (real-time updates without refresh).

- Social media feeds (Twitter, Instagram).

- Project management tools (Trello, Asana).

- E-commerce product browsers (smooth navigation without reload).

#### **Examples**

Mini SPA (Vanilla JS)

```js
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Mini SPA</title>
</head>
<body>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <div id="app"></div>

  <script>
    const routes = {
      home: "<h1>Welcome to Home</h1><p>This is the homepage.</p>",
      about: "<h1>About</h1><p>We are learning SPAs!</p>",
      contact: "<h1>Contact</h1><p>Email: test@example.com</p>"
    };

    function router() {
      const hash = location.hash.slice(1) || "home";
      document.getElementById("app").innerHTML = routes[hash];
    }

    window.addEventListener("hashchange", router);
    window.addEventListener("load", router);
  </script>
</body>
</html>

```

### **16.2 Project Structure (assets, helpers, components)**

#### **Explanation**

When building SPAs, your project grows fast — lots of files, scripts, and styles.
A clean project structure helps you:

- Separate logic from UI.

- Reuse code.

- Maintain and scale the app easily.

Typical SPA project is divided into:

- assets/ → images, CSS, fonts.

- helpers/ → utility functions (like API calls).

- components/ → UI blocks (header, posts, footer).

- index.html → entry point of the app.

- app.js → main file to start the SPA.

#### **Real-life use cases**

Blog SPA:

- components: Header.js, PostCard.js, Loader.js

- helpers: fetchPosts.js, paginate.js

E-commerce SPA:

- components: ProductItem.js, Cart.js

- helpers: currencyFormatter.js, apiClient.js

Dashboard SPA:

- components: Sidebar.js, Chart.js

- helpers: auth.js, dateFormatter.js

#### **Examples**

Example Folder Structure

```js
my-spa/
│── index.html
│── app.js
│
├── assets/
│   ├── css/
│   │   └── styles.css
│   └── img/
│       └── logo.png
│
├── helpers/
│   ├── api.js
│   └── utils.js
│
└── components/
    ├── Header.js
    ├── PostCard.js
    └── Footer.js

```

helpers/api.js

```js
export async function fetchData(url) {
  const res = await fetch(url);
  return await res.json();
}
```

components/Header.js

```js
export function Header() {
  return `<header><h1>My SPA</h1></header>`;
}
```

app.js

```js
import { Header } from "./components/Header.js";
import { fetchData } from "./helpers/api.js";

document.body.innerHTML = Header();

fetchData("https://jsonplaceholder.typicode.com/posts?_limit=3").then(
  (posts) => {
    posts.forEach((p) => {
      const div = document.createElement("div");
      div.innerHTML = `<h3>${p.title}</h3>`;
      document.body.appendChild(div);
    });
  }
);
```

- Keep assets (static files) separate from logic (helpers) and UI (components).

- Components can return HTML templates (strings) or directly manipulate the DOM.

- This structure is the foundation for frameworks like React or Vue — they just automate and enhance it.

### **16.3 REST API Connection Helper**

#### **Explanation**

A REST API Connection Helper is a reusable function or module that simplifies how your application communicates with APIs. Instead of writing fetch or axios requests all over your code, you create a central helper that:

- Handles GET, POST, PUT, DELETE requests.

- Applies consistent headers (like Content-Type).

- Manages errors and provides meaningful messages.

- Makes your code cleaner and easier to maintain.

This way, your UI components don’t care about request details—they just call the helper.

#### **Real-life use cases**

- Blog Application → Fetch posts, add new posts, update existing posts, delete posts.

- E-commerce Store → Get product lists, create new orders, update user data, delete cart items.

- Dashboard/Analytics App → Connect to multiple APIs with a single, consistent interface.

Basically, any SPA (Single Page Application) that interacts with APIs benefits from a helper.

#### **Examples**

✅ Example with fetch

```js
// apiHelper.js
const apiHelper = (endpoint, options = {}) => {
  const defaultHeaders = {
    "Content-Type": "application/json",
  };

  options.method = options.method || "GET";
  options.headers = options.headers
    ? { ...defaultHeaders, ...options.headers }
    : defaultHeaders;

  return fetch(endpoint, options)
    .then((res) =>
      res.ok
        ? res.json()
        : Promise.reject({
            err: true,
            status: res.status || "00",
            statusText: res.statusText || "Something went wrong",
          })
    )
    .catch((err) => err);
};

export default apiHelper;
```

✅ Usage:

```js
import apiHelper from "./apiHelper.js";

const URL = "https://jsonplaceholder.typicode.com/posts";

// GET
apiHelper(URL).then((data) => console.log(data));

// POST
apiHelper(URL, {
  method: "POST",
  body: JSON.stringify({
    title: "New Post",
    body: "This is a new post",
    userId: 1,
  }),
}).then((data) => console.log(data));
```

✅ Example with axios

```js
// apiHelper.js
import axios from "axios";

const apiHelper = axios.create({
  baseURL: "https://jsonplaceholder.typicode.com/",
  headers: { "Content-Type": "application/json" },
});

export default apiHelper;
```

✅ Usage:

```js
import apiHelper from "./apiHelper.js";

apiHelper.get("/posts").then((res) => console.log(res.data));
```

### **16.4 AJAX Requests Helper**

#### **Explanation**

An AJAX Requests Helper is similar to the REST API helper, but specifically focused on making asynchronous HTTP requests (usually using XMLHttpRequest or fetch) in a clean, reusable way.

Its main purpose is to:

- Simplify repeated AJAX calls.

- Handle success, error, and loading states consistently.

- Avoid duplicating code in multiple components.

- Integrate smoothly with SPAs to dynamically update content without reloading the page.

Think of it as a utility module that wraps your fetch/axios calls and provides standardized responses for your app.

#### **Real-life use cases**

- Dynamic content loading → Load more posts, comments, or products without refreshing the page.

- Form submission → Submit contact forms or user data asynchronously.

- Filters and searches → Update search results instantly by calling an API.

- Dashboard updates → Fetch analytics or metrics at intervals without reloading.

Basically, anytime your SPA needs to communicate with a backend and you want consistent, reusable code, an AJAX helper is perfect.

#### **Examples**

✅ Example with fetch wrapper

```js
// ajaxHelper.js
export const ajaxHelper = async (url, options = {}) => {
  const defaultHeaders = { "Content-Type": "application/json" };
  options.method = options.method || "GET";
  options.headers = options.headers
    ? { ...defaultHeaders, ...options.headers }
    : defaultHeaders;

  try {
    const res = await fetch(url, options);
    if (!res.ok) throw new Error(`Error: ${res.status}`);
    return await res.json();
  } catch (err) {
    console.error(err);
    return { error: true, message: err.message };
  }
};
```

✅ Usage:

```js
import { ajaxHelper } from "./ajaxHelper.js";

const API_URL = "https://jsonplaceholder.typicode.com/posts";

// GET posts
ajaxHelper(API_URL).then((data) => console.log("Posts:", data));

// POST a new post
ajaxHelper(API_URL, {
  method: "POST",
  body: JSON.stringify({ title: "Hello", body: "AJAX helper", userId: 1 }),
}).then((data) => console.log("Created:", data));
```

✅ Example with XMLHttpRequest (classic AJAX)

```js
export function ajaxXHR(url, callback) {
  const xhr = new XMLHttpRequest();
  xhr.open("GET", url);
  xhr.onload = () => {
    if (xhr.status >= 200 && xhr.status < 300) {
      callback(null, JSON.parse(xhr.responseText));
    } else {
      callback(`Error: ${xhr.status}`, null);
    }
  };
  xhr.send();
}

// Usage
ajaxXHR("https://jsonplaceholder.typicode.com/posts", (err, data) => {
  if (err) console.error(err);
  else console.log(data);
});
```

```js

```

### **16.5 First UI Components**

#### **Explanation**

In a Single Page Application (SPA), UI Components are the building blocks of the interface.
They are small, reusable pieces of code that combine HTML (structure), CSS (style), and JS (behavior) into one unit.

For example:

- A button with custom style and click behavior

- A card showing a blog post (title, image, description)

- A navigation menu

The idea is: instead of repeating code, you create components once and then reuse them anywhere in the app.

#### **Real-life use cases**

- Blog Website → A reusable Post Card component to display different posts dynamically.

- E-commerce → A Product Card component showing product info, price, and “Add to Cart” button.

- Dashboard → A Widget component (like weather, sales, notifications) that updates with new data.

- Navigation bars or footers that appear the same across all pages.

#### **Examples**

✅ Example 1: Simple Button Component

```js
function Button(label, onClick) {
  const btn = document.createElement("button");
  btn.textContent = label;
  btn.classList.add("my-btn");
  btn.addEventListener("click", onClick);
  return btn;
}

// Usage
document.body.appendChild(Button("Click me!", () => alert("Button clicked!")));
```

✅ Example 2: Blog Post Card Component

```js
function PostCard(post) {
  const card = document.createElement("div");
  card.classList.add("post-card");

  card.innerHTML = `
    <h2>${post.title}</h2>
    <p>${post.body}</p>
  `;

  return card;
}

// Example usage
const samplePost = { title: "My first post", body: "This is the content." };
document.body.appendChild(PostCard(samplePost));
```

Here, you can reuse PostCard for any post, just passing different data.

👉 Components in this stage are vanilla JS functions that return DOM elements. Later (in React or frameworks), components get more powerful, but the concept is the same:
reusable, modular pieces of UI.

### **16.6 Header Component**

#### **Explanation**

The Header Component is a reusable part of an SPA that usually appears at the top of every page.
It often contains:

- The site logo or title

- A navigation menu (links to Home, About, Blog, Contact, etc.)

- Sometimes a search bar or user profile/avatar

Since SPAs don’t reload the page completely, the header must be built once and reused across all “views.”
Instead of writing <header> in every HTML page, you create a Header Component in JavaScript and insert it dynamically.

#### **Real-life use cases**

- Blog site → The header has logo + menu linking to Home, Blog, Contact.

- E-commerce store → The header shows logo, navigation, and cart icon.

- Dashboard → Header includes user profile + logout button.

#### **Examples**

✅ Example 1: Basic Header Component

```js
function Header() {
  const header = document.createElement("header");
  header.classList.add("site-header");

  header.innerHTML = `
    <h1>My SPA</h1>
    <nav>
      <a href="#/">Home</a>
      <a href="#/about">About</a>
      <a href="#/contact">Contact</a>
    </nav>
  `;

  return header;
}

// Usage
document.body.prepend(Header());
```

✅ Example 2: Header with Dynamic Items

```js
function Header(links) {
  const header = document.createElement("header");
  header.classList.add("site-header");

  const navLinks = links
    .map((link) => `<a href="${link.href}">${link.label}</a>`)
    .join(" ");

  header.innerHTML = `
    <h1>My Website</h1>
    <nav>${navLinks}</nav>
  `;

  return header;
}

// Usage
const menu = [
  { href: "#/", label: "Home" },
  { href: "#/blog", label: "Blog" },
  { href: "#/contact", label: "Contact" },
];

document.body.prepend(Header(menu));
```

Here, the menu items are dynamic → you could later load them from a database or config file.

👉 The Header Component is important in SPA because it’s often shared across all views.

### **16.7 Dynamic Rendering**

#### **Explanation**

Dynamic Rendering means generating or updating the content of a webpage using JavaScript, instead of writing everything in static HTML.

In an SPA:

- You don’t reload the whole page when the user clicks a link.

- Instead, JavaScript inserts or replaces components in a specific part of the page (like a <main> or #app container).

This makes the experience faster and smoother because only the part that changes is updated, not the whole page.

#### **Real-life use cases**

- Blog SPA → Clicking a post shows its content inside the main area, without refreshing.

- E-commerce site → When you click a product, the details appear dynamically.

- Dashboards → Widgets and charts update without page reload.

- Single-page portfolio → Navigation links load sections dynamically.

#### **Examples**

✅ Example 1: Switching Views

```js
function Home() {
  return `<h2>Welcome to Home</h2><p>This is the homepage.</p>`;
}

function About() {
  return `<h2>About Us</h2><p>We are building a cool SPA.</p>`;
}

function render(view) {
  const app = document.getElementById("app");
  app.innerHTML = view;
}

// Usage
render(Home()); // Show home
setTimeout(() => render(About()), 3000); // After 3s, show about
```

Here the view changes dynamically without reloading the page.

✅ Example 2: Rendering Posts Dynamically

```js
const posts = [
  { title: "Post 1", body: "This is the first post." },
  { title: "Post 2", body: "This is the second post." },
];

function renderPosts() {
  const app = document.getElementById("app");
  app.innerHTML = posts
    .map(
      (post) => `<article><h2>${post.title}</h2><p>${post.body}</p></article>`
    )
    .join("");
}

renderPosts();
```

Here we loop through data and dynamically create HTML for each post.

### **16.8 Routing (Router)**

#### **Explanation**

In a traditional website, when you click a link, the browser makes a new request to the server and loads a new page.

But in a Single Page Application (SPA), you don’t want to reload the page — you just want to swap content dynamically.

That’s where a Router comes in:

- It listens for changes in the URL (usually after # or using the History API).

- Based on the URL, it decides which component or view to render.

👉 Think of it as the "traffic director" of your app:

- #/home → show Home view

- #/about → show About view

- #/contact → show Contact view

#### **Real-life use cases**

- Blog SPA → #/post/1 shows post 1, #/post/2 shows post 2.

- E-commerce SPA → #/products lists products, #/cart shows shopping cart.

- Portfolio SPA → #/about, #/projects, #/contact — all inside one HTML file.

- Dashboard → different sections (#/analytics, #/settings) without reloading.

#### **Examples**

✅ Example 1: Simple Hash Router

```js
function Home() {
  return "<h2>Home</h2><p>Welcome to the homepage.</p>";
}

function About() {
  return "<h2>About</h2><p>This is the about section.</p>";
}

function Contact() {
  return "<h2>Contact</h2><p>Get in touch with us.</p>";
}

function router() {
  const app = document.getElementById("app");
  switch (location.hash) {
    case "#/about":
      app.innerHTML = About();
      break;
    case "#/contact":
      app.innerHTML = Contact();
      break;
    default:
      app.innerHTML = Home();
  }
}

window.addEventListener("hashchange", router);
window.addEventListener("load", router);
```

✅ Example 2: Router with a Map (cleaner)

```js
const routes = {
  "#/": () => "<h2>Home</h2><p>Welcome!</p>",
  "#/about": () => "<h2>About</h2><p>About us page.</p>",
  "#/contact": () => "<h2>Contact</h2><p>Contact info.</p>",
};

function router() {
  const app = document.getElementById("app");
  const render = routes[location.hash] || routes["#/"];
  app.innerHTML = render();
}

window.addEventListener("hashchange", router);
window.addEventListener("load", router);
```

This makes the router more scalable — easier to add new routes later.

### **16.9 App Refactoring & Async Routing**

#### **Explanation**

By now, your SPA probably has:

- Components (like Header, PostCard)

- A Router that shows views depending on the URL

But as your app grows, the code can get messy and repetitive.
That’s why you need refactoring: reorganizing your code into smaller, cleaner, reusable modules.

At the same time, some routes need asynchronous data (for example, fetching blog posts or products from an API). This is where Async Routing comes in:

- Instead of returning static HTML, your router can wait for data (async/await) and then render the view.

#### **Real-life use cases**

- Blog SPA → /posts route fetches posts from JSON Server or WordPress API before rendering.

- E-commerce SPA → /products loads product data dynamically from an API.

- Dashboard SPA → /analytics loads charts only when that route is visited.

- Better code structure → Each view (Home, About, Contact) in its own file/module, instead of a huge app.js.

#### **Examples**

✅ Example 1: Refactored Routes (modular)

```js
// home.js
export function Home() {
  return "<h2>Home</h2><p>Welcome to the homepage.</p>";
}

// about.js
export function About() {
  return "<h2>About</h2><p>This is the about page.</p>";
}

// router.js
import { Home } from "./home.js";
import { About } from "./about.js";

const routes = {
  "#/": Home,
  "#/about": About,
};

export async function router() {
  const app = document.getElementById("app");
  const render = routes[location.hash] || routes["#/"];
  app.innerHTML = await render(); // supports async
}
```

✅ Example 2: Async Route (fetch posts)

```js
async function Posts() {
  const res = await fetch(
    "https://jsonplaceholder.typicode.com/posts?_limit=3"
  );
  const posts = await res.json();

  return posts
    .map(
      (post) => `<article><h3>${post.title}</h3><p>${post.body}</p></article>`
    )
    .join("");
}

const routes = {
  "#/": async () => "<h2>Home</h2>",
  "#/posts": Posts,
};

async function router() {
  const app = document.getElementById("app");
  const render = routes[location.hash] || routes["#/"];
  app.innerHTML = await render();
}

window.addEventListener("hashchange", router);
window.addEventListener("load", router);
```

Here:

- The /posts route fetches remote data asynchronously.

- The router can handle both static (Home) and async (Posts) views.

### **16.10 Current Post View**

#### **Explanation**

The Current Post View is the page/screen that shows a single item’s full details after a user clicks it in a list (e.g., a blog post from the posts list).
In an SPA, this usually means:

- The router reads a dynamic route like #/post/123.

- Your app fetches the post by ID from the API.

- It renders the title, date, author, content, image, etc.

- Optionally shows loading, error states, and a Back link.

Key ideas:

- Dynamic route param (:id) → extract it from the URL.

- On-demand fetch → only load the post when the route is visited.

- Stateful UI → show loading, then content (or error).

#### **Real-life use cases**

- Blogs/CMS: Show the full article when a card/title is clicked.

- E-commerce: Product detail page after clicking a product in the catalog.

- Knowledge bases: Article detail view with author, tags, and related links.

- Social apps: Open a single post/thread with comments.

#### **Examples**

A) Minimal vanilla SPA: hash route #/post/:id + JSONPlaceholder

```js
<div id="app"></div>
<script>
  // Small helper
  async function fetchJSON(url) {
    const res = await fetch(url);
    if (!res.ok) throw new Error(`HTTP ${res.status}`);
    return res.json();
  }

  // View: Current Post
  async function PostView(id) {
    const app = document.getElementById("app");
    app.innerHTML = `<p>Loading post…</p>`;

    try {
      // Get the post details
      const post = await fetchJSON(`https://jsonplaceholder.typicode.com/posts/${id}`);
      // (Optional) get the author
      const author = await fetchJSON(`https://jsonplaceholder.typicode.com/users/${post.userId}`);

      app.innerHTML = `
        <article>
          <a href="#/" aria-label="Back">← Back</a>
          <h1>${post.title}</h1>
          <p><em>by ${author.name}</em></p>
          <p>${post.body}</p>
        </article>
      `;
    } catch (err) {
      app.innerHTML = `
        <p role="alert">Could not load the post. ${err.message}</p>
        <a href="#/">Go back</a>
      `;
    }
  }

  // Simple router with dynamic segment: #/post/ID
  async function router() {
    const hash = location.hash || "#/";
    if (hash.startsWith("#/post/")) {
      const id = hash.split("/")[2];     // e.g. "#/post/123" → "123"
      await PostView(id);
      return;
    }
    // Home (list) – placeholder
    document.getElementById("app").innerHTML = `
      <h2>Posts</h2>
      <ul>
        <li><a href="#/post/1">Open post #1</a></li>
        <li><a href="#/post/2">Open post #2</a></li>
      </ul>
    `;
  }

  window.addEventListener("hashchange", router);
  window.addEventListener("load", router);
</script>

```

What to notice:

- The router detects #/post/:id.

- PostView(id) handles loading, fetch, render, error.

- There’s a Back link (#/) to return to the list.

B) WordPress REST API flavor (title + HTML content)

If you’re using WordPress, you usually fetch a post by ID and render content.rendered (already HTML). Use ?\_embed to get author and featured media in one call.

```js
async function WPPostView(id) {
  const app = document.getElementById("app");
  app.innerHTML = `<p>Loading post…</p>`;

  try {
    const res = await fetch(
      `https://example.com/wp-json/wp/v2/posts/${id}?_embed`
    );
    if (!res.ok) throw new Error(`HTTP ${res.status}`);
    const post = await res.json();

    const title = post.title.rendered;
    const contentHTML = post.content.rendered; // already HTML from WP
    const author = post._embedded?.author?.[0]?.name ?? "Unknown";
    const featured = post._embedded?.["wp:featuredmedia"]?.[0]?.source_url;

    app.innerHTML = `
      <article>
        <a href="#/">← Back</a>
        <h1>${title}</h1>
        <p><em>by ${author}</em></p>
        ${featured ? `<img src="${featured}" alt="">` : ""}
        <div>${contentHTML}</div>
      </article>
    `;
  } catch (e) {
    app.innerHTML = `<p role="alert">Could not load the post. ${e.message}</p>`;
  }
}
```

Tips for WordPress:

- Use ?\_embed to avoid multiple requests for author/media.

- The content is trusted HTML from your WP; render carefully if you ever accept user-generated HTML from unknown sources.

Wrap-up: The Current Post View ties together routing, dynamic params, API fetching, and stateful UI to show a single item’s full details—exactly what users expect when they click a list item in your SPA.

### **16.11 Internal Search**

#### **Explanation**

Internal Search means allowing users to search inside your SPA’s content, without leaving the app.

- It usually works by capturing the query (from an <input> or search bar).

- Then the app sends a request to the API with that query (e.g., ?search=keyword) or - filters existing data in memory.

- The router updates the view (e.g., #/search/javascript).

- The results are shown dynamically, without a full page reload.

Key ideas:

- Capture search text from user.

- Update the SPA’s route (so you can share/bookmark search results).

- Fetch results from API (or filter cached ones).

- Render them as a list of clickable items (leading to detail views).

#### **Real-life use cases**

- Blog / CMS: Search articles by keyword.

- E-commerce: Search products by name or description.

- Docs site: Search topics, functions, or keywords.

- Streaming platform: Search for movies or shows.

#### **Examples**

A) Simple SPA search with JSONPlaceholder

We’ll build a fake blog search.

```js
<div id="app"></div>
<script>
  async function fetchJSON(url) {
    const res = await fetch(url);
    if (!res.ok) throw new Error(`HTTP ${res.status}`);
    return res.json();
  }

  // Internal Search View
  async function SearchView(query) {
    const app = document.getElementById("app");
    app.innerHTML = `<p>Searching for "${query}"…</p>`;

    try {
      // JSONPlaceholder doesn’t support real search → simulate
      const posts = await fetchJSON("https://jsonplaceholder.typicode.com/posts");
      const results = posts.filter(p =>
        p.title.includes(query) || p.body.includes(query)
      );

      if (!results.length) {
        app.innerHTML = `<p>No results found for "${query}".</p>`;
        return;
      }

      app.innerHTML = `
        <h2>Results for "${query}"</h2>
        <ul>
          ${results.map(r => `<li><a href="#/post/${r.id}">${r.title}</a></li>`).join("")}
        </ul>
      `;
    } catch (err) {
      app.innerHTML = `<p>Error: ${err.message}</p>`;
    }
  }

  // Router
  async function router() {
    const hash = location.hash || "#/";
    const app = document.getElementById("app");

    if (hash.startsWith("#/search/")) {
      const query = decodeURIComponent(hash.split("/")[2]);
      await SearchView(query);
      return;
    }

    // Home: show search bar
    app.innerHTML = `
      <h2>Search Posts</h2>
      <input id="searchInput" placeholder="Type a keyword..." />
      <button id="searchBtn">Search</button>
    `;

    document.getElementById("searchBtn").onclick = () => {
      const value = document.getElementById("searchInput").value.trim();
      if (value) location.hash = `#/search/${encodeURIComponent(value)}`;
    };
  }

  window.addEventListener("hashchange", router);
  window.addEventListener("load", router);
</script>

```

What happens:

- The Home screen shows a search bar.

- When you search, it navigates to #/search/keyword.

- Router triggers SearchView(query).

- Results are listed as links to individual post views.

B) WordPress REST API example

WordPress has built-in search with ?search=query.

```js
async function WPSearchView(query) {
  const app = document.getElementById("app");
  app.innerHTML = `<p>Searching for "${query}"…</p>`;

  try {
    const res = await fetch(
      `https://example.com/wp-json/wp/v2/posts?search=${query}`
    );
    if (!res.ok) throw new Error(`HTTP ${res.status}`);
    const results = await res.json();

    if (!results.length) {
      app.innerHTML = `<p>No results found for "${query}".</p>`;
      return;
    }

    app.innerHTML = `
      <h2>Results for "${query}"</h2>
      <ul>
        ${results
          .map(
            (r) => `
          <li><a href="#/post/${r.id}">${r.title.rendered}</a></li>
        `
          )
          .join("")}
      </ul>
    `;
  } catch (e) {
    app.innerHTML = `<p>Error: ${e.message}</p>`;
  }
}
```

✅ Wrap-up: Internal Search connects a query input to the API (or cached data), integrates with the router, and dynamically displays results—all without reloading the page.

### **16.12 Current Search View**

#### **Explanation**

After implementing Internal Search, the Current Search View is the screen where you actually display the search results for the query.

- It’s like a “results page” in your SPA.

- Triggered by a route (e.g., #/search/javascript).

- It fetches results from the API (or filters cached data).

- Shows them dynamically (list, grid, cards, etc.).

- Each result often links to a detail view (e.g., #/post/23).

In other words:

- Internal Search = capturing the user’s query.

- Current Search View = showing the results for that query.

#### **Real-life use cases**

- Google Search results page → “current search view” of your query.

- E-commerce site: Search “laptop” → you get a page with a list of laptops.

- Blog: Search “JavaScript” → list of articles that match.

- Streaming app: Search “Batman” → shows all Batman-related movies.

#### **Examples**

A) Using JSONPlaceholder

```js
<div id="app"></div>

<script>
  async function fetchJSON(url) {
    const res = await fetch(url);
    if (!res.ok) throw new Error(`HTTP ${res.status}`);
    return res.json();
  }

  // Current Search View
  async function CurrentSearchView(query) {
    const app = document.getElementById("app");
    app.innerHTML = `<p>Loading results for "${query}"...</p>`;

    try {
      // Fake search simulation with JSONPlaceholder
      const posts = await fetchJSON("https://jsonplaceholder.typicode.com/posts");
      const results = posts.filter(p =>
        p.title.includes(query) || p.body.includes(query)
      );

      app.innerHTML = `
        <h2>Results for "${query}"</h2>
        ${
          results.length
            ? `<ul>${results.map(r => `<li><a href="#/post/${r.id}">${r.title}</a></li>`).join("")}</ul>`
            : `<p>No results found.</p>`
        }
      `;
    } catch (err) {
      app.innerHTML = `<p>Error: ${err.message}</p>`;
    }
  }

  // Router
  async function router() {
    const hash = location.hash || "#/";
    const app = document.getElementById("app");

    if (hash.startsWith("#/search/")) {
      const query = decodeURIComponent(hash.split("/")[2]);
      await CurrentSearchView(query);
      return;
    }

    app.innerHTML = `
      <h2>Search Posts</h2>
      <input id="searchInput" placeholder="Type something..." />
      <button id="searchBtn">Search</button>
    `;

    document.getElementById("searchBtn").onclick = () => {
      const value = document.getElementById("searchInput").value.trim();
      if (value) location.hash = `#/search/${encodeURIComponent(value)}`;
    };
  }

  window.addEventListener("hashchange", router);
  window.addEventListener("load", router);
</script>

```

What happens here:

- On the home screen, you type a keyword.

- It navigates to #/search/keyword.

- CurrentSearchView(query) is called.

- Results are displayed dynamically.

B) WordPress REST API

```js
async function CurrentSearchView(query) {
  const app = document.getElementById("app");
  app.innerHTML = `<p>Searching "${query}"...</p>`;

  try {
    const res = await fetch(
      `https://example.com/wp-json/wp/v2/posts?search=${query}`
    );
    const posts = await res.json();

    app.innerHTML = `
      <h2>Results for "${query}"</h2>
      ${
        posts.length
          ? `<ul>${posts
              .map(
                (p) =>
                  `<li><a href="#/post/${p.id}">${p.title.rendered}</a></li>`
              )
              .join("")}</ul>`
          : `<p>No posts found.</p>`
      }
    `;
  } catch (err) {
    app.innerHTML = `<p>Error: ${err.message}</p>`;
  }
}
```

### **16.13 Infinite Scroll & Higher-Order Components**

#### **Explanation**

This part of the syllabus has two ideas combined:

Infinite Scroll

- Instead of showing pagination buttons (Next / Previous), content loads automatically when the user scrolls near the bottom of the page.

- It’s a modern alternative to pagination (like how Instagram, Twitter, or Facebook load more posts as you scroll).

Higher-Order Components (HOCs) in Vanilla JS

- A pattern (borrowed from React) where you create a function/component that wraps another component and adds extra behavior.

- In this context, you build a reusable function to “wrap” your components with infinite scroll behavior.

So:

- Infinite Scroll = loading more data automatically.

- HOC = reusable logic to apply infinite scroll to different views.

#### **Real-life use cases**

- Social media apps: Twitter, TikTok, Facebook, Instagram feed → infinite scrolling.

- E-commerce sites: products load as you scroll instead of clicking "Next page".

- News apps/blogs: keep loading articles until the user stops.

- Reusable behavior: HOCs make it easy to apply this logic to multiple parts of your SPA without rewriting code.

#### **Examples**

1. Simple Infinite Scroll with scroll event

```js
let page = 1;

async function loadPosts() {
  const res = await fetch(
    `https://jsonplaceholder.typicode.com/posts?_limit=5&_page=${page}`
  );
  const posts = await res.json();

  const container = document.getElementById("posts");
  posts.forEach((post) => {
    const div = document.createElement("div");
    div.innerHTML = `<h3>${post.title}</h3><p>${post.body}</p>`;
    container.appendChild(div);
  });
}

window.addEventListener("scroll", () => {
  if (window.innerHeight + window.scrollY >= document.body.offsetHeight - 50) {
    page++;
    loadPosts();
  }
});

// Load first posts
loadPosts();
```

👉 This listens for the scroll event, and when the user reaches the bottom, it fetches more data.

2. Infinite Scroll with IntersectionObserver (better way)

```js
let page = 1;
const sentinel = document.getElementById("sentinel");

async function loadPosts() {
  const res = await fetch(
    `https://jsonplaceholder.typicode.com/posts?_limit=5&_page=${page}`
  );
  const posts = await res.json();

  const container = document.getElementById("posts");
  posts.forEach((post) => {
    const div = document.createElement("div");
    div.innerHTML = `<h3>${post.title}</h3><p>${post.body}</p>`;
    container.appendChild(div);
  });
}

const observer = new IntersectionObserver((entries) => {
  if (entries[0].isIntersecting) {
    page++;
    loadPosts();
  }
});

observer.observe(sentinel);

// Initial load
loadPosts();
```

👉 Here, we place a hidden <div id="sentinel"> at the bottom. When it becomes visible, more posts are loaded.

3. Higher-Order Component (HOC) for Infinite Scroll

Instead of coding infinite scroll in every view, you create a wrapper:

```js
function withInfiniteScroll(componentFn) {
  let page = 1;
  const sentinel = document.getElementById("sentinel");

  async function loadMore() {
    await componentFn(page); // call the original component logic
    page++;
  }

  const observer = new IntersectionObserver((entries) => {
    if (entries[0].isIntersecting) loadMore();
  });

  observer.observe(sentinel);

  loadMore(); // load first page
}
```

Usage with a posts component:

```js
async function PostsComponent(page) {
  const res = await fetch(
    `https://jsonplaceholder.typicode.com/posts?_limit=5&_page=${page}`
  );
  const posts = await res.json();

  const container = document.getElementById("posts");
  posts.forEach((post) => {
    const div = document.createElement("div");
    div.innerHTML = `<h3>${post.title}</h3><p>${post.body}</p>`;
    container.appendChild(div);
  });
}

// Wrap PostsComponent with infinite scroll
withInfiniteScroll(PostsComponent);
```

### **16.14 Styled Components & Single File Components**

#### **Explanation**

This step introduces two important concepts for organizing and styling your SPA:

Styled Components (in Vanilla JS context)

- A pattern where you define component-specific styles directly in JavaScript, so the styles are tightly coupled with the component they belong to.

- Prevents global CSS conflicts and makes styles easier to manage.

- Similar to how React’s styled-components library works, but we can mimic it in plain JS.

Single File Components (SFCs)

- A structure where HTML, CSS, and JS for a component live together in one file.

- Keeps everything about that component modular and self-contained.

- Inspired by frameworks like Vue.js and Svelte, but in this SPA, you’ll organize files manually.

#### **Real-life use cases**

- Avoiding CSS conflicts: If you have many components, you don’t want styles from one to accidentally affect another.

- Scalability: In large SPAs, Single File Components help organize the project, making it easier for teams to work on different parts.

- Modern UI design: Styled Components let you write dynamic styles (e.g., based on props or state).

#### **Examples**

1. Styled Components in Vanilla JS

```js
function Button(label, color = "blue") {
  const btn = document.createElement("button");
  btn.textContent = label;

  // Component-specific styles
  btn.style.backgroundColor = color;
  btn.style.color = "white";
  btn.style.padding = "10px 20px";
  btn.style.border = "none";
  btn.style.borderRadius = "8px";
  btn.style.cursor = "pointer";

  return btn;
}

// Usage
document.body.appendChild(Button("Click Me!", "green"));
```

👉 Each button instance has its own encapsulated styles, so you don’t need global CSS rules.

2. Single File Component (manual SPA style)

Imagine you create a folder components/ and store each component in its own file.

📄 Header.js

```js
export function Header() {
  const header = document.createElement("header");
  header.innerHTML = `
    <style>
      header {
        background: #333;
        color: white;
        padding: 1rem;
        text-align: center;
      }
    </style>
    <h1>My SPA</h1>
  `;
  return header;
}
```

📄 App.js

```js
import { Header } from "./components/Header.js";

document.getElementById("app").appendChild(Header());
```

👉 Here, the HTML, CSS, and JS are bundled together in one file, so the component is self-contained.

3. Combining Styled + SFC

You can even combine both:

Write dynamic styles in JS (Styled Components).

Keep everything (structure + style + logic) inside one file (SFC).

Example:
📄 Card.js

```js
export function Card(title, desc) {
  const card = document.createElement("div");
  card.classList.add("card");

  card.innerHTML = `
    <style>
      .card {
        border: 1px solid #ccc;
        border-radius: 10px;
        padding: 15px;
        margin: 10px;
        box-shadow: 2px 2px 6px rgba(0,0,0,0.1);
      }
      .card h2 {
        margin: 0 0 10px;
        color: #333;
      }
    </style>
    <h2>${title}</h2>
    <p>${desc}</p>
  `;

  return card;
}
```

Usage:

```js
import { Card } from "./components/Card.js";
document
  .getElementById("app")
  .appendChild(Card("Hello!", "This is a styled card."));
```

## **17. Reactivity**

### **17.1 Reactivity Introduction**

#### **Explanation**

Reactivity is a programming pattern where the UI automatically updates when your data (state) changes. Instead of manually finding DOM elements and changing them every time something changes, you change the data and the UI reacts for you.

Core ideas:

- State: a single source of truth (an object that holds app data).

- Reactive layer: watches the state for changes and triggers updates (re-render or patch).

- Techniques to implement reactivity: Proxy / Object.defineProperty, observable patterns (event emitters), or frameworks (Vue, React, Svelte) that provide their own reactive systems.

- Benefits: less boilerplate, fewer DOM bugs, clearer separation between data and view.

#### **Real-life use cases**

- A counter or live stats widget that updates automatically.

- Forms with live preview (markdown editor shows HTML as you type).

- Search/filter UIs where results update as you type.

- Dashboards with real-time metrics (stock tickers, analytics).

- Two-way binding (form inputs keep state and UI in sync).

- Component libraries where changing a prop updates the component automatically.

#### **Examples**

A — Non-reactive (manual DOM updates)

```js
<div id="app">
  <p id="count">Count: 0</p>
  <button id="inc">+1</button>
</div>

<script>
const countEl = document.getElementById("count");
const btn = document.getElementById("inc");
let count = 0;

btn.addEventListener("click", () => {
  count += 1;
  // MANUAL update of the DOM every time
  countEl.textContent = "Count: " + count;
});
</script>

```

Every change requires explicit DOM manipulation (countEl.textContent = ...).

B — Simple reactive approach using Proxy (modern, compact)

```js
<div id="app">
  <p id="count"></p>
  <button id="inc">+1</button>
</div>

<script>
const app = document.getElementById("app");
const countEl = document.getElementById("count");

const state = { count: 0 };

function render() {
  countEl.textContent = `Count: ${state.count}`;
}

// Create a Proxy that calls render() whenever a property is set
const reactive = new Proxy(state, {
  set(target, prop, value) {
    target[prop] = value;
    // simple synchronous update — in real apps you might batch updates
    render();
    return true;
  }
});

// initial render
render();

// Interact with reactive state
document.getElementById("inc").addEventListener("click", () => {
  reactive.count += 1; // triggers Proxy -> render()
});
</script>

```

You update reactive.count and the UI updates automatically — no manual DOM calls at each place.

C — Older approach with Object.defineProperty

```js
const state = {};
let internalCount = 0;

Object.defineProperty(state, "count", {
  get() {
    return internalCount;
  },
  set(val) {
    internalCount = val;
    render(); // called when state.count changed
  },
});

function render() {
  document.getElementById("count").textContent = `Count: ${state.count}`;
}
```

Works in older environments (pre-Proxy). More verbose and less flexible than Proxy.

D — Observable / Event-emitter pattern (explicit notify)

```js
const store = {
  state: { count: 0 },
  listeners: [],
  setCount(v) {
    this.state.count = v;
    this.listeners.forEach((fn) => fn(this.state));
  },
  subscribe(fn) {
    this.listeners.push(fn);
  },
};

store.subscribe((s) => {
  document.getElementById("count").textContent = `Count: ${s.count}`;
});

document.getElementById("inc").addEventListener("click", () => {
  store.setCount(store.state.count + 1);
});
```

More explicit: you call setCount() which notifies subscribers.

Performance notes & best practices

- Naive re-rendering can be expensive. Real frameworks use diffing or DOM patching to update only what changed.

- Batching updates (microtask / requestAnimationFrame) avoids too many reflows.

- For large apps, combine reactivity with immutable state patterns and selective rendering to keep updates fast.

### **17.2 Non-Reactive DOM Manipulation**

#### **Explanation**

Non-Reactive DOM Manipulation is the traditional way of updating the DOM manually, without any automatic “reactivity” layer.

- You directly select elements using document.querySelector or getElementById.

- Then you update properties, content, or attributes when needed.

- Changes do not automatically propagate—you must explicitly update the DOM each time your data changes.

- Works in plain JavaScript, but can become messy and repetitive for dynamic apps.

Key point: In non-reactive approaches, your data and the UI are not synchronized automatically.

#### **Real-life use cases**

- Small static websites where content rarely changes.

- Simple forms, buttons, or modals that only need one-time updates.

- Legacy applications built before modern reactive frameworks existed.

- When you want full control over DOM updates and don’t need automatic binding.

#### **Examples**

A — Updating text manually

```js
<div id="counter">Count: 0</div>
<button id="inc">+1</button>

<script>
let count = 0;
const counter = document.getElementById("counter");
const button = document.getElementById("inc");

button.addEventListener("click", () => {
  count += 1;
  counter.textContent = "Count: " + count; // MANUAL DOM update
});
</script>

```

Each click requires a manual update to the element.

If you have multiple elements showing count, you need to update all of them manually.

B — Changing attributes manually

```js
<img id="photo" src="photo1.jpg" alt="Photo 1">
<button id="next">Next Photo</button>

<script>
const photos = ["photo1.jpg", "photo2.jpg", "photo3.jpg"];
let index = 0;

const img = document.getElementById("photo");
document.getElementById("next").addEventListener("click", () => {
  index = (index + 1) % photos.length;
  img.src = photos[index]; // MANUAL DOM update
});
</script>

```

You have to manually update img.src every time.

No automatic syncing between data (index) and UI.

C — Form input handling manually

```js
<input type="text" id="nameInput" placeholder="Enter name">
<p id="greeting"></p>

<script>
const input = document.getElementById("nameInput");
const greeting = document.getElementById("greeting");

input.addEventListener("input", () => {
  greeting.textContent = "Hello, " + input.value; // MANUAL update
});
</script>

```

Every keystroke triggers a manual DOM update.

Works, but if your app has lots of bindings, this becomes repetitive.

### **17.3 UI Based on State**

#### **Explanation**

UI Based on State is a concept where your interface (UI) is rendered according to the current data or “state” of your application.

- The state is a JavaScript object that represents the app’s current data.

- When the state changes, the UI re-renders to reflect the new data.

- This is the foundation of reactive programming in modern SPAs.

- You don’t manually update each DOM element—the UI depends on the state.

Key idea: The state is the single source of truth. The UI is a function of that state.

#### **Real-life use cases**

- Counters or counters with multiple displays.

- Todo apps where the list updates when items are added or removed.

- Shopping carts where quantity and total price update automatically.

- Dashboards where metrics, graphs, or charts update based on state changes.

- Forms with dynamic previews (e.g., a live markdown editor).

#### **Examples**

A — Simple counter based on state

```js
<div id="app">
  <p id="count"></p>
  <button id="inc">+1</button>
  <button id="dec">-1</button>
</div>

<script>
const state = { count: 0 };

function render() {
  document.getElementById("count").textContent = `Count: ${state.count}`;
}

document.getElementById("inc").addEventListener("click", () => {
  state.count += 1;
  render(); // UI updates automatically based on new state
});

document.getElementById("dec").addEventListener("click", () => {
  state.count -= 1;
  render();
});

// Initial render
render();
</script>

```

B — Todo list example

```js
<ul id="todoList"></ul>
<input id="todoInput" placeholder="New task">
<button id="addTodo">Add</button>

<script>
const state = { todos: [] };

function render() {
  const list = document.getElementById("todoList");
  list.innerHTML = ""; // clear previous items
  state.todos.forEach((todo, index) => {
    const li = document.createElement("li");
    li.textContent = todo;
    list.appendChild(li);
  });
}

document.getElementById("addTodo").addEventListener("click", () => {
  const input = document.getElementById("todoInput");
  if (input.value.trim()) {
    state.todos.push(input.value.trim());
    input.value = "";
    render(); // update UI based on new state
  }
});

// Initial render
render();
</script>

```

### **17.4 Reactive State**

#### **Explanation**

Reactive State is an improvement over the “UI Based on State” pattern.

- Instead of manually calling a render function every time state changes, the UI updates automatically when the state changes.

- Achieved using modern JavaScript tools like Proxy, Object.defineProperty, or reactive libraries/frameworks (Vue, Svelte).

- You don’t need to call render() manually; the system “reacts” to changes in the state.

Key idea: State is reactive, meaning that changes propagate automatically to the UI.

#### **Real-life use cases**

- Live counters that update multiple places in the UI.

- Forms with live preview (e.g., Markdown editor).

- Dynamic dashboards with charts and metrics updating automatically.

- Shopping carts: quantity, subtotal, and total update automatically when items change.

- Any SPA feature where data changes frequently and the UI must reflect those changes instantly.

#### **Examples**

A — Reactive counter using Proxy

```js
<div>
  <p id="countDisplay">Count: 0</p>
  <button id="inc">+1</button>
</div>

<script>
// State object
const state = { count: 0 };

// Proxy to make state reactive
const reactiveState = new Proxy(state, {
  set(target, key, value) {
    target[key] = value;
    document.getElementById("countDisplay").textContent = `Count: ${target.count}`;
    return true;
  }
});

// Event listener updates reactive state
document.getElementById("inc").addEventListener("click", () => {
  reactiveState.count += 1; // automatically updates UI
});
</script>

```

No need to call render() manually.

Changing reactiveState.count triggers the UI update automatically.

B — Reactive todo list

```js
<ul id="todoList"></ul>
<input id="todoInput" placeholder="New task">
<button id="addTodo">Add</button>

<script>
const state = { todos: [] };

// Reactive proxy
const reactiveState = new Proxy(state, {
  set(target, prop, value) {
    target[prop] = value;
    const list = document.getElementById("todoList");
    list.innerHTML = "";
    target.todos.forEach(todo => {
      const li = document.createElement("li");
      li.textContent = todo;
      list.appendChild(li);
    });
    return true;
  }
});

document.getElementById("addTodo").addEventListener("click", () => {
  const input = document.getElementById("todoInput");
  if (input.value.trim()) {
    reactiveState.todos.push(input.value.trim()); // UI updates automatically
    input.value = "";
  }
});
</script>

```

State changes propagate automatically

### **17.5 Immutable State**

#### **Explanation**

Immutable State means that you never directly modify the existing state object. Instead, you create a new version of the state whenever it changes.

- This helps prevent bugs from accidental state mutations.

- Makes state tracking, debugging, and undo/redo features easier.

- Widely used in modern frameworks (React, Redux) because predictable state changes simplify re-rendering.

Key idea: Treat state like a snapshot — when something changes, create a new snapshot, don’t modify the old one.

#### **Real-life use cases**

- Redux or similar state management: all state changes are immutable.

- Undo/redo systems: keeping previous states intact.

- Optimized re-rendering: frameworks can detect differences between old and new state efficiently.

- Collaborative apps (like Google Docs clones): immutable snapshots help merge changes.-

#### **Examples**

A — Counter with immutable state

```js
let state = { count: 0 };

function setState(newState) {
  state = { ...state, ...newState }; // create new object
  render();
}

function render() {
  document.getElementById("countDisplay").textContent = `Count: ${state.count}`;
}

document.getElementById("inc").addEventListener("click", () => {
  setState({ count: state.count + 1 }); // old state is not mutated
});

// Initial render
render();
```

state is replaced, not modified.

Spread operator (...state) copies previous properties.

B — Todo list with immutable updates

```js
let state = { todos: [] };

function setState(newState) {
  state = { ...state, ...newState };
  render();
}

function render() {
  const list = document.getElementById("todoList");
  list.innerHTML = "";
  state.todos.forEach((todo) => {
    const li = document.createElement("li");
    li.textContent = todo;
    list.appendChild(li);
  });
}

document.getElementById("addTodo").addEventListener("click", () => {
  const input = document.getElementById("todoInput");
  if (input.value.trim()) {
    // create a NEW array instead of mutating the old one
    setState({ todos: [...state.todos, input.value.trim()] });
    input.value = "";
  }
});
```

The array state.todos is replaced with a new array, keeping previous snapshots intact.

Safer than state.todos.push(), especially in complex apps.

### **17.6 Components with State**

#### **Explanation**

Components with State means building UI pieces (components) that manage their own state.

- Each component can have internal data that determines how it renders.

- Changes to the component’s state automatically update its UI if you’re using a reactive system.

- State is local to the component, but components can also communicate with parent/child components.

- This is the foundation of modern frontend development (React, Vue, Svelte, etc.).

Key idea: Components = reusable UI blocks + their own state + behavior.

#### **Real-life use cases**

- Counters or toggles inside a dashboard widget.

- Forms with live input validation.

- Todo items that can mark themselves completed.

- Tabs or modals that maintain their open/close state.

- Dynamic cards that update independently when data changes.

#### **Examples**

A — Counter component (vanilla JS)

```js
<div id="counterComponent"></div>

<script>
function CounterComponent(root) {
  let state = { count: 0 };

  const container = document.createElement("div");
  const display = document.createElement("p");
  const incBtn = document.createElement("button");

  display.textContent = `Count: ${state.count}`;
  incBtn.textContent = "+1";

  container.appendChild(display);
  container.appendChild(incBtn);
  root.appendChild(container);

  function render() {
    display.textContent = `Count: ${state.count}`;
  }

  incBtn.addEventListener("click", () => {
    state.count += 1;
    render(); // update only this component
  });
}

CounterComponent(document.getElementById("counterComponent"));
</script>

```

Component has its own state (state.count).

UI updates when the component state changes, independent of other components.

B — Todo Item Component

```js
function TodoItemComponent(todoText, root) {
  let state = { done: false };

  const li = document.createElement("li");
  const checkbox = document.createElement("input");
  checkbox.type = "checkbox";
  li.textContent = todoText;
  li.prepend(checkbox);
  root.appendChild(li);

  checkbox.addEventListener("change", () => {
    state.done = checkbox.checked;
    li.style.textDecoration = state.done ? "line-through" : "none";
  });
}

const ul = document.createElement("ul");
document.body.appendChild(ul);

TodoItemComponent("Learn JS", ul);
TodoItemComponent("Build project", ul);
```

Each Todo item manages its own state (done).

Changing one item doesn’t affect others, but each reacts independently.

### **17.7 Component Library**

#### **Explanation**

A Component Library is a collection of reusable UI components that you can use across your project or even multiple projects.

- Components are pre-built, self-contained, and often configurable.

- They help maintain consistency in design and behavior.

- Libraries can be internal (created by your team) or external (like Bootstrap, Material UI, or Tailwind UI).

- Components in a library usually handle state, events, and rendering internally, so developers don’t have to rewrite them every time.

Key idea: Think of it as a toolbox of pre-made building blocks for your UI.

#### **Real-life use cases**

- Button, Input, Modal, Dropdown components reused throughout an app.

- Card components for displaying products, articles, or user info.

- Navigation bars or side menus that appear in multiple pages.

- Form controls (checkboxes, radio buttons, sliders) with consistent styling and behavior.

- Any project where you want reusable and maintainable UI.

#### **Examples**

A — Simple Button Component

```js
function Button({ text, onClick, color = "blue" }) {
  const btn = document.createElement("button");
  btn.textContent = text;
  btn.style.backgroundColor = color;
  btn.addEventListener("click", onClick);
  return btn;
}

// Usage
document.body.appendChild(
  Button({
    text: "Click me",
    onClick: () => alert("Hello!"),
    color: "green",
  })
);
```

Reusable and configurable: you can create multiple buttons with different text, colors, or actions.

B — Card Component

```js
function Card({ title, description }) {
  const card = document.createElement("div");
  card.style.border = "1px solid #ccc";
  card.style.padding = "10px";
  card.style.margin = "5px";

  const h3 = document.createElement("h3");
  h3.textContent = title;
  const p = document.createElement("p");
  p.textContent = description;

  card.appendChild(h3);
  card.appendChild(p);

  return card;
}

// Usage
const root = document.getElementById("cards");
root.appendChild(
  Card({ title: "JS Basics", description: "Learn JS fundamentals" })
);
root.appendChild(
  Card({ title: "React", description: "Build components and apps" })
);
```

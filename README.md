# 100 Must-Know Javascript Interview Questions with Answers in 2025

You can also find me on Instagram for all such technical content: [@misstechie15](https://www.instagram.com/misstechie15/)

### JavaScript Basics
<br>
## 1. What is JavaScript?<br>
 Ans: JavaScript is a lightweight, interpreted programming language primarily used to create
   interactive and dynamic content on web pages.
<br>

## 2. What are the different data types in JavaScript?<br>
 Ans: Primitive types: String, Number, Boolean, Undefined, Null, BigInt, Symbol<br>
   Non-primitive types: Objects (including Arrays, Functions, etc.)
<br>

## 3. What is the difference between var, let, and const?<br>
 Ans: var: Function-scoped, can be redeclared and updated.<br>
   let: Block-scoped, cannot be redeclared, but can be updated.<br>
   const: Block-scoped, cannot be redeclared or updated.
<br>

## 4. What are template literals?<br>
Ans:  Template literals use backticks (`) and allow embedding expressions using ${expression}.
   Example:`Hello, ${name}!`.
<br />

## 5. What is the difference between == and ===?<br>
Ans:  ==: Compares values with type coercion.<br>
      ===: Compares values without type coercion.
<br>

### JavaScript Functions 
<br>
## 6. What are arrow functions?<br>
Ans: Arrow functions provide a concise syntax for writing functions. They don’t bind their context.<br>

## 7. What is the difference between function declaration and function expression?
Ans: Function declaration: Defined with the function keyword. Example: function greet(){}.<br>
     Function expression: Assigned to a variable. Example: const greet = function() {};.<br>

## 8. What is a callback function?<br>
Ans: A function passed as an argument to another function and executed after the completion of
that function.<br>

## 9: What is a pure function?<br>
Ans: A pure function always produces the same output for the same input and has no side effects.<br>

## 10. What is the purpose of closures?<br>
Ans: Closures allow a function to access variables from its outer scope even after the outer
function has been executed.<br>

### Advanced JavaScript <br>
## 11. What is the difference between null and undefined? <br>
Ans: null: Explicitly set to indicate "no value."<br>
     undefined: A variable has been declared but not assigned a value.<br>

## 12. What are JavaScript promises?<br>
Ans: Promises represent a value that may be available now, in the future, or never . They can be in
one of three states: pending, fulfilled, or rejected.<br>

## 13. What is async/await?<br>
Ans: It is a syntax for handling asynchronous code, making it look synchronous and easier to read.<br>

## 14. What are higher-order functions?<br>
Ans: Functions that can take other functions as arguments or return them.<br>

## 15. What is the difference between call, apply, and bind?<br>
Ans: call: Invokes a function with a specified context and arguments passed individually.<br>
     apply: Similar to a call but takes arguments as an array.<br>
     bind: Returns a new function with this bound to a specified object.<br>

### DOM Manipulation <br>
## 16. How can you select elements in the DOM?<br>
Ans: getElementById()<br>
     getElementsByClassName()<br>
     getElementsByTagName()<br>
     querySelector()<br>
     querySelectorAll()<br>

## 17. What is the difference between a window and a document?<br>
Ans: window: Represents the browser window and global context.<br>
     document: Represents the DOM (content of the web page).<br>

## 18. What is the purpose of addEventListener?<br>
Ans: It adds an event handler to an element without overwriting existing handlers.<br>

## 19. How do you create a DOM element in JavaScript?<br>
Ans: Using document.createElement() and appending it to the DOM using methods like
appendChild.<br>

## 20. What is event delegation?<br>
Ans: Attaching a single event listener to a parent element to manage events for child elements.<br>

### DOM Manipulation <br>
# 21. What are rest and spread operators?<br>
Ans: Rest (...args): Collects arguments into an array.<br>
     Spread (...array): Spreads elements of an array/object.

# 22. What are JavaScript modules?<br>
Ans: Modules allow code to be divided into reusable chunks using import and export.<br>

# 23. What is destructuring?<br>
Ans: A syntax to extract values from arrays or objects into variables.<br>

# 24. What are generators?<br>
Ans: Functions that can pause execution (yield) and resume later, returning an iterator .<br>

# 25. What is the difference between Map and WeakMap?<br>
Ans: Map: Stores key-value pairs. Keys can be any type.<br>
     WeakMap: Keys must be objects, and they are weakly referenced.<br>

### JavaScript Objects and Prototypes<br>
# 26. What is the difference between an object and a Map in JavaScript?<br>
Ans:  Object: Keys are strings or symbols, unordered.<br>
      Map: Keys can be any type and maintain insertion order .<br>

# 27. What is prototypal inheritance?<br>
Ans: Prototypal inheritance allows objects to inherit properties and methods from another object.<br>

# 28. What is the Object.create() method?<br>
Ans: It creates a new object with the specified prototype object and properties.<br>

# How do you clone an object in JavaScript?<br>
Ans: Using Object.assign({}, obj)<br>
     Using the spread operator: { ...obj }<br>

# 30. What is a JavaScript class?<br>
Ans: Classes are syntactic sugar over JavaScript’s prototype-based inheritance to define
constructors and methods.<br>

### Error Handling<br>
# 31. What is the purpose of try...catch in JavaScript?<br>
Ans: It handles exceptions by running the code inside try and executing catch if an error occurs.<br>

# 32. What is the final block used for?<br>
Ans: It executes code after try and catch, regardless of the outcome.<br>

# 33. How can you create a custom error in JavaScript?<br>
Ans: By using the Error class:throw new Error('Custom error message');<br>

# 34. What is the error event in JavaScript?<br>
Ans: It is triggered when a runtime error occurs in the script.<br>

# 35. How can you handle asynchronous errors?<br>
Ans: By using .catch() for Promises or try...catch with async/await.<br>

### Asynchronous JavaScript<br>
# 36. What is the event loop in JavaScript?<br>
Ans: It is a mechanism that handles the execution of multiple tasks, including callbacks and
asynchronous code.<br>

# 37. What is the difference between microtasks and microtasks?<br>
Ans: Microtasks: Processed before microtasks, e.g., Promises.<br>
     Macrotasks: These include tasks like setTimeout and setInterval.<br>

# 38. How does setTimeout work in JavaScript?<br>
Ans: It schedules a task to run after a specified delay.<br>

# 39. What is Promise? All?<br>
Ans: It resolves when all promises passed as an array are resolved or rejected when any promise
fails.<br>

# 40. What is the purpose of Promise? Race?<br>
Ans: It resolves or rejects as soon as any one of the promises in the array is resolved or rejected .<br>

### JavaScript Arrays<br>
# 41. What are the different ways to iterate over an array?<br>
Ans: for loop<br>
     forEach()<br>
     map()<br>
     for ...of loop<br>

# 42. What is the difference between map() and forEach()?<br>
Ans: map(): Creates a new array with the results of calling a function.<br>
     forEach(): Executes a function on each array element without returning a new array.<br>

# 43. What is the use of reduce() in JavaScript?<br>
Ans: It reduces an array to a single value by applying a function on each element.<br>

# 44. What is the purpose of Array.from()?<br>
Ans: It creates a new array from array-like or iterable objects.<br>

# 45. How do you remove duplicates from an array?<br>
Ans: Using Set: [...new Set(array)];<br>

### Memory and Performance<br>
# 46. What is a memory leak in JavaScript?<br>
Ans: It occurs when memory that is no longer needed is not released, e.g., unused variables with
global references.<br>

# 47. What is garbage collection?<br>
Ans: The process of automatically reclaiming memory by removing objects that are no longer in
use.<br>

# 48. What is the difference between deep copy and shallow copy?<br>
Ans: Shallow copy: Only top-level properties are copied.<br>
     Deep copy: All levels of properties are copied recursively.<br>

# 49. How do you optimise JavaScript performance?<br>
Ans: Minimize DOM access<br>
     Use requestAnimationFrame for animations<br>
     Debounce or throttle events<br>
     Use asynchronous code effectively.<br>

# 50. What are web workers in JavaScript?<br>
Ans: Web Workers allow you to run JavaScript in the background, parallel to the main thread.<br>

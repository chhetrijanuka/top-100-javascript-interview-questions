# 100 Must-Know Javascript Interview Questions with Answers in 2025

You can also find me on Instagram for all such technical content: [@misstechie15](https://www.instagram.com/misstechie15/)

## JavaScript Basics

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

## JavaScript Functions 
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

## Advanced JavaScript <br>

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

## DOM Manipulation <br>

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

## ES6+ Features <br>

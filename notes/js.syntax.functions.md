---
id: t04qd5lkr9qhmmaok9ek8if
title: Functions
desc: ''
updated: 1738187350454
created: 1735912593406
---

<!--#region styles-->
<style>
    * { font-size: 18px; }
    h1 {
        color: red;
        font-weight: bold;
        border-bottom: 2px solid red; 
        font-family: 'Algerian';
        text-align: center;
        font-size: 2em;
    }
    h2 { 
        color: crimson; 
        font-weight: bold;
        font-family: 'Algerian'; 
        border-bottom: 2px solid crimson;
        font-size: 1.5em;
    }
    h3 { 
        color: rgb(255, 0, 127);
        font-weight: bold;
        text-decoration: underline;
        font-size: 1.2em;
        font-size: 1.2em;
    }
    h4 { 
        color: rgb(0, 255, 255);
        font-weight: bold;
        text-decoration: underline;
        font-size: 1em; 
    }
    h5 { 
        color: darkblue;
        font-weight: bold;
        font-style: italic;
        font-size: 0.9em;
    }
    code {
        font-family: 'Cascadia Code';
        border: 1px solid #282A36; 
        border-radius: 4px; 
        padding: 1px 4px; 
    }
    pre {
        font-family: 'Cascadia Code';
        border: 1px solid #282A36; 
        border-radius: 4px; 
        padding: 1px 4px; 
    }
    p { 
        font-style: 'Cascadia Code';
        color: white;
    }
    li { 
        margin-bottom: 10px;
        font-style: italic;
        font-weight: bold;
        color: orange;
    }
    ul { 
        margin-bottom: 10px;
        font-style: italic;
        font-weight: bold;
        color: orange;
    }
    b {
        font-weight: bold;
        color: rgb(255, 0, 0); 
    }
    u {
        text-decoration: underline;
        font-weight: bold;
        font-style: italic; 
    }
    a {
        color: #98c379;
        text-decoration: none;
    }
        a:hover {
        text-decoration: underline;
    }
    i {
        font-style: italic;
        color: yellow;
    }
    blockquote {
    background: rgba(255, 0, 127, 0.1); /* Light pink background */
    border-left: 5px solid rgb(255, 0, 127); /* Bold pink left border */
    padding: 10px 15px;
    margin: 10px 0;
    font-style: italic;
    font-weight: bold;
    color: white;
    }
</style>
<!--#endregion-->

# Functions Syntax in JavaScript

A function is a block of code that performs a specific task. It is executed when "something" invokes it (calls it).

### Function Declaration Syntax

```js
function functionName(parameters) {
    // code to be executed
}
```

<b>where</b>

-   `functionName` is the name of the function. It is a unique identifier for the function. It is used to call the function. It is optional.

-   `parameters` are the values passed to the function. They are optional. A function can have zero or more parameters. They are separated by commas. They are used to pass values to the function.
-   `code to be executed` is the block of code that performs the task. It is enclosed in curly braces `{}`. It is mandatory. It is the code that is executed when the function is called.

#### Example

```js
function greet() {
    console.log('Hello, World!');
}
```

### Function Expression Syntax

A function expression is a function that is assigned to a variable. It is not hoisted. It is executed when the variable is called.

```js
const variableName = function (parameters) {
    // code to be executed
};
```

<b>where</b>

-   `variableName` is the name of the variable the function is being assigned to.

-   `const` is a keyword that declares a constant variable. It is mandatory.

#### Example

```js
const greet = function () {
    console.log('Hello, World!');
};
```

### Arrow Function Syntax

An arrow function is a shorter syntax for writing function expressions. It does not have its own `this`, `arguments`, `super`, or `new.target`. It is not hoisted. It is executed when the variable is called.

`this` when talking about functions in general refers to the object that the function is a method of. Arrow functions do not have their own `this`. They inherit `this` from the parent scope.

`arguments` is an array-like object that contains the arguments passed to the function. Arrow functions do not have their own `arguments`. They inherit `arguments` from the parent scope.

`super` is used to call functions on an object's parent. Arrow functions do not have their own `super`. They inherit `super` from the parent scope.

`new.target` is used to determine whether a function was called with the `new` operator. Arrow functions do not have their own `new.target`. They inherit `new.target` from the parent scope.

```js
const variableName = (parameters) => {
    // code to be executed
};
```

#### Example

```js
const greet = () => {
    console.log('Hello, World!');
};
```

> <b>IMPORTANT:</b> All functions in JavaScript return a value by default. If no return value is specified, the function returns `undefined`.
> The return statement does not only specify a value to be returned but also stops execution within a block.

### Function Constructor Syntax

A function constructor is a built-in function that creates a new function object. It is not recommended to use the function constructor to create functions. It is slower and less secure.

```js
const variableName = new Function('parameters', 'code to be executed');
```

<b>where</b>

-   `variableName` is the name of the variable the function is being assigned to.
-   `new` is a keyword that creates a new object. It is mandatory.
-   `Function` is a built-in function constructor. It is mandatory.

#### Example

```js
const greet = new Function('console.log("Hello, World!")');
```

### Self-Invoking Function Syntax

A self-invoking function is a function that runs as soon as it is defined. It is executed immediately. It is not hoisted.

```js
(function () {
    // code to be executed
})();
```

#### Example

```js
(function () {
    console.log('Hello, World!');
})();
```

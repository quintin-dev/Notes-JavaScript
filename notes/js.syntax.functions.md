---
id: t04qd5lkr9qhmmaok9ek8if
title: Functions
desc: ''
updated: 1736034244699
created: 1735912593406
---

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
</style>

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

### Function Expression Syntax

A function expression is a function that is assigned to a variable. It is not hoisted. It is executed when the variable is called.

```js
const functionName = function (parameters) {
    // code to be executed
};
```

<b>where</b>

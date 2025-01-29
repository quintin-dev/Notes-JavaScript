---
id: 4ayysmpraawxjb15aj8u4n0
title: Conditionals
desc: ''
updated: 1738175440884
created: 1734085507093
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

# Conditionals in JavaScript

Conditionals are used to perform different actions based on different conditions. In JavaScript, we have the following conditional statements:

-   `if` statement
-   `if...else` statement
-   `if...else if...else` statement
-   `switch` statement
-   `ternary` operator

## The `if...else` Statement

The `if...else` statement executes a block of code if a specified condition is true and another block of code if the condition is false.

![[js.syntax.conditionals#ifelse-statement-syntax]]

Here is an example of an `if...else` statement:

```javascript
let x = 10;

if (x > 20) {
    console.log('x is greater than 20');
} else {
    console.log('x is less than or equal to 20');
}
```

In this example, the condition `x > 20` is false, so the output will be:

```
x is less than or equal to 20
```

## The Ternary Operator

The ternary operator is a shorthand way of writing an `if...else` statement.

```javascript
condition ? expression1 : expression2;
```

Here is an example of the ternary operator:

```javascript
let x = 10;

let result = x > 5 ? 'x is greater than 5' : 'x is less than or equal to 5';

console.log(result);
```

In this example, the condition `x > 5` is true, so the output will be:

```
x is greater than 5
```

The ternary operator can be used to assign values to variables based on conditions.

---

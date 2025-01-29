---
id: 83jsizmr297zghbccyeg0uk
title: Pop
desc: ''
updated: 1738188668945
created: 1738107296077
---

<!-- #region styles -->
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
<!-- #endregion -->

## Definition

The `pop()` method removes the last element from an array and returns that element. This method changes the length of the array.

## Syntax

```js
arr.pop();
```

## Parameters

None

## Return Values

The removed element from the array.

## Examples

### Example 1

```js
const arr = [1, 2, 3, 4, 5];
const removedElement = arr.pop();

console.log(removedElement); // 5
console.log(arr); // [1, 2, 3, 4]
```

### Example 2

```js
const arr = ['apple', 'banana', 'cherry', 'date'];
const removedElement = arr.pop();

console.log(removedElement); // 'date'
console.log(arr); // ['apple', 'banana', 'cherry']
```

## Applicable To

-   Arrays
-   Typed Arrays

## Edge Cases

## Links

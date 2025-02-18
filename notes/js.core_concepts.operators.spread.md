---
id: b9gkiqglqzx9xiquurkcrt9
title: Spread
desc: ''
updated: 1739906559064
created: 1738969862385
---

<!--#region styles-->
<style>
    * {
        font-size: 18px;
    }
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
        border: 1px solid #282a36;
        border-radius: 4px;
        padding: 1px 4px;
    }
    pre {
        font-family: 'Cascadia Code';
        border: 1px solid #282a36;
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

# Spread Operator

The spread operator is a new addition to the set of operators in JavaScript ES6. It takes in an iterable (e.g an array) and expands it into individual elements. The spread operator is used to split up array elements or object properties.

The spread operator is denoted by three dots `...` and is used to expand an array or object into individual elements. It is used to copy the elements of an array or object into another array or object.

The spread operator is used in the following ways:

1. <b>Copying an array:</b> The spread operator is used to copy the elements of an array into another array.

2. <b>Concatenating arrays:</b> The spread operator is used to concatenate two or more arrays.

3. <b>Passing elements of an array as arguments:</b> The spread operator is used to pass the elements of an array as arguments to a function.
4. <b>Copying an object:</b> The spread operator is used to copy the properties of an object into another object.

#### Examples:

1.  <b>Copying an array:</b>

    ```javascript
    const arr = [1, 2, 3];
    const arr2 = [...arr]; // copies arr into arr2
    console.log(arr2); // Output: [1, 2, 3]
    ```

2.  <b>Concatenating arrays:</b>

    ```javascript
    const arr1 = [1, 2, 3];
    const arr2 = [4, 5, 6];
    const arr3 = [...arr1, ...arr2]; // concatenates arr1 and arr2 into arr3
    console.log(arr3); // Output: [1, 2, 3, 4, 5, 6]
    ```

3.  <b>Passing elements of an array as arguments:</b>

    ```javascript
    function sum(x, y, z) {
        return x + y + z;
    }
    const numbers = [1, 2, 3];
    console.log(sum(...numbers)); // Output: 6
    ```

4.  <b>Copying an object:</b>

    ```javascript
    const obj1 = { a: 1, b: 2 };
    const obj2 = { ...obj1, c: 3 }; // copies obj1 into obj2 and adds property c
    console.log(obj2); // Output: { a: 1, b: 2, c: 3 }
    ```

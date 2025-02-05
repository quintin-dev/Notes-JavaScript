---
id: h6tq3ojhfqba0wrymvyny30
title: Reduce
desc: ''
updated: 1738796926174
created: 1738708823732
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

## Definition

`reduce()` is a method that executes a reducer function on each element of the array, resulting in a single output value. This method is used to reduce the array to a single value.

## Syntax

```js
array.reduce(callback(accumulator, currentValue, index, array), initialValue);
```

## Parameters

-   `callback`: A function that is called on each element of the array. It takes four arguments:

    -   `accumulator`: The accumulator accumulates the callback's return values. It is the accumulated value previously returned in the last invocation of the callback, or `initialValue`, if supplied.
    -   `currentValue`: The current element being processed in the array.
    -   `index`: The index of the current element being processed in the array.
    -   `array`: The array `reduce()` was called upon.

## Return Values

The return value of the `reduce()` method is the accumulated value that results from the reduction. If no `initialValue` is provided, the first element in the array is used as the initial value. If the array is empty and no `initialValue` is provided, a `TypeError` is thrown. If the array has only one element and no `initialValue` is provided, the single element is returned without calling the callback function.

## Examples

### Example 1

```js
const numbers = [1, 2, 3, 4, 5];

const sum = numbers.reduce(
    (accumulator, currentValue) => accumulator + currentValue
);

console.log(sum); // Output: 15
```

## Applicable To

-   arrays

## Edge Cases

## Links

-   [MDN Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce)

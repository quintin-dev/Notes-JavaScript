---
id: ud9smcs7hiaxvgukb6ya98n
title: Sort
desc: ''
updated: 1738275940326
created: 1736370797095
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

The `sort()` method sorts the elements of an array in place and returns the sorted array. The default sort order is ascending, built upon converting the elements into strings, then comparing their sequences of UTF-16 code units values.

## Syntax

```js
arr.sort([compareFunction]);
```

where `compareFunction` is an optional parameter that specifies a function that defines the sort order. If omitted, the array elements are converted to strings, then sorted according to each character's Unicode code point value.

## Parameters

-   `compareFunction` (Optional) - Specifies a function that defines the sort order. If omitted, the array is sorted according to each character's Unicode code point value.

## Return Values

-   The sorted array.

## Examples

### Example 1

```js
const months = ['March', 'Jan', 'Feb', 'Dec'];
months.sort();
console.log(months);
// expected output: Array ["Dec", "Feb", "Jan", "March"]
```

in this example, the array is sorted alphabetically, with the default sort order being ascending.

### Example 2

```js
const array1 = [1, 30, 4, 21, 100000];
array1.sort();
console.log(array1);
// expected output: Array [1, 100000, 21, 30, 4]
```

in this example, the array is sorted as strings, so the default sort order is not correct. The reason this array was sorted as strings is that the `compareFunction` parameter was not provided.

## Applicable To

-   JavaScript Arrays
-   JavaScript Typed Arrays

## Edge Cases

### Edge Case 1

```js
const array1 = [1, 30, 4, 21, 100000];
array1.sort((a, b) => a - b);
console.log(array1);
// expected output: Array [1, 4, 21, 30, 100000]
```

in this example, the array is sorted numerically, with the `compareFunction` parameter provided. this is an edge case because the array is sorted numerically, not alphabetically which is due to the `compareFunction` parameter.

### Edge Case 2

```js
const array1 = [1, 30, 4, 21, 100000];
array1.sort((a, b) => b - a);
console.log(array1);
// expected output: Array [100000, 30, 21, 4, 1]
```

in this example, the array is sorted numerically in descending order, with the `compareFunction` parameter provided. this is an edge case because the array is sorted numerically in descending order, not alphabetically which is due to the `compareFunction` parameter.

## Links

-   [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)
-   [JavaScript.info](https://javascript.info/array-methods#sort)

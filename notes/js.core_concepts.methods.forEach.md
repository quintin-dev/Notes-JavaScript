---
id: 906psszxe7kmdkpie5udape
title: forEach
desc: ''
updated: 1738186130574
created: 1737650770269
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
</style>
<!--#endregion-->

## Definition

The `forEach()` method executes a provided function once for each array element.

## Syntax

```js
array.forEach(function(currentValue, index, arr), thisValue)


```

## Parameters

-   `currentValue`: The current element being processed in the array.

-   `index`: The index of the current element being processed in the array.
-   `arr`: The array `forEach()` was called upon.
-   `thisValue`: A value to be passed to the function to be used as its "this" value.
-   `function`: A function to execute for each element, taking three arguments:
    -   `currentValue`: The current element being processed in the array.
    -   `index`: The index of the current element being processed in the array.
    -   `arr`: The array `forEach()` was called upon.

## Return Values

The `forEach()` method does not return anything.

## Examples

```js
const array1 = ['a', 'b', 'c'];

array1.forEach((element) => console.log(element));
```

## Applicable To

The `forEach()` method is applicable to all arrays.

## Edge Cases

-   If the array is modified during iteration, other elements might be skipped.
-   If the array is sparse, the index will not be visited for those elements.

## Links

-   [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)

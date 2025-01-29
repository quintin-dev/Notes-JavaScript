---
id: hojtxmdeeiwl0s5vff90cz7
title: Split
desc: ''
updated: 1738170314450
created: 1736634481961
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

## Definition

The `split()` method is used to split a string into an array of substrings, and returns the new array. The method takes two parameters: a separator and an optional limit. The separator is used to specify where to split the string, and the limit is used to specify the maximum number of splits to make.

## Syntax

```js
string.split(separator, limit);
```

## Parameters

-   `separator`: The separator to use when splitting the string. This can be a string or a regular expression. If the separator is an empty string, the string is split into an array of each character. If the separator is omitted, the entire string is returned as the first element of the array. The separator is case-sensitive.

-   `limit`: An optional parameter that specifies the maximum number of splits to make. If the limit is provided, the resulting array will have a maximum length of limit - 1. If the limit is not provided, the entire string is split. If the limit is 0, the method returns an empty array.

## Examples

```js
const str = 'Hello,World,JavaScript';
const arr = str.split(',');
console.log(arr); // Output: ['Hello', 'World', 'JavaScript']

const str2 = 'Hello,World,JavaScript';
const arr2 = str2.split(',', 2);
console.log(arr2); // Output: ['Hello', 'World']
```

in this example, the `split()` method is used to split a string into an array of substrings. The first example splits the string `Hello,World,JavaScript` using a comma as the separator, resulting in an array with three elements: `['Hello', 'World', 'JavaScript']`. The second example splits the same string using a comma as the separator and a limit of 2, resulting in an array with two elements: `['Hello', 'World']`.

## Applicable To

The `split()` method is applicable to all JavaScript strings.

## Return Values

-   The `split()` method returns an array of substrings. If the string is empty, the method returns an array with one empty string as the only element.

-   If the separator is an empty string, the method returns an array of each character in the string.
-   If the separator is not found in the string, the method returns an array with the entire string as the only element.
-   If the limit is 0, the method returns an empty array.
-   If the limit is not provided, the method returns an array with all the splits.
-   If the limit is greater than the number of splits, the method returns an array with all the splits.

## Edge Cases

-   If the separator is not found in the string, the method returns an array with the entire string as the only element. For example, `str.split('!')` will return `['Hello,World,JavaScript']`.
-   If the separator is an empty string, the method returns an array of each character in the string. For example, `str.split('')` will return `['H', 'e', 'l', 'l', 'o', ',', 'W', 'o', 'r', 'l', 'd', ',', 'J', 'a', 'v', 'a', 'S', 'c', 'r', 'i', 'p', 't']`.
-

## Links

-   [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/split)
-   [W3Schools](https://www.w3schools.com/jsref/jsref_split.asp)
-   [JavaScript.info](https://javascript.info/array-methods#split)
-   [Can I Use](https://caniuse.com/?search=split)

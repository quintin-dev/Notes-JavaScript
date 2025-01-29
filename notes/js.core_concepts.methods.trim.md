---
id: asfz0jtx7ogz575opk56w6z
title: Trim
desc: ''
updated: 1738168199014
created: 1736972360164
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

## Definiton

The `trim()` method removes whitespace from both ends of a string. Whitespace in this context is all the whitespace characters (space, tab, no-break space, etc.) and all the line terminator characters (LF, CR, etc.).

## Syntax

```js
str.trim();
```

## Parameters

None

## Return value

A new string representing the calling string stripped of whitespace from both ends.

## Examples

```js
console.log('   foo  '.trim()); // 'foo'
```

## Applicable To

The trim method is applicable to all strings.

## Edge cases

```js
console.log('   foo  '.trim()); // 'foo'
console.log('foo'.trim()); // 'foo'
console.log(''.trim()); // ''
```

## Links

-   [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/trim)

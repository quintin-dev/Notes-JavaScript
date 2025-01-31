---
id: ocuv4lpmtw0f1lmmnu17zc2
title: Selectors
desc: ''
updated: 1738363430319
created: 1738359449554
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

# DOM API METHODS

## 1. querySelector()

The `querySelector()` method returns the first element that matches a specified CSS selector(s) in the document.

```js
document.querySelector(selector);
```

#### Example:

```js
const paragraph = document.querySelector('p');

/* The above code will return the first paragraph element in the document and 
assign it to the variable 'paragraph'. */
```

## 2. querySelectorAll()

The `querySelectorAll()` method returns all elements in the document that matches a specified CSS selector(s), as a static NodeList object.

```js
document.querySelectorAll(selector);
```

#### Example:

```js
const paragraphs = document.querySelectorAll('p');

/*The above code will return a static NodeList of all paragraph elements in the document and
 assign it to the variable 'paragraphs'.*/
```

> **Note:** The `querySelectorAll()` method returns a static NodeList, which means that any changes made to the document will not be reflected in the NodeList.

## 3. getElementById()

The `getElementById()` method returns the element that has the ID attribute with the specified value.

```js
document.getElementById(id);
```

#### Example:

```js
const myElement = document.getElementById('myId');

/*The above code will return the element with the ID 'myId' and
 assign it to the variable 'myElement'.*/
```

## 4. getElementsByClassName()

The `getElementsByClassName()` method returns a collection of all elements in the document with the specified class name.

```js
document.getElementsByClassName(className);
```

#### Example:

```js
const myElements = document.getElementsByClassName('myClass');

/*The above code will return all elements with the class 'myClass' and
 assign them to the variable 'myElements'.*/
```

## 5. getElementsByTagName()

The `getElementsByTagName()` method returns a collection of all elements in the document with the specified tag name.

```js
document.getElementsByTagName(tagName);
```

#### Example:

```js
const myElements = document.getElementsByTagName('p');

/*The above code will return all paragraph elements in the document and
 assign them to the variable 'myElements'.*/
```

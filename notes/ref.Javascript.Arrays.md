---
id: bvi76ileaqas0cngzyau7lb
title: Arrays
desc: ''
updated: 1733966446011
created: 1733966144654
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

# Arrays In JavaScript

An array is a special variable that can hold more than one value at a time. It is a collection of variables that are stored under a single name. Each value in an array is called an element. eg. `var cars = ["Saab", "Volvo", "BMW"];`

## Creating an Array

You can create an array in two ways:

1. Using an array literal: `var cars = ["Saab", "Volvo", "BMW"];` An array literal is a list of variables separated by commas and enclosed in square brackets.

2. Using the `Array()` constructor: `var cars = new Array("Saab", "Volvo", "BMW");` The `Array()` constructor is used to create an array.

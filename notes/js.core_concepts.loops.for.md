---
id: j6vlzbs0u6szoo1t88s4kuf
title: For
desc: ''
updated: 1738275940364
created: 1738105763926
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

## for Loop

The `for` loop is used to execute a block of code a specified number of times. The syntax of the `for` loop is as follows:

```javascript
for (initialization; condition; increment / decrement) {
    // code to be executed
}
```

The `initialization` statement is executed only once at the beginning of the loop. The `condition` is evaluated before each iteration. If the condition is `true`, the code block is executed. The `increment / decrement` statement is executed after each iteration. The loop continues until the condition is `false`.

Here is an example of a `for` loop:

```javascript
for (let i = 0; i < 5; i++) {
    console.log(i);
}
```

In this example, the loop will run five times, and the output will be:

```
0
1
2
3
4
```

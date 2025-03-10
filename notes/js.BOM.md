---
id: d56bfd14w5pfy7u0hisjq1o
title: BOM
desc: ''
updated: 1741662427012
created: 1741488886729
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

## BOM (Browser Object Model)

The Browser Object Model (BOM) is a collection of objects that allow JavaScript to interact with the browser. It provides methods and properties to manipulate the browser window, including the ability to open new windows, navigate to different URLs, and manage browser history.

### Key Components of BOM

-   **Window Object**: Represents the browser window and provides methods to control it.
-   **Navigator Object**: Contains information about the browser and the operating system.
-   **Screen Object**: Provides information about the user's screen, such as its width and height.
-   **Location Object**: Represents the current URL and provides methods to manipulate it.
-   **History Object**: Allows access to the browser's session history, enabling navigation through previously visited pages.
-
-   **Document Object**: Represents the HTML document loaded in the browser and provides methods to manipulate its content.
-   **XMLHttpRequest Object**: Used for making asynchronous HTTP requests to the server, enabling dynamic content loading without refreshing the page.
-
-   **Console Object**: Provides methods for logging messages to the browser's console, useful for debugging and testing.
-   **Alert, Confirm, and Prompt Dialogs**: Methods for displaying alert messages, confirmation dialogs, and input prompts to the user.
-   **Timers**: Functions like `setTimeout` and `setInterval` for scheduling code execution after a specified delay or at regular intervals.
-   **Geolocation API**: Provides access to the user's geographical location, allowing for location-based services.

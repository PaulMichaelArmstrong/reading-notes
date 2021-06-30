[< Back](README.md)

# Dynamic Web Pages With JavaScript
JavaScript makes web pages interactice. If HTML is the structure of a house, CSS is the decorations, then JavaScript are the fuctional parts like hinges and doorknobs. Have you ever signed up for a newsletter on a website? That's JavaScript!

It leans uses variable sets and functions to create actions. Here is an explape from Code Maven:

```
<html>
<head>
  <title>Hello World</title>
</head>
<body>
 
First name: <input id="first_name">
Last name: <input id="last_name">
<button id="say">Say hi!</button>
 
<hr>
<div id="result"></div>
 
<script>
function say_hi() {
    var fname = document.getElementById('first_name').value;
    var lname = document.getElementById('last_name').value;
 
    var html = 'Hello <b>' + fname + '</b> ' + lname;
 
    document.getElementById('result').innerHTML = html;
}
 
document.getElementById('say').addEventListener('click', say_hi);
</script>
 
</body>
</html>
```

And it would result in something like this:

_Empty State_

![input form](/linked-files/input_form.png)

_Output State_

![input form with output](/linked-files/input_form_and_output.png)


What can JavaScript do?
- Change HTML content
- Change HTML attributes
- Change CSS style
- Hide HTML elements
- Show hidden HTML elements

Where do you insert JavaScript?
- `<head>`
- `<body>`
- An external file
- An external url
- An external folder

Where can JavaScript output to?
- The HTML output
- An HTML element
- A window alert box
- The browser console


***

**Sources:**
- [MDN Web Docs - JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Code Maven - Input Output In Plain JavaScript](https://code-maven.com/input-output-in-plain-javascript)
- [W3 Schools - JavaScript Variables](https://www.w3schools.com/js/js_variables.asp)
- [How Computers Work](https://www.youtube.com/playlist?list=PLzdnOPI1iJNcsRwJhvksEo1tJqjIqWbN-)

[< Back](README.md)
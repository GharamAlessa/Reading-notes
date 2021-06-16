# JavaScript
![js](https://coryrylan.com/assets/images/posts/types/javascript-1280x960.png)
JavaScript ***JS*** is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. 
This section is dedicated to the JavaScript language itself, and not the parts that are specific to Web pages or other host environments.
 The JavaScript documentation throughout MDN is based on the latest draft versions of ECMA-262 and ECMA-402.
 Both "Java" and "JavaScript" are trademarks or registered trademarks of Oracle in the U.S. and other countries. However, the two programming languages have very different syntax, semantic, and use.

## examples/js/pure_js_greating.html

><html>
><head>
  ><title>Hello World</title>
></head>
><body>
 
>First name: <input id="first_name">
>Last name: <input id="last_name">
><button id="say">Say hi!</button>
 
><hr>
><div id="result"></div>
 
><script>
>function say_hi() {
    >var fname = document.getElementById('first_name').value;
    >var lname = document.getElementById('last_name').value;
 
    >var html = 'Hello <b>' + fname + '</b> ' + lname;
 
    >document.getElementById('result').innerHTML = html;
 
>document.getElementById('say').addEventListener('click', say_hi);
></script>
 
></body>
></html>
## JavaScript Variables
JavaScript variables are containers for storing data values.

In this example, x, y, and z, are variables, declared with the var keyword
![js2](https://www.wikihow.com/images/thumb/7/7e/Declare-a-Variable-in-Javascript-Step-2.jpg/aid1337336-v4-728px-Declare-a-Variable-in-Javascript-Step-2.jpg.webp)

In programming, just like in algebra, we use variables (like price1) to hold values.

In programming, just like in algebra, we use variables in expressions (total = price1 + price2).
#### JavaScript Underscore (_)
Since JavaScript treats underscore as a letter, identifiers containing _ are valid variable names

and you can read more [here](https://www.w3schools.com/js/js_variables.asp)

---
layout: post
title: "Object, Elements, and Properties for Javascript manipulation "
permalink: /class-01
---
Jason Dormier

Objects, elements, and properties are the things that make up a any webpage. We can interact with all of these things that comprise a webpage using Javascript code and understanding of how the elements and properites of the each page are laid out, and begin to manipulate the elements, properites and data in anyway we see fit.

For the example below the `<!DOCTYPE html>` is the declaration of the DocumentType Object. Everything inside this object can be maniuplated in various ways using events, methods, and functions with javascript. 

```HTML
<!DOCTYPE html> <!-- This represents out page -->
  <html><!-- Element -->
      <head><!-- Element -->
        <title> This is a property of the DOM </tile><!-- This is a property of the webpage. It is describing the title of the current page. -->
        <link rel="stylesheet" href="/css/styles.css" /> <!-- CSS style sheets are a properity of the DOM object because they are used to describe many visual properites of the object. -->

    </head>
      <body><!-- Element -->
        <h1> A header </h1><!-- Element -->
        <p class="someClass someClass--switch">Some text to change color of</p><!-- Element nested in an element -->
        <script src="/js/somescript.js"></script>
    </body>
  </html>
```

Below is an example of manipulating the text inside an element of the document object.

```Javascript
      //grabbing class element of the document object and storing it in a variable.
      const someClassSwitch = document.querySelector('.someClass--switch');
      
      //Telling the text of the element in the document object to change to the color red when the mouse hovers over it.
      someClassSwitch.addEventListener('mouseover', function () {
        someClassSwitch.style.color = 'red';
      });
      //Telling the text of the element in the document object to change to the color to black when the mouse stops hovering over it.
      someClassSwitch.addEventListener('mouseout', function () {
        someClassSwitch.style.color = 'black';
      });

```

---
layout: post
title: "Links and Functions"
permalink: /class-04
---
Jason D

* links are created using `<a>` element

* `<a>` element uses `<a href>` attribute to direct the user to the right page.

* linking to an external site `<a href = "https://www.examplepage.com">`

* It is best to use relative links when linking your your page. For example: `<``a href = "exampleFolder/example.html">`.

* An example of going back to the homepage from a nested page: `<a href = "../../index.html>`.

* If you want to make it easy for someone to email you `<a href = "mailto:exampleEmail@example.com">Email Timmy</a>`.

* You can link to to important places on your page. This would be useful for a website that is a single page. `<a href ="#top">Top</a>` This will send the user to a page element with the ID of top.

* Functions and methods are a series of statements that have been grouped together.

* Objects create a model of the world using data.

* Example of a basic funtion.

```javascript
function whadUp(){
  alert('Whad Up!');
}
```

* calling the funtion

```javascript
whadUp();
```

* Example of Function with a parameter.

```javascript
function whadUp(name){
  alert(`Whad Up ${name}!`);
}
```

Calling a function with an argument.
```javascript
whadUp('Timmy');
```
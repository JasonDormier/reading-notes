---
layout: post
title: "Floats and Flexibility"
permalink: /read-01
---
Jason D
 
* If the parent element contains nothing but floats it will collapse.
* `<float: left>` `<float: right>` `<clear: left>` `<clear: right>` `<clear: both>`
* `<float: left>` will float the element to the left. Allowing text to flow around the element.
* `<float: right>` will float the element to the right. Allowing text to flow around the element.
* `<clear: left>` will clear elements to the left of the element.
* `<clear: right>` will clear elements to the right of the element.
* `<clear: both>` will clear both sides of the element.
* Use an empty div to help with float issues with the following css styling
```CSS
.clearfix:after { 
   content: "."; 
   visibility: hidden; 
   display: block; 
   height: 0; 
   clear: both;
}
```
* Moblie development, Responsive development, and Adaptive development.
* vw - viewport width
* vmin - min of viewport height and width
* vh - viewport height
* vmax - max viewport height and width
* use media queries to dictate what kind of screen or device the user is on and adjust your design accordingly.
* Most sites use a rudimentary grid already
* Make it easier by using an actual CSS grid.


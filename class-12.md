---
layout: post
title: "Charts, Canvas, and Shapes"
permalink: /class-12
---
Jason D

### Canvas

* The `<canvas>` element can be styled just like any normal image (margin, border, background…).

* An example js script drawing to squares

```js
    function draw() {
      var canvas = document.getElementById('canvas');
      if (canvas.getContext) {
        var ctx = canvas.getContext('2d');

        ctx.fillStyle = 'rgb(255, 0, 0)';
        ctx.fillRect(50, 5S0, 100, 100);

        ctx.fillStyle = 'rgba(135, 135, 135, 0.5)';
        ctx.fillRect(60, 60, 100, 100);
      }
    }
```
### Drawing Shapes

* `<fillRect(x, y, width, height)>` Draws a filled rectangle

* `<strokeRect(x, y, width, height)>` Draws a rectangle outlined

* `<clearRect(x, y, width, height)>` Clears a specified area making the are transparent

* `<beginPath()>` Creates a new path

* `<closePath()>` Adds a straight line to the path, from start to sub path

* `<stroke()>` Draws the shaoe by outline

* `<fill()>` Dars a solid shape

### Chart.js

* Chart js just needs a canvas setup on the page to get going

* Example of a line graph with chart.js

```js
var buyerData = {
	labels : ["July","August","September","November","December","January"],
	datasets : [
		{
			fillColor : "rgba(108,179,187,0.3)",
			strokeColor : "#6CB3BB",
			pointColor : "#565656",
			pointStrokeColor : "##19626A",
			data : [150,130,58,365,123,78]
		}
	]
}
```

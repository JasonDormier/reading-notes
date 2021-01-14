---
layout: post
title: "Responsive Web Design and Regular Expressions"
permalink: /read-04
---
Jason D


* Setting up the grid template to manipulate.

  ```css
  #section {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
  }
  ```

* `<grid-column-start>` - starting point of a column.

*  `<grid-column-end>` - the ending point of a column.

* `<grid-column: 2/5;>` - short hand for column start and end.

* `<grid-column-start: span 5>` - another method to get an element to increase the size of an element across the grid.

* `<grid-row-start>` - starting point of a row.

*  `<grid-row-end>` - the ending point of a row.

* `<grid-row: 2/5;>` - shorthand for row start and end.

* use a combination of `<grid-row>` and `<grid-column>` 

* `<grid-area: 1/2/3/4>` Is short hand to define the column row start and end and row start and end.
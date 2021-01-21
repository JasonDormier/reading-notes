---
layout: post
title: "Refactoring"
permalink: /read-09
---
Jason D

* Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

* In order to make a function pure it should not change global varibles. If you funtion relies of global varibles that need to change they should be passed into the function and the parameter should handle the change. Leaving the global varible the same in essense.

```javascript
let counter = 1;

const increaseCounter = (value) => value + 1;

increaseCounter(counter); // 2
console.log(counter); // 1
```

* Pure functions are easier to test

* When data is immutable, its state cannot change after it’s created








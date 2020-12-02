---
layout: post
title: "Arrays and Loops"
permalink: /class-02
---
Jason D

Loops and arrays go hand in hand. Arrays terrific ways to get storing large amounts of data of all sorts. The issue with all of that data can be how do you sort through it. Especially when programming. A programmer needs to instruct the computer what it needs to do every step of the way. What happens when the array is several thousand, million, or heaven forbid, billion elements long? Well, that’s where loops come in handy. However, let’s keep it relatively simple.

Let’s create an array of random numbers.

```javascript
const arryNum = [1, 4, 5, 7, 8, 54, 34, 43, 4323, 43, 234, 23, 43, 93, 3, 21,];
```
We could also create an array of names or string elements it doesn’t matter.

```javascript
const arryNames = [ ‘tim’, ‘ryan’, ‘michael’, ‘bryan’, ‘jason’, ‘harold’];
```
Now let’s write a basic for loop that can count to 10.

```javascript
for( let i = 0; i < 1 i++){
	//do some loopitry loop stuff
} ;
```

Now let’s put the two ideas together and loop through an array. 
```javascript
//our array of numbers from before
const arryNum = [1, 4, 5, 7, 8, 54, 34, 43, 4323, 43, 234, 23, 43, 93, 3, 21,];


for (let i = 0; i < arryNum.length; i++) {
  console.log(arryNum[i]);
};
```

We have created a loop that will now loop through our whole array and report to the console each number in the array.

```javascript
const arryNum = [1, 4, 5, 7, 8, 54, 34, 43, 4323, 43, 234, 23, 43, 93, 3, 21,];


for (let i = 0; i < arryNum.length; i++) {
  console.log(arryNum[i]);
  if (arryNum[i] === 43) {
    console.log([i]);
  }
};
```
Here we have taken it a step further and added an if statement to find each index that holds the number 43

This has been a basic presentation of arrays and loops and hopefully shows some of the might these two aspects of programming provide.

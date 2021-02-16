---
layout: post
title: "Node Ecosystem, TDD, CI/CD"
permalink: /read-class-01
---

### Array.map()
  * will create a new array with the results of a function provided on each element of the input array.
  [mdn array.map()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
 
### Array.reduce()
  * Reduce while taking an input array and produce a single value output.
  * The output will depend on what the user returns to the accumulator on each element of the array.
  * Reduce can take four inputs `Accumulator`, Current `Value`, Current `Index`, Source `Array`
  * `arr.reduce(callback( accumulator, currentValue, [, index[, array]] )[, initialValue])`
  [mdn array.reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)
### supgeragent()
  * super-agent is a tool used to fetch API data from relevant URLs
  * `npm install superagent`
  * insert `const superagent = require('superagent');`
  * now you are ready to rock and roll using promises which you can see below with `.then` and add a `.catch` for any errors
 
  ```javascript
      const domainUrl = `https://api.domainsdb.info/v1/domains/search?&limit=5&country=us&domain=keyword`;
      superagent.get((domainUrl)
      .then(results => {
        console.log(results.body)
      })
      .catch(err => console.error(err));
      );
  ```
  * Now lets try it using ES6 promises 
 ```javascript
    async function getDomain(request, response){
      const domainUrl = await superagent.get(`https://api.domainsdb.info/v1/domains/search?&limit=5&country=us&domain=keyword`);
      console.log(domainUrl);
  ```
  * a promise is a way to tell javascript to move on to the next piece of code while the data is returning and will return to execute that piece of code when the promise is returned.
 
### Are callback functions Asynchronous?
* No, it really depends on the use of the callback function. A callback function that is attached to a promise will execute Asynchronously, however, if it is just a function passed into another function it will execute synchronously. 

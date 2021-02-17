---
layout: post
title: "Express REST API"
permalink: /read-class-03
---

##### Name 3 real world use cases where you’d want to change the request with custom middleware
  * Error handling
  * validation
  * preprocessing data
 
##### True or false: The route handler is middleware?
  * No the route handler itself is not middleware
 
##### In what ways can a middleware function end the process and send data to the browser?
  * `next()`
  * `res.end()`
  * `res.send()`
 
##### At what point in the request lifecycle can you “inject” middleware?
  * It can be injected between the request and the response
 
##### What can cause express to error with “Request headers sent twice, cannot start a second response”
  * This happens when the request header has already been sent 
 
 
### Document the following Vocabulary Terms
 
##### Middleware
  * functionality that sits between request and response routes
 
##### Request Object
  * Any form of data being sent from a client
 
##### Response Object
  * Any form of data that is responding to the client's request
 
##### Application Middleware
  * software that functions in between operating systems and applications
 
##### Routing Middleware
  * routing middleware brings the request data in one end does a thing and passes it down the route
 
##### Test Driven Development
  * is a process that replies on the software being converted into test cases for tracking and repeatedly testing the software against test cases
 
##### Behavioral Testing
  * testing the external behaviors of a program

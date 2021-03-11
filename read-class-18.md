---
layout: post
title: "AWS: Events"
permalink: /class-18
---
Jason D


##### What’s the difference between a FIFO and a standard queue?
* FIFO is first in first out, where as standard queues support "exactly one" processing and ordering of the queue

##### How can the server be assured a message was properly received?
* The client can emit right back to the server that the message was received

##### What classic design pattern is best represented by event driven programming?
* The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods

##### How do you test an event driven system?
* Unit tests, which will test individual parts of the system

### Vocabulary Terms

##### Serverless API
* using API Gateway you can create RESTful APIs that enable real-time two-way communication applications, API Gateway supports containerzied and serverless workloads as well as web applications 

##### Triggers
* Are assigned to a function to envoke the function to fire

##### Dynamo vs Mongo
* Monogo can be deployed anywhere with JSON
* Dynamo can only be deplyed on AWS, with a key-values and some JSON

##### Dynamoose vs Mongoose
* Dynamoose is simalar to Mongoose but allows us to provise a schema to perform CRUD operations

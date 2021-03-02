---
layout: post
title: "Socket.io"
permalink: /read-class-11
---

###### What is the benefit of transforming data into packets?
* It is an efficient way to send data, that allows for some error, if there is an error sending a packet it doesn't disrupt the whole transmission. The errored packet can just be resent.
 
##### UDP is often referred to as a connectionless protocol. Why is this?
* No connection needs to be established between the source and destination before you transmit data. UDP does not have a mechanism to make sure that the payload is not corrupted. As a result, the application must take care of data integrity all by itself.
 
##### Can a socket server application have multiple socket connections?
* A server socket listens on a single port. ... Multiple connections on the same server can share the same server-side IP/Port pair as long as they are associated with different client-side IP/Port pairs, and the server would be able to handle as many clients as available system resources allow it to
 
##### Can a socket connection application be connected to multiple socket servers?
* Multiple connections on the same server can share the same server-side IP/Port pair as long as they are associated with different client-side IP/Port pairs, and the server would be able to handle as many clients as available system resources allow it to
 
##### Can an application be both a socket server and a socket connection?
* yes
 
##### Observer Pattern
* is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.
 
##### Listener
* A function that listens for an event to occur
 
##### Event Handler
* A function that is triggered by a specific event
 
##### Event Driven Programming
* The flow of a program is driven by a series of events
 
##### Event Loop
* Is responsible for monitoring the call stack 
 
##### Event Queue
* Stores a series of functions, objects, and notifications 
 
##### Call Stack
* a call stack is a stack data structure that stores information about the active subroutines of a computer program
 
##### Emit/Raise/Trigger
* Facilitates the communication and interaction between node objects.
 
##### Subscribe
* A subscriber is a method that sets up an event publisher
 
##### database
* A database is a storage of data.
 

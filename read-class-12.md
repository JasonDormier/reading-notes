---
layout: post
title: "Message Queues"
permalink: /read-class-12
---

##### What does it mean that web sockets are bidirectional? Why is this useful?
* It means that receive messages and emit them as well. It makes them a more robust network of socket connections.
 
##### Does socket.io use HTTP? Why?
* Yes, so it can serve as its own client
 
##### What happens when a client emits an event?
* The client will emit a message, packet, or data whatever it may be out to the server where the server will redirect it to where it needs to go
 
##### What happens when a server emits an event?
* The server will emit the message to all connected and listening sockets
 
##### What happens if a client “misses” an event?
* It will be ignored
 
##### How can we mitigate this?
* making sure you have handlers installed and make sure they are handling those events properly
 
##### Socket
* the endpoint of a two-way communication
 
##### Web Socket
*  an end-point in communication across a network or the Internet
 
##### Socket.io
* A javascript library that allows bidirectional event direction communication of web sockets
 
##### Client
* One of the two endpoints where the socket communication either ends or begins
 
##### Server
* The transfer hub that disperses the emits to the right location
 
##### OSI Model
* Open system interconnection references how information should move from software to software
 
##### TCP
* Transmission control protocol specifies how data should be packaged and sent
 
##### UDP
* User Datagram protocol 
 
##### Packets
* is a formatted chunk of data sent over a network.



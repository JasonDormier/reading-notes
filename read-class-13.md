---
layout: post
title: "Event Driven Architecture"
permalink: /read-class-13
---

##### What’s the difference between a FIFO and a standard queue?
* FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly-once processing.

##### How can the server be assured a message was properly received?
* It can log a confirmation message

##### What classic design pattern is best represented by event driven programming?
* it most closely resembles the observer pattern

##### How do you test an event driven system?
* Event-driven application architectures make it so that various components in a very large distributed system can communicate and interoperate asynchronously

##### FIFO Queue
* queues are designed to enhance messaging between applications when the order of operations and events is critical

##### Pub/Sub
* is an asynchronous messaging service that decouples services that produce events from services that process events
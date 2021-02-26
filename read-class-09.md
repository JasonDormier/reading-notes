---
layout: post
title: "Stacks and Queues"
permalink: /read-class-09
---

## Stack and Queues
 
### Stack
 
* A stack is a data structure that consists of `Nodes`. Each `Node` references the next `Node` in the stack but does not reference its previous `Node`.
 
##### Stack Terminology
 
* Push - Node or items that are put into the stack are pushed
* Pop - Nodes or items that are removed from the stack are popped
* Top - This is the top of the stack
* Peek - this receives the value of the Node on the top of the stack
* IsEmpty - returns true when the queue is empty otherwise returns false
 
##### FILO
* First In Last Out - First item in will be the last item popped out
 
##### LIFO
* Last in First Out - Last item in will be the first item popped out
 
### Queue
 
* Queues seem to be a similar data structure as stacks but in a linear fashion
 
##### Queue Terminology
 
* Enqueue - Nodes or items that are added to the queue
* Dequeue - Nodes or items that are removed from the queue
* Front - this is the front/first Node in the queue
* Rear - this is the rear/last Node in the queue
* Peek - this receives the value of the front Node in the queue
* IsEmpty - returns true when the queue is empty otherwise returns false
 
##### FiFO
* First In First Out - First item into the queue will be the first item out
 
##### LILO
* Last In Last Out - Last item into the queue will be the last item out
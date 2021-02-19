---
layout: post
title: "Linked Lists"
permalink: /read-class-05
---

* A linked list is a sequence of `Nodes` that are connected to each other
* Each `Node` references the next  `Node` in the link
* A `Singly` linked list means there is only one reference pointing to the next `Node`
* `Doubly` linked lists means the `Node` is refencing both the `Next` and `Previous` `Node`
* Each `Node` contains data pretaining to the linked list
* `Current` refers to the Node that is currently being looked at
* `Next` refers to the `Node` that is next in the list
* `Previous`refers to the `Node` that appeared prior to the `Current` `Node`
* To traverse a linked list `for` loops don't work, you have to use `Next`
* `while()`loops are the best way to traverse a linked list
* The `Current` Node will tell us where the end of the linked list
* The `while()` loop will only run if the node the `Current` node looking at is not `null`
* Order of operations is extermely important when it comes tow orking with linked lists
* Set `Current` to equal `Head` this will make sure we are starting from the beginning

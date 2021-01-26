---
layout: post
title: "The Call Stack"
permalink: /read-10
---
Jason D

* A call stack is a mechanism for an interpreter to keep track of its place in a script that calls multiple functions

* When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.

* Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.

* When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.

* If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.

* The call stack is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

* A stack overflow occurs when there is a recursive function without an exit point. The browser has a maximum stack call that it can accomodate before throwing a stack error.

* It works as a LIFO — Last In, First Out data structure.
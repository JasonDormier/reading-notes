---
layout: post
title: "Redux - Combined Reducers"
permalink: /class-30
---
Jason D

##### Why choose Redux instead of the Context API for global state?
* REdux does a better job of keeping your state organized when your project starts to increase in scope

##### What is the purpose of a reducer?
* After receiving an action the reducer interprets that actions and changes or updates the state

##### What does an action contain?
* Actions are objects that contains type and payload components

##### Why do we need to copy the state in a reducer?
* It can only make copies of the on the original values to prevent bugs and other problems

### Vocabulary Terms

##### immutable state
* A state that cannot be changed

##### time travel in redux
* The ability to step forward and backwards through your code when debugging

##### action creator
* A function that returns an object

##### reducer
* A function that manages the state

##### dispatch
* The action trigger
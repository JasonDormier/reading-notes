---
layout: post
title: "Login and Auth"
permalink: /class-27
---
Jason D

##### Why is the Context API useful?
* Because it allows the programmer to control the global state of the app rather then having to pass it down through props

##### What are some common use cases for using the Context API?
* Changing from dark to light themes or UI based changes. Generally anything from end related

##### Describe “Context Hell”
* adding Context Providers makes for messy and unreadable code and this makes for a very frustrating workspace.

### Vocabulary Terms

##### global state
* when many components need access to the same stateful information

##### global context
* is designed to share data that can be considered “global” for a tree of React components

##### provider
* component makes the Redux store available to any nested components that need to access the Redux store

##### consumer
* wrap a component with context which injects the context argument in the component
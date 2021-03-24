---
layout: post
title: "Component Composition"
permalink: /class-21
---
Jason D

##### Can a parent component access the state of a child component?
* Refs can be used to access the state of a child component. Refs are created using React.createRef() and attached to React elements via the ref attribute.
 
##### What can be passed along in a prop variable?
*  Most anything can be passed through a prop(properties) variable
 
##### How can a child component “know” the state of another component?
* You can accomplish this by passing the component the state using a prop variable
 
### Vocabulary Terms
 
##### component props
* Input that can be used to pass along data through components in React
 
##### component state
* The state of a specific component that can only be updated in that component. 
 
##### application state
* This is a global state that can be passed down from whichever file is acting as the main source file
 
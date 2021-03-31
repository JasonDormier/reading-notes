---
layout: post
title: "Context API"
permalink: /class-25
---
Jason D

##### Describe use cases for useMemo() and useReducer()
* useMemo returns a memoized value, the result of that function call. useReducer() is primitive and you can use useReducer for everything you can do with useState. Reducer is so powerful that it can apply for various use cases.

##### Why do custom hooks need the use prefix?
* They should start with use so you can tell at a glance that the rules of hooks applies to it

##### What do custom hooks usually do?
* They allow you to extract and share logic that was not possible using classes

##### Using any list of custom hooks, research and name one that you think will be useful in your applications
* useEffects() Data fetching, setting up a subscription, and manually changing the DOM in React components are all examples of side effects. Whether or not you’re used to calling these operations “side effects” (or just “effects”), you’ve likely performed them in your components before.

##### Describe how a hook that fetches API data might work
* to set the data in the local state of the component with the state hook's update function. ... Because we are setting the state after every data fetch, the component updates and the effect runs again. It fetches the data again and again

##### Vocabulary Terms

##### reducer
* seReducer() is primitive and you can use useReducer for everything you can do with useState. Reducer is so powerful that it can apply for various use cases.
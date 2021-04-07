---
layout: post
title: "Redux - Asynchronous Actions"
permalink: /class-31
---
Jason D

#### How granular should your reducers be?
* As granular as you need them to be.

#### Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched
* That would depend on how much control you prefer to have over the actions of your app. If you are looking to have total control then it would be a con.

#### Name a strategy for preventing the above
* Come up with unqiue names for your actions

### Vocabulary Terms
#### store
* A store holds the whole state tree of your application. The only way to change the state inside it is to dispatch an action on it.

#### combined reducers
* helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore.
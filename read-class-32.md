---
layout: post
title: "Redux - Additional Topics"
permalink: /class-31
---
Jason D

#### What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?
* useEffect() on the index.js file should do it

#### When using a thunk/async action that dispatches the actual action, which do you export from your reducer?
* You export the actual action

### Vocabulary Terms
#### middleware
*  middleware is some code you can put between the framework receiving a request, and the framework generating a response

#### thunk
* middleware the delays an action
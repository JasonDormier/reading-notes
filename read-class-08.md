---
layout: post
title: "Access Control"
permalink: /read-class-08
---

##### When is Basic Authorization used vs. Bearer Authorization?
* Basic auth is used with a username and a secret that is string-based. Bearer is more secure and uses tokens that are encrypted 
 
##### What does the JSON Web Token package do?
* defines the compact and self-contained way for securely transmitting information between parties as a JSON object.
 
##### What considerations should we make when creating and storing a SECRET?
* How it is being sent, where it is being stored, how long should it last, should it be stored in local storage for a better user experience or does it need to expire to be more secure, it should never be stored in plain text.
 
### Document the following Vocabulary Terms
 
##### encryption
* Is the process of encoding information on one end and decoded on the other end to be used
 
##### token
* A token that is given to the user to allow them to access the data they are seeking for that session
 
##### bearer
* Is an HTTP authentication scheme that involves security tokens
 
##### secret
* Something you don't want anyone else to know, lol, in this context, it would be the same as a password
 
##### JSON Web Token
* is a compact URL-safe means of representing claims to be transferred between two parties.
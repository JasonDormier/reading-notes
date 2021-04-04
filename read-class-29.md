---
layout: post
title: "Application State with Redux"
permalink: /class-29
---
Jason D


##### What are the advantages of storing tokens in “Cookies” vs “Local Storage”
* Local storage is vulnerable because it's easily accessible using JavaScript and an attacker can retrieve your access token and use it later. However, while httpOnly cookies are not accessible using JavaScript, this doesn't mean that by using cookies, you are safe from XSS attacks involving your access token.

##### Explain 3rd party cookies.
*  are cookies that are set by a website other than the one you are currently on.

##### How do pixel tags work?
* Pixel tags are typically single pixel, transparent GIF images that are added to a web page. Even though the pixel tag is virtually invisible, it is still served just like any other image you may see online, and it used for tracking user engagement.

### Vocabulary Terms

##### cookies
* is a small piece of data stored on the user's computer by the web browser while browsing a website.

##### authorization
* giving permission or authority

##### access control
* is a method of guaranteeing that users are who they say they are and that they have the appropriate access to company data.

##### conditional rendering
* rendering content based on the state of your application
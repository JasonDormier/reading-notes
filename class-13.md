---
layout: post
title: "Charts, Canvas, and Shapes"
permalink: /class-13
---
Jason D

### Local Storage

* check for html5 
```js
function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}
```

* or use modrenizer
```js
if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
}
```

* HTML5 Storage is based on named key/value pairs.

* `<setItem()>` with a ket value pair to set the pack the information, and retrieve it with `<getItem()>` and the key to get the information.

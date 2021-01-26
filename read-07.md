---
layout: post
title: "API's"
permalink: /read-07
---
Jason D

* The Node client allows you to pipe data to and from the request. Please note that .pipe() is used instead of .end()/.then() methods.

``` javascript
const request = require('superagent');
const fs = require('fs');

const stream = fs.createReadStream('path/to/my.json');
const req = request.post('/somewhere');
req.type('json');
stream.pipe(req);

```
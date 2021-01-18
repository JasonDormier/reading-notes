---
layout: post
title: "Node, Express, and API's"
permalink: /read-05
---
Jason D


* Node.js is a JavaScript runtime built on Chrome’s V8 JavaScript engine.
* The V8 engine is the open-source JavaScript engine that runs in Google Chrome.
* Node.js Lets Us Run JavaScript on the Server.
* Node.js is single threaded and ecery-driven.
* Node.js uses the libuv library to implement asynchronous behavior.
* Node.js is best for applications with some form of real-time interaction.

* `<Date()>` is old and clunky
* `<Temporal>` should be used instead.
```javascript
// exact time since the Unix epoch on 1 Janary, 1970 UTC
Temporal.now.instant();
Temporal.now.instant().epochSeconds;
Temporal.now.instant().epochMilliseconds;

// current time zone
Temporal.now.timeZone();

// time in current location, e.g.
// 2021-09-18T04:17:48.435068431-04:00[America/New_York]
Temporal.now.zonedDateTimeISO();

// time in another time zone, e.g.
// 2021-09-18T09:17:48.438068435+01:00[Europe/London]
Temporal.now.zonedDateTimeISO('Europe/London');

```
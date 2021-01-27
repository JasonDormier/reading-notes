---
layout: post
title: "Sending Form Data"
permalink: /read-13
---
Jason D

* Escape potentially dangerous characters.

* Limit the incoming amount of data to allow only what's necessary.

* Sandbox uploaded files.

* Set the method attribute to POST because file content can't be put inside URL parameters.

* Set the value of enctype to multipart/form-data because the data will be split into multiple parts
 
* Include one or more `<input type="file">`
---
layout: post
title: "Hashtables"
permalink: /class-23
---
Jason D

### Hashtables

* A data structure that utilize key value pairs. This means every Node or Bucket has both a key, and a value.

* We hash our key and determine the exact location where our value is stored, we can do a lookup in an O(1) time complexity. This is ideal when quick lookups are required.

* Hash maps take advantage of an array’s O(1) read access

* A hash map uses a “hash function” to place each item at a precise index location, based off it’s key.

* the hash function takes a key and returns an integer. We use the integer to determine where the key/value pair should be placed in the array.

* A hashtable traditionally is created from an array. 
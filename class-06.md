---
layout: page
title: "201.06 Reading Notes"
permalink: /201-R6/
---

## Class 6 Readings

### JavaScript Objects

* In an object, *variables* become *properties*; *functions* become *methods.*

* Within the object, property & method names are *keys* (which are unique per object)

* Object creation can be done through *Literal notion* (among other ways), like:
`var exampleObject = {
  exampleKey: exampleValue
};`

* Dot notation: `.` is the **member operator**; precedes property/method, like:
`exampleObject.ExampleKey`

* Bracket use: access object properties (note: not methods) like: `= exampleObject['exampleKey'];`

### Document Object Model

* Browser-side

* Models page in memory

* Composed of objects

* **Application Programming Interface**: facilitates communication between [script and browser?] *Note to self: review*

* Nodes in the DOM tree are accessed by the browser- element/attribute (same node), and text nodes (childless)

* DOM queries: methods that locate elements within the tree; can store store location in a variable. Minimizing node "travel time" through arrangement improves performance

### Primitives vs Objects in JS

* Objects include: Functions, Arrays, and Dates

* Assignment: when assigned to an object, a variable is *not* assigned to a value but rather a reference to a location in memory.

* Mutibility: primitives cannot be changed (only reassigned), while object references can. (example: string character values vs. array index values)

### Problem Domains

* Problem Domain: the use and context of the software to be written. Determining the requirements and bounds of a project can help to focus the actual code being written.

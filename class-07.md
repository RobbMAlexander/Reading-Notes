---
layout: page
title: "201.07 Reading Notes"
permalink: /201-R7/
---

## Class 7 Readings

### Domain Modeling

* Definition: use of conceptual models to represent a problem in order to focus planning or  communication about objectives and solutions

### Tables

* HTML element: `<table>`, with child `<tr>` defining rows and descendant `<td>` within bounding each cell's content. `<th>` marks headings (attribute `scope="row"` or `scope="column"` to define) (required even for blank cells for formatting purposes) Dimensions can be set entirely in HTML (sans CSS)

* (see *Ducket on HTML* p133 for more elements & attributes)

### Functions, Methods, Objects

* `this`: used for self-referential term within objects; allows for programmatic solutions to avoid hard-coding object references for each functional use

* Scope: Recall that globally defined variables and declared functions may be used/called within "smaller" scopes

* Arrays: arrays *are* objects; object properties can have arrays as property values

* Built-in objects: BOM; DOM; Global JS Obj.'s
  * Browser Object Model: models browser instance, with the current window and several child objects (current page; page history; current URL; browser info; device/output info)
  
  * Global Javascript Objects: Note capital letters (eg. `String` & `Date`); related methods usable across many objects,

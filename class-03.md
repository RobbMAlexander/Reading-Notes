---
layout: page
title: "201.03 Reading Notes"
permalink: /201-R3/
---

## Class 3 Readings

### Lists in HTML

* In HTML, 3 list types: **ordered** `<ol>` (numbered); **unordered** `<li>` (bullet points); **definition** `<dl>` lists (paired terms `<dt>` and definitions `<dd>`)

* Lists can be nested inside an unordered list (changed indentation & point iconography)

### Element "Boxes": in HTML

* CSS can adjust the appearance around elements via(more attributes in *Duckett* on HTML p300-329):
  * adjusting space around elements w/: Borders, margins, padding,
  * adjusting dimensions of elements: `height` ; `width`; `min-width`; `max-width`;
  * changing the texture and shape: `box-shadow`; `border-style`; `border-top-left-radius`

### Switch Statements

* Set multiple code blocks to run depending on the *switch value*

* Anatomy: `switch ()` evaluating a **Switch value** variable, followed by multiple `case` values and a `default` option, each broken by the `break` keyword and all in a single code block, like:
`switch (temp) {
  case 'High':
    adjust = 'cool';
    break;

  case 'Low':
    adjust = 'heat';
    break;

  default:
    adjust = 'off';
    break;
}`

### Type Coercion

* **Type coercion**: Conversion of one JS data type to another (such as string values to numbers)

* **Truthy** & **Falsy**: Values treated as true or false, respectively, when coerced. Like, for True: non-zero numbers; strings. For False: numeric zero; NaN; empty values; unassigned vaiables.

* Use `===` & `!==` to limit unintended valuation.

* Short-circuits: logical operators stop as soon as evaluating the minimum required Booleans,  truthy-s, or falsy-s (latter two will not return a Boolean)

### Loop Counters

* Variable initialization: set at `0` (during or after declaration), (often named `i`)

* Can be set to run a # or variable of times

* `i` value increments as w/ `i++`

* Anatomy: like
`for (counter = 0; counter < 12; i++) {//code to be run twelve times
}`

* Keywords: `break` terminates and sends interpreter outside loop; `continue` maintains and rechecks condition for `true` evaluation

### `for` & `while` Loops

* `for` can be used to loop through an array's values

* `while` can be used to set code for an indetermined number of executions

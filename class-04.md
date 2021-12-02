---
layout: page
title: "201.04 Reading Notes"
permalink: /201-R4/
---

## Class 4 Readings

### Links in HTML

* `<a>`: creates links accessible in rendered page by clicking elements between tags.

* Anatomy: `<a href="URLHERE">CLICKABLECONTENT</a>`

* Design tips: use relevant text/content to link (keep searching/finding in mind)

* Internal links: Do not need domain in URL (*Relative URL*); Can use relative filepath-- good reason to keep organized tree of directories for site.

* Add `mailto:` in front of URL for link to email address (browsers will load email program)

* `target-"_blank"` attribute at end of opening tag opens link in new window (...not good practice).

* Use `#` followed by id attribute of specific page element at *end* of tag to link to that element.

### Page Layout

* Conteptual tips:
  * Build with "blocks": relative positions, containers, z-indexing, floats,

  * Keep in mind which CSS behaviors are defaults (width stretching, vertical margins, etc.)

  * *Absolute* vs. *Relative* positioning (may ease or complicate multiplying elements, future-proofing)

  * Consider variety in screen dimensions, input/selection types (an advantage to not using absolute dimensions)

  * *Liquidity*: ability of a page to dynamically handle window resizing

  * Modularity: sheets can be used per section for very distinct styling

### Functions in JS

* See also: [102 Unit 7 Notes](https://robbmalexander.github.io/Reading-Notes/102-07/)

* Functions: grouped, sequential statements.

  * Anatomy: `function functionNameHere(parameterHere, andMoreHereAndSoOn) {satementshere;}`
  
  * Must be *declared* initially

  * Can be *called* later in code to invoke all statements using the function name and any paranthetical parameters

  * **Parameters**: data passed to a function

  * Can return arrays

  * Can be interpreted as an expression

  * **iffy**: "Immediately Invoked Funtion Expressions" (IIFE) that can be used to store an expression into a variable as declared rather than used for calls.

* Scope: within the block of a function, (keep track of braces!`{}`) defined variables will not exist outside of this **scope**.

  * Memory use: Global variables are more memory-intensive. (and must be conflict-proofed for naming)

### Pair Programming

* **Pair Programming**: method of coding by assigning two developers to the same exact coding task for mutual advice, insight, oversight, proofreading, and engagement.

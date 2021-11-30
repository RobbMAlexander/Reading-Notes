---
layout: page
title: "201.02 Reading Notes"
permalink: /201-R2/
---

## Class 02 Readings

### Text

* HTML uses graded headings (`<h1>` through `<h6>`) that default to decreasing text sizes

* Paragraphs (`<p>`) separate text, and new paragraphs will begin on a new line. Text within can be bolded (`<b>`), italicized (`<i>`) and further styled with tags around specific text (following standard element rules) (see *Duckett* on HTML p 45-48)

* Browsers use **white space collapsing** to display 1 space when 2+ are continuous in code

* Content management systems may add markup automatically to pasted text-- plain text editors can serve as a "clean" copy source to avoid this

* Semantic Markup: Used to describe or communicate about content for data or other programmatic interpretation rather than user view (eg: `<cite>`;`<strong>`)

### CSS (see also [102 Reading Notes](https://robbmalexander.github.io/Reading-Notes/102-05/))

* Cascading Style Sheets: controls visuals of content and text

* Inline (selectors w/ elements); Internal (`<style>` section for whole page); external (pulled from other file-- useful for templating, aids load times in some circumstances)

* Cascading priority: Marked Important (`!important`); More Specific; Later

### JavaScript (see also [102 Reading Notes](https://robbmalexander.github.io/Reading-Notes/102-06/))

* Anatomy: **Statements** (individual instructions) separated by `;`'s; **Code Blocks** separated by curled braces (which may contain multiple statements)

* Comments: Use `//` for single-line, `/*` to `*/` for multi-line.

* **Variables** named, stored data that may be recalled (short-term) or adjusted through statements

### JavaScript Data Types (not exhaustive)

* Numeric: can include integers, decimals,

* String: text, indicated by closed quotes (`'string'` or `"string"`). No breaks in a string. Use *escape characters* (`\`) to safely use meaningful JS characters within a string.

* Boolean: `True` or `False`

* note: JS doesn't need data type specified when variables are declared

### JS variable naming restrictions

* Begins with letter, `$`, or `_`

* Contains letters, `$`,`_`, and numbers. *NO* `-` or `.`

* Keywords and reserved words can't be used

* Case-sensitive

* "camel case": capitalize *only* words after initial word in variable name

### Arrays

* Variable that stores multiple values (lists) separated by `,`'s within brackets, like `soup = [355, 'Chopped Mushrooms', False];`

* Declared like other variables

* Can include various data types

* Ordering: values accessed in left-right order (first position is position `0`), like: `tastyIngredient = soup[1];`, including for adjustment or reassignment. "length" property is number of arrayed items (can be accessed with `.length`, like: `soup.length`)

### Decisions & Loops (see also [102 Reading Notes](https://robbmalexander.github.io/Reading-Notes/102-08/))

* Comparison operators evaluate a value for `true` or `false` Boolean: `==` (equality); `!=` (inequality); `===` (strict equality requiring same data type); `!==` (strict inequality) `>` ; `<` ; `>=` (greater than/equal to); `<=` ;

* Logical operators test one or more conditions *until* a Boolean result: `&&` (logical And); `||` (logical Or); `!` (logical Not)

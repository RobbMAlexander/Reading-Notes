---
layout: page
title: "201.09 Reading Notes"
permalink: /201-R9/
---

## Class 9 Readings

### Forms

* HTML elements used to allow for easy data input from users

* Examples (from *Duckett on HTML*): Online shopping, registrations, search engines

* Input formats
  * Text: 1/more lines of text (possibly hidden as it is input)

  * Multiple-choice: buttons & drop-downs

  * "Clickables" (to do something)

* HTML anatomy (refer to *Ducket on HTML* p151)

  * `<form action="urlforpagereceivinginfo" method="get">` the `method` can also be `post`.
  
  * `<input type="" name="" maxlength="">` `type` values may be `text` for single-line input, `password` for blocked-out; `name` is an identifier for particular input field, `maxlength` caps character count;

  * `<form action=""><textarea name=""></textarea></form>` Note closing tag required. Displays given text before user adds input.

### Lists, Tables, & Forms

* Can be styled w/ CSS (examples: list bullets/numbers/icons; table cell/row shading) see *Ducket on HTML* p335

### Events

* Variety of inputs that can be reacted to programmatically

  * Examples: page loading; page scrolling; key input; mouseover

* Events **fire** / have been **raised**; scripts **trigger**

* JS uses DOM manipulation to interact with/based on firing events

* Can -- *but should not* -- use deprecated system of HTML handlers

* Event listeners: more recent browsers use this method approach to linking elements to events and then calling functions

---
layout: page
title: "201.12 Reading Notes"
permalink: /201-R12/
---

## Class 12 Readings

### Chart.js

* Chart.js: HTML5 plugin based in JavaScript that charts images.

  * (after sourcing the `Chart.min.js` script in HTML head) Use `<canvas>` element with `id` and `width` & `height` dimension attributes to set bounds of chart-able area on page

* JS variables and some Chart-specific keywords are used to define and adjust graphs, like (for bar graph in brown w/ 3 data points):
`var barData = {
 labels: ["Snickers", "3 Musketeers", "Reese's"],
 datasets : [
   {
fillColor : "#6e655c",
strokeColor : "#141413",
data : [11,6,20]
   }
 ]
}`

* Can be styled by CSS, but this has limited/unintended effects on the displayed canvas element itself

* Alt text or images can be incorporated for accesibility purposes

### Dimensionality & geometry in Canvas API

* Defaults to Cartesean grid (1px x 1px)

* Only two shapes: rectangle and *path*
  * Paths may serve to construct non-rectilinear shapes

* several functions for rectangular constructions, with parameters of (x position, y position, width, height)
`function rect() {
  var canvas = document.getElementById('canvas');
  if (canvas.getContext) {
    var ctx = canvas.getContext('2d');

    ctx.fillRect(10, 10, 50, 50);
  }
}`

* (refer to [MDN](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes) for path code & use)

### Color & "Inking"

* Takes common color code values (HEX, rgb(a), CSS-recognized color names) and alpha values;

* Can use gradients

* Can select "inclusive" and "exclusive" lines to/around points

* Can use simple animated borders & rotation

* (refer to [MDN](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors) for color-related code & use; [MDN](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text) for text illustration)

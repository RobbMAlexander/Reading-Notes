---
layout: page
title: "201.05 Reading Notes"
permalink: /201-R5/
---

## Class 5 Readings

### Images in HTML

* Sample anatomy:
  
  * `<img src="sourceURLhere" alt="altTextHere" title="imagetitlehere."/>

  * Remember: empty element (no closing tags
  
* attributes: `width=` ; `height=`

* Tag placement matters: (see *Duckett* on HTML p101)

* Some deprecated tags controlled attributes now handled via CSS

* Image file properties:

  * dimensions

  * resolution (72 ppi is recommended for web pages)

  * file formats (jpeg, gif, png) have appearance & performance differences
    * JPEG: handles fine color differences

    * GIF / PNG: preferable for logos & "flat color" images

    * GIF can handle animations

    * vector images: use grid of points with lines extended, then colored in, avoiding scaling issues

* Partial transparency (in GIF and PNG)

* `<figure>`: HTML5 addition for associating images w/ captions

### Color in CSS

* Feed in coded # according to various value systems (Hex, RGB, HSLA etc.) or defined color names. (note: some use alpha values for opacity)

* Design tips: use high contrast,

### Text in CSS

* Font-family: property that allows for a tiered list of fonts, allowing for design not hinging on a single assumed typeface

* Sizing: by pixel (`px`); percentages; "EMs" (`em`) = 1 "m"

* Can convert from traditional type sizing to absolute units

* `:link` & `:visited` : color hyperlinks (and already visited ones)

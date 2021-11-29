---
layout: page
title: "201.01 Reading Notes"
permalink: /201-R1/
---

## Class 01 Readings

### Web Connection Outline

* User-end **browser** connects via **ISP** to **DNS** to get **IP address** for site. Web server sends **page** to **browser**

### Web Page Structure

* Consider web pages as documents-- for readability and intention-- in parallel with analog equivalents

* HTML structures pages using `<elements></elements>`that define, categorize, and arrange the text and other content of a site. (see 102 Reading notes, or Chapter 1 in *Ducket* on HTML)

### HTML Versions

* HTML 4: Circa 1997; some styling features that are discouraged in favor of CSS solutions

* XHTML 1.0: Circa 2000; based in XML language, necessitating closing tags (for most elements), case-sensitivity, and syntax changes (attributes, nesting tags); usable with other data formats

* HTML 5: Some tags don't need closing; new elements & attributes; In progress

* `<!DOCTYPE>` and similar elements declare HTML version to browser

* `<-- comment formatting works like this -->` ; comments viewable in source but not browser view

* `<iframe>`: "Inline Frames" : sub-windows for separating content with attributes: `src` (url sourced); `height` & `width`; `scrolling`; `frameborder`; `seamless`

* `<meta>`: within `<head>`, communicates to search engines

### HTML5 Layout

* Updated elements: within or replacing`<div>` sections (aids some layout & accesibilty features);groupings like `<hgroup>` to treat elements as single block; `<figure>`&`<figcaption>`for visual, non-textual content;

* Use CSS code (seen in *Duckett HTML* p442) for backwards compatibility of HTML5 elements

### Design

* Keep audience & usage in mind for structure, style, accesibility, and functionality

### JavaScript & Basics of Programming

* For browsers-- Adding JS can take user input to affect rendered page, store and use data live in browser.

* **Scripts:** specific codes that instruct the activity of a browser or other program

* Tips: Keep overall goal of script in mind; break things down to components;

* Coding language revolves around **Vocabluary** and **Syntax**

* **Objects:** "thing" of data; with **properties** to it (**name** & **value**). (eg, web page in browser w/ various elements)

* **Event**: activation of a certain section of code (eg, clicked elements of a web page leading to changed output)

* **Method**: process by which an action is achieved via code (eg, JS functions)

* New web content via JS (like `document.write()`)

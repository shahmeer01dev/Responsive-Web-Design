# Cafe Menu

---

## Overview
The "Cafe Menu" project showcases a simple web page for a cafe, listing various coffee and dessert items along with their prices. The page uses basic HTML for structure and CSS for styling.

---

## HTML Structure
### 1. Doctype and Language
The document begins with a ```<!DOCTYPE html>``` declaration, specifying the document type and ensuring standards-compliant rendering.
The ```<html>``` tag includes the ```lang="en"``` attribute, indicating that the content is in English.

### 2. Head Section
The ```<head>``` section contains meta-information about the document:
```<meta charset="utf-8" />``` specifies the character encoding.
```<meta name="viewport" content="width=device-width, initial-scale=1.0" />``` ensures proper scaling on all devices.
```<title>Cafe Menu</title>``` sets the title of the page, which is displayed on the browser tab and used by search engines.
```<link href="styles.css" rel="stylesheet"/>``` links to the external CSS file for styling.

### 3. Body Section
The ```<body>``` contains the main content of the page:
A ```<div class="menu">``` element wraps all the content, which helps in organizing the layout.
```<main>``` contains the primary content, including the header, menu sections, and items.
```<h1>CAMPER CAFE</h1>```: The main heading of the page.
```<p class="established">Est. 2020</p>```: A paragraph indicating the establishment year.
```<hr>```: A horizontal rule to separate sections.
Two ```<section>``` elements:
Coffee Section: Lists various coffee flavors with corresponding images and prices using ```<article>``` elements.
Desserts Section: Similar structure for desserts.
```<footer>``` includes additional information:
A link to the FreeCodeCamp website.
An address paragraph for the cafe.
  
### 4. Use of Semantic Elements
```<article>``` elements are used to group related content together, making the structure clear and enhancing accessibility.

---

## CSS Styling

### 1. General Styling
The background image for the page is set using ```body { background-image: url(https://cdn.freecodecamp.org/curriculum/css-cafe/beans.jpg); }```.
A sans-serif font is applied across the page for a clean, modern look.
Padding and centering are applied to ensure content is well-spaced and visually appealing.

### 2. Typography
The main heading (h1) and section headings (h2) have specific font sizes for emphasis.
The p.established class is styled with italic font to differentiate it from regular text.

### 3. Layout
The .menu class centers the main content with a fixed width, background color, and padding, providing a visually distinct area for the menu items.
Images are centered using ```img { display: block; margin-left: auto; margin-right: auto; }```.

### 4. Link Styling
To style visited links differently, a pseudo-selector ```a:visited { propertyName: propertyValue; }``` can be used.
Additional Notes
The ```<div>``` element is used primarily for layout purposes, unlike other semantic elements like ```<section>``` and ```<article>```.
The ```<title>``` element is essential for SEO and displaying the page's title in the browser tab.
Semantic elements like ```<article>```, ```<section>```, and ```<footer>``` enhance the document's accessibility and structure.

***

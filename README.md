# Blog Preview Card

## Table of contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Acknowledgments](#acknowledgements)
  
## Overview

This is a solution to the [Blog Preview Card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

### The challenge

Users should be able to:
- See hover and focus states for all interactive elements on the page

### Screenshot

![screenshot](https://github.com/IrieBee/fem-blogPreviewCard/blob/main/images/screenshot.jpg)

### Links

* Solution URL: https://github.com/IrieBee/fem-blogPreviewCard
* Live Site URL: https://IrieBee.github.io/fem-blogPreviewCard/

## My Process

### Built with

  * Semantic HTML5 markup
  * CSS custom properties
  * Flexbox

### What I learned

* When h1 is a link => wrap link in h1 instead of h1 in link.
```html
<h1><a href="http://">HTML & CSS foundations</a></h1>
```
* Add favicon to the head of html.
```html
<link rel="shortcut icon" href="images/favicon-32x32.png" type="image/x-icon">
```
* Move 'main' to the center  and 'footer' to the bottom
```css
body {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
}
main {
    margin: auto;
}
```
* Wrap background in h2 around text
```css
h2 {
      display: inline-block;
}
```
* Make image responsive
```css
main :first-child {
    width: 100%;
}
```

### Continued development

 * Flexbox.
 * Selectors: descendant combinators

## Useful resources

* https://www.sitepoint.com/community/t/how-to-make-h1-h2-etc-as-links/3004 - wrapping link in 'header
* https://www.w3schools.com/html/html_favicon.asp - favicon

## Acknowledgements

* [Odin project](https://www.theodinproject.com/)
* [Frontend Mentor](https://www.frontendmentor.io/home)
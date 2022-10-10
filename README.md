# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### Screenshot

#### `Desktop` Design Preview

![](/screenshot/order-summary-card-desktop.png)

#### `Mobile` Design Preview

<p align="center">
<img height="667" width="375" src="/screenshot/order-summary-card-mobile.png"/>
  </p>

### Links

- Site URL: https://simple-website-with-html-and-css-position.vercel.app/

## My process

### Built with

- Semantic HTML5 markup
- Cube CSS
- CSS custom properties

### What I learned

While creating this project I learned how to use :is css property.

```css
/* .button[data-type="primary"]:hover, 
.button[data-type="primary"]:focus) */
.button[data-type="primary"]:is(:hover, :focus) {
  background-color: var(--clr-primary-300);
}
```

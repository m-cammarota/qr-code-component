# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

The challenge is to build a QR code component that is as similar as possible to the original design.

### Screenshot

![Design](./preview.jpg)

### Links

- [Solution repo](https://github.com/m-cammarota/qr-code-component/)
- [Live Site](https://m-cammarota.github.io/qr-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS 
- Flexbox

### What I learned

I learned how to create a component by following a style-guide.

- How to use flexbox to align elements.
- How to use variables to implement the style-guide.
```css
:root {
    --color-slate-300: hsl(212, 45%, 89%);
    --color-slate-500: hsl(216, 15%, 48%);
    --color-slate-900: hsl(218, 44%, 22%);
}
```
- How to use calc() to perform operations
```css
.qr-code {
    width: var(--card-width);
    height: var(--card-width);
    border-radius: calc(var(--card-border-radius)/2);
}
```
### Continued development

I would like to learn how to use figma to understand the guidelines more quickly.

### Useful resources
- [W3Schools](https://www.w3schools.com/css/default.asp) - Learn and practice.

## Author

- Frontend Mentor - [@m-cammarota](https://www.frontendmentor.io/profile/m-cammarota)


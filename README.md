# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

- The aim is to improve the speed of delivery and accuracy of the end product.

## My process

- Think about how to layout the elements- what came to mind was position: absolute for the main card, then display: flex for the items structured as a column. Some consideration as to the number of containers to use.
- To process took two iterations and about 3hrs working on and off and researching.

### Built with

- Semantic HTML5 markup
- CSS custom properties and media queries
- Flexbox

### What I learned

- See below regarding absolute position: set the parent element to relative, set the child element to position: absolute; and it will snap to the containing block element starting from the top left by default. Declare top/bottom/left/right: 0. This assigns the space available to it i.e. the entire space of the parent element if set to 0. This inner element will expand (or shrink?) to fit the space of the containing block element. Set width and height to 50% which will reduce the element by 50% of the parent element within the declared space. Set margin: auto; to center the child element horizontally in the parent container. 

### Continued development

- start with mobile first. Need to find a more efficient way of scaling up the element sizes from mobile -> desktop.
- Sigificant time spent deliberating over layout / positioning of the elements. Need to revisit normal flow, positioning principals especially absolute positioning.
- Time consumed on responsive design trial and error.

### Useful resources

- Googled how to center div within a div horizontally and vertically
- https://www.youtube.com/watch?v=QGKO0PGzFXQ&ab_channel=KevinPowell
- https://codepen.io/kevinpowell/pen/NWjBQQm

## Author

- wkan17012021

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

  - First exercise of Front-end Mentor.
  - Use of the grid to place the elements inside the main message and "transform:translate()" and "position:absolute" rules, to center it. 

### Screenshot

![](./screenshotexer1.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- CSS custom properties
- CSS Grid

### What I learned

Another method to to center an element. This is using the "transform:Translate()" rule. While my person knows that with flexbox is more easy to apply the desired effect, it was wished to execute it through what it seems to be, the second most common method to do it.

First, you have to position the element to absolute and move it 50% from top and from left. This later, only would center the top left corner of the element, hence with the "transform" property you "translate" the element "-50%" from top and left. When used as values of the translate function, the "%" values are taken from the element itself, so "Translate(-50%,-50%)" will move 50% of itself to the top and to the left, thus the element core, or center point, then will be in the center of the screen.

it was not too clear what the favicon icon was for. It result, that you may show this icon in the title tab that identify the webpage. To include it has to introduce the command "<link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">".  

### Continued development

It is a matter of concern to discover if to use an alternative to grid, would improve the code and the responsiveness of the page.

### Useful resources

- https://css-tricks.com/snippets/css/complete-guide-grid/#aa-grid-properties - This helped me for as a guide to the several properties that can be used in grid



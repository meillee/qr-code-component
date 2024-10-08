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

## Overview

### Screenshot

![](./design/screenshot.png)

### Links

- Solution URL: (https://qr-code-component-xi-blond.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- Going only 1 month without coding is enough for it to feel rusty and awkward.

- Even with small projects like this, wireframing helps me visualise the structure of the HTML DOM and organisation of HTML tags to have a smoother coding experience.

- *max-width: 100%;* on images makes them fit within their containers.

- Although the border radii aren't pixel-perfect, I was able to follow this nested element border-radius formula: (outer-radius) = (inner-radius) + (padding between elements)

- The box-shadow property can have up to 4 length values and a colour!
(offset-x, offset-y, blur-radius, spread-radius, color)

- *box-sizing: border-box;* solved the vertical scrollbar problem that I was having.

- I wanted to experiment with using the **ch** unit to restrict the max-width of the main element. I think it worked pretty well and allowed me to easily get the line length exactly the same as the design.

### Continued development

- Footers are hard. Initially I tried flexbox combined with *margin-top: auto;* and it pushed the QR code component to the top when I wanted it vertically centered in the viewport. I couldn't find any answers on Stack Overflow so for now, I'm using fixed position to stick the footer to the bottom. It's not exactly what I want, but it works fine for this scenario. Something to look into for future projects.

### Useful resources

- [Kevin Powell's Guide to Responsive Design](https://www.youtube.com/watch?v=x4u1yp3Msao)

- [Kevin Powell's Nested Border Radius](https://www.youtube.com/shorts/D0lIR1qVJOk)

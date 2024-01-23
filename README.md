# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Github Link](https://github.com/Kansoldev/QRCode-FEM)
- Live Site URL: [Live site](https://kansoldev.github.io/QRCode-FEM/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox

### What I learned

I learnt from this project, as simple as it is, where overflow: hidden can be useful. I figured out in my css code that after I gave the card-header class a border-radius, it wasn't showing

```css
.card-header {
  border-radius: 10px;
}
```

I found out that it is because the image is covering the border-radius from showing (I figured this out by applying border: 2px solid red;), that was when I used overflow: hidden, and it gave me the result i was looking for

```css
.card-header {
  border-radius: 10px;
  overflow: hidden;
}
```

This helped me hide the image from covering the border-radius, because the image was essentially overflowing from the .card-header container.

## Author

- Frontend Mentor - [Kansoldev](https://www.frontendmentor.io/profile/Kansoldev)
- Twitter - [Kansoldev](https://www.twitter.com/Kansoldev)

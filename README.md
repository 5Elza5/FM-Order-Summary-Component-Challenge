# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshots

Desktop version

![](./images/screenshot1-desktop.png)

Mobile version

![](./images/screenshot2-mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

```css
/* Price Section */

.price-container {
  border-radius: 10px;
  margin-bottom: 30px;
  padding: 20px;
  background-color: hsl(225, 100%, 98%);
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.img-and-price {
  display: flex;
  align-items: center;
  gap: 20px;
}
.price-container span {
  color: var(--Desaturated-blue);
}
.price-container a {
  color: var(--Bright-blue);
}
.price-container a:hover {
  text-decoration: none;
  opacity: 0.7;
}

/* Media queries */

@media screen and (max-width: 490px) {
  body {
    background: url(/images/pattern-background-mobile.svg) transparent no-repeat;
    background-size: 100%;
    background-color: var(--Pale-blue);
  }
  .wrapper {
    width: 325px;
  }
  .content {
    inline-size: 275px;
  }
}
```

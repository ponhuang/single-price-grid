# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

Desktop
![](screenshot/desktop.png)

Button Effect
![](screenshot/hover.png)

Mobil
![](screenshot/mobile.png)

### Links

- [Solution URL](https://github.com/ponhuang/single-price-grid)
- [Live Site URL](https://ponhuang.github.io/single-price-grid/)

## My process

### Built with

- Semantic HTML5 markup
- node-sass install
- SCSS custom properties
- CSS Grid
- Desktop-first workflow

### What I learned

1.) set overflow: hidden to the container, then it will show the border-radius properly.

```css
.container {
  overflow: hidden;
}
```

2.) When I set grid columns / rows to 50%, and it has text overflow issue. (the content didn't stay inside the padding) Change the value to 1fr and it fixed this problem.

```css
.container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr 1fr;
}
```

3.) Use all: unset to make the button works properly in desktop and mobile version. Also we need to give text-align property as well.

```css
.btn {
  all: unset;
  text-align: center;
}
```

## Author

Pon Huang

- Instagram - [Pon Huang](https://www.instagram.com/ponhuang/)
- Art Blog - [une felt](https://une722.wordpress.com)

## Acknowledgments

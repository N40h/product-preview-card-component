# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop](./design/my-solution.png)

### Links

- Solution URL: [Solution](https://github.com/N40h/product-preview-card-component)
- Live Site URL: [Live Site](https://tangerine-pastelito-ab4e47.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Using gap with flexbox to separate some contents is very useful

```css
.content-right {
	width: 60%;
	display: flex;
	flex-direction: column;
	gap: 25px;
	padding: 30px 35px;
	background: var(--white);
	border-radius: 0 10px 10px 0;
}
```

# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Social links profile solution](#frontend-mentor---social-links-profile-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Solution for the challange](./design/screenshot.png)

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/social-links-profile-YKuBHPAZBT)
- Live Site URL: [GitHub Pages](https://pellia.github.io/fm-social-links-profile/)

## My process

### Built with

- Semantic HTML
- CSS | Grid | Flex | Custom Properties | Media Queries
- Mobile-first workflow
- Responsive Design

### What I learned

I learned about the ```font``` shorthand property, which allows you to set all font-related styles in a single declaration. I combined this with CSS custom properties to define text presets, so I only needed to assign the relevant font style using one of the predefined custom properties.

Here are the different text presets:

```css
  /* Typography */
  --line-height: 150%;
  --text-preset-1: 700 24px / var(--line-height) var(--font-inter);
  --text-preset-2: 400 14px / var(--line-height) var(--font-inter);
  --text-preset-2-bold: 700 14px / var(--line-height) var(--font-inter);
```

Using the ```font``` shorthand property in combination with a preset:

```css
.card__person-name {
  font: var(--text-preset-1);
  ...
}
```

### Useful resources

- [MDN font property](https://developer.mozilla.org/en-US/docs/Web/CSS/font) - A CSS shorthand for setting up all the different properties of an font element.

## Author

- Website - [Rupinder Singh](https://www.rupinder-singh.com/)
- Frontend Mentor - [@Pellia](https://www.frontendmentor.io/profile/Pellia)


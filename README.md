# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Stats_preview_card_component](./Stats_preview_card_component.png)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- CSS Modules


### What I learned

## CSS
### 1.How to add color onto the jpg image
```css
img {
  mix-blend-mode: multiply;
}
```
### 2.how to divide code into files/modules
```css
@import "style.css";
```
- Note: CSS @import does not work when deploying the project into GitHub Pages. Apparently, GitHub Pages seem to ignore underscores. Sass import, on the other hand, will work because Sass files will be compiled into a CSS file.



### Continued development

# Responsive Design:
The card component does not shrink while reducing the screen size.
  - How to shrink the component dynamically based on the screen size

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/) - This helped me better understand how to use flex and grid for positioning.
- [stackoverflow](https://stackoverflow.com/) - This website shares different approach to certain problems. In this challenge, this helped me figure out how to add color on the image using the mix-blend-mode property.

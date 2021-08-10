# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![desktop](/my_screencaps/desktop.png)
![hover](/my_screencaps/hover.png)
![mobile](/my_screencaps/mobile.png)

### Links

- [Solution URL](https://github.com/jmgisele/frontend_3-column-soln/)
- [Live Site URL](https://jmgisele.github.io/frontend_3-column-soln/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This is my first html/css project in a while, and my first ever trying to implement someone else's design! It was a challenge to have to push through sections I wasn't sure how to implement rather than just finding a different look based on what I already knew, the way I do when implementing my own designs. I always have a hard time with centering items in flexbox. I also wasn't sure what best practices are in terms of responsive design--- I started out with the center flexbox completely resizing depending on the viewport, but this caused a lot of issues with smaller and larger viewports. I could have messed around with responsively changing the font size and spacing, button size, etc to grow alongside the viewport, but I decided to go the more simple route and have a mostly static-sized  flexbox for simplicity, with a couple media queries to handle a vertical flexbox for smaller screens.

### Continued development

I'm excited to get more of a handle on how much "flex" to give in responsive design vs just hard coding in the sizes I want and making sure they look good in various viewport sizes. I'd also like to eventually learn a CSS preprocessor-- hopefully I can find one with more extensive support for variables, so I can do things like have a button inherit the color of its parent element, rather than having to individually handle each button's color manually like I did here. I don't believe it's possible to inherit this way with vanilla CSS so hopefully I can find a tool to do this so my CSS is less redundant. 

## Author

- Github - [@jmgisele](https://github.com/jmgisele)
- Frontend Mentor - [@jmgisele](https://www.frontendmentor.io/profile/jmgisele)

## Acknowledgments

Thanks to FEM for the challenge and freecodeacademy & colt steele's Udemy course for teaching me the basics.
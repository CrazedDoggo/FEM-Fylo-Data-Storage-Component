# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://github.com/CrazedDoggo/FEM-Fylo-Data-Storage-Component](https://github.com/CrazedDoggo/FEM-Fylo-Data-Storage-Component)
- Live Site URL: [https://crazeddoggo.github.io/FEM-Fylo-Data-Storage-Component/](https://crazeddoggo.github.io/FEM-Fylo-Data-Storage-Component/)

## My process

As standard, I began by building the components themselves and then dealing with the layout.

### Built with

- Semantic HTML5 markup
- Flexbox
- Grid
- CSS custom properties
- Mobile-first workflow

### What I learned

I encountered and resolved a few issues in this project. These include:

1. Positioning my cards in the middle while also allowing them to grow and shrink.
2. Centering absolutely positioned elements.
3. Resetting the pop-up notification's (187 GB LEFT) positioning for the desktop model.
4. Creating a triangle.

For the **first** issue, I resolved such by adding a div tag to wrap my cards. This allowed me to have the wrapper stretch to 100%, but automatically margin the cards inside of it. It also allows for padding to be applied to always have space around the cards. Centering the cards inside the wrapper instead of the body resolved the issue with them not stretching.

For the **second**, most of it was centering the absolutely positioned element. Used a simple online resource (see useful resources) to get a solution.

For the **third**, I Googled and discovered that simply setting a position to "auto" reset it and that these were the default values for positions.

For the **fourth**, I found it from CSS-Tricks and messed around with the values to fit it in.

### Useful resources

- [Centering Absolute Positioned Elements](https://stackoverflow.com/a/25776315)
- [CSS Shapes](https://css-tricks.com/the-shapes-of-css/)

## Author

- GitHub - [Crazed Doggo](https://github.com/CrazedDoggo)
- Frontend Mentor - [@CrazedDoggo](https://www.frontendmentor.io/profile/CrazedDoggo)
- Twitter - [@DoggoCrazed](https://www.twitter.com/DoggoCrazed)
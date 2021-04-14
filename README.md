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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](images/challenge-screenshot.png)

### Links

- Solution URL: [frontendmentor-3-column-card](https://tagabaza.github.io/frontendmentor-3-column-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive Design

### What I learned

The primary lessons I took from completing this challenge revolved around the layouts and positioning of different elements. Figuring out the different ways of centering divs...

```css
.card{
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);,
}
```
or adjusting layouts appropriately for varying screen sizes...
```css
@media screen and (max-width: 1000px) {
  .card{
    flex-direction: column;
    transform: translate(-50%, -25%);
    width: 80%;
  }
}
```

### Continued development

A thought for the future for me is to possibly start building out websites with a mobile first strategy. I initially found it quite difficult to scale down my website layout to seamlessly change between screen sizes. I think that creating the layout for smaller screens first benefits me as a developer as it would be easier to refactor my code for bigger sizes. Plus it means that the user experience is consistent throughout.


### Useful resources

- [CSS-Tricks: Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me understand flexbox in detail, giving out an in depth in its entirety; covering the background, properties, patterns, terminology and of course demos.


## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)

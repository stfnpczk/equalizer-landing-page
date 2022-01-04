# Frontend Mentor - Equalizer landing page solution

This is a solution to the [Equalizer landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/equalizer-landing-page-7VJ4gp3DE). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

![Design preview for Meet landing page](./images/preview.jpg)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  <!-- - [Continued development](#continued-development) -->
  - [Useful resources](#useful-resources)
- [Author](#author)
<!-- - [Acknowledgments](#acknowledgments) -->

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links


- [Frontend Mentor - solution URL](https://www.frontendmentor.io/solutions/equalizer-landing-page-wWXCg8Hou)
- [Live Demo](https://stfnpczk.github.io/equalizer-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- BEM notation
- SCSS
- Flexbox
- Mobile-first workflow

### What I learned
In this challenge I learned more about layout, specifically the  positioning of overlap patterns and background images.
- `background property:` 

```scss
 .bg-black {
    background-color: $black;
    background-image: url(../assets/bg-pattern-2.svg);
    background-repeat: no-repeat;
    background-position: top -1.5625rem left -3.125rem;
    background-size: 17.5rem 26.25rem;
 }
```

- `multiple background images:` notation for setting multiple images in html elements --> [css-tricks article](https://css-tricks.com/css-basics-using-multiple-backgrounds/)

```scss
body {
  background-image: 
    url(image-one.jpg),
    url(image-two.jpg);
  
  background-position:
    top right, /* this positions the first image */
    bottom left; /* this positions the second image */
  
  background-repeat:
    no-repeat; /* this applies to both images */
}

```


### Useful resources

- [using multiple backgrounds --> CSS-Tricks ](https://css-tricks.com/css-basics-using-multiple-backgrounds/) 

- [background property --> MDN ](https://developer.mozilla.org/en-US/docs/Web/CSS/background)

## Author

- Frontend Mentor - [@stfnpczk](https://www.frontendmentor.io/profile/stfnpczk)

<!-- - Website - [Add your name here](https://www.your-site.com) -->
<!-- - Twitter - [@yourusername](https://www.twitter.com/yourusername) -->

<!-- ## Acknowledgments
**ADD TEXT**
This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit. -->

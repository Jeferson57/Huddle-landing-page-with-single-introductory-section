# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./images/screenshot-Huddle-landing-page.png)

### Links

- Solution URL: [Repo](https://github.com/Jeferson57/Huddle-landing-page-with-single-introductory-section.github.io)
- Live Site URL: [Page](https://jeferson57.github.io/Huddle-landing-page-with-single-introductory-section.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first 
- Sass
- Responsive Design

### What I learned

For first time, I use the sass preprocessor. I learned Variables, Nesting and Mixins 

```scss
// Variables
$primary-color: hsl(257, 40%, 49%);

// Nesting
.header-container {
    width: 90%;
    margin: auto;
    
    img {
        width: 115px;
        margin: {
            block-start: 25px;
            block-end: 70px;
        }
    }
}

// Mixins
@mixin style-titleh1 ($size, $weight, $text-align) {
  font: {
    size: $size;
    family: 'Poppins', sans-serif;
    weight: $weight;
  }
  color: $white;
  text-align: $text-align;
}
```

### Continued development

I loved Sass. I think that i contiued development resposive sites with my new superpower.

### Useful resources

- [Example resource 1](https://youtu.be/rDBzoq86SXY)
- [Example resource 2](https://sass-lang.com/guide)

## Author

- Website - [Jeferson](https://github.com/Jeferson57)
- Frontend Mentor - [@Jeferson57](https://www.frontendmentor.io/profile/Jeferson57)
- Twitter - [@Jeferso06531446](https://twitter.com/Jeferso06531446)

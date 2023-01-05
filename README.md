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

desktope
![desktop](./screenshots/Screenshot%202023-01-04%20at%2016-05-24%20Frontend%20Mentor%20Huddle%20landing%20page%20with%20single%20introductory%20section.png)

mobile
![mobile](./screenshots/Screenshot%202023-01-04%20at%2016-04-38%20Frontend%20Mentor%20Huddle%20landing%20page%20with%20single%20introductory%20section.png)

### Links

- Solution URL: [solution URL here](https://github.com/AlanLopRey/huddle-landing-page-with-single-introductory-section-master)
- Live Site URL: [live site URL here](https://alanloprey.github.io/huddle-landing-page-with-single-introductory-section-master/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [SASS](https://sass-lang.com/) - CSS pre-processor
- [BEM metodology](https://getbem.com/) - Block Element Modifier metodology

### What I learned

I have some difficulties when I was putting the hover effect in the navigation icons, first of all, I don't have previous knowledge in the use of libraries of icons so I've researched the use of SVG and how to modify it with CSS when I was download the SVG I can not change the background color, so I research and in the importation method but that doesn't allow me to move them as I wanted, so I remember that SVG is like images and then I put the filter property to change the color in the hover, but at the end, it wasn't as I want

```css
&--active {
  width: 2.5em;
  height: 2.5em;
  display: inline;
  position: relative;
  text-align: end;
  bottom: 3px;
  /*this is the filter property that i made*/
  filter: brightness(0) saturate(100%) invert(100%) sepia(3%) saturate(109%) hue-rotate(
      310deg
    )
    brightness(114%) contrast(89%);
  &:hover {
    filter: brightness(0) saturate(100%) invert(85%) sepia(20%) saturate(4624%) hue-rotate(
        245deg
      )
      brightness(94%) contrast(94%);
    transition: ease 0.2s;
  }
}
```

### Continued development

I would like to have more knowledge in the use of the SVG's as well as star to do my portafolio

### Useful resources

- [piccalil](https://piccalil.li/blog/a-modern-css-reset/) - This page helped me to get a better reset of my code
- [CSS Color filter generetor](https://angel-rs.github.io/css-color-filter-generator/) - This page allow me to creat the filter for the hover
- [HSL to HEX](https://htmlcolors.com/hsl-to-hex) - this page help me change the hsl to hex for the filter creator

## Author

- Frontend Mentor - [@AlanLopRey](https://www.frontendmentor.io/profile/AlanLopRey)

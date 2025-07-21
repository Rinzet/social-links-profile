# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- See hover and focus states for all interactive elements on the page
- View the component at different screen sizes, with the container and content scaling proportionally

### Screenshot

![Screenshot of the solution](./screenshot.png)

### Links

- Solution URL: [https://github.com/Rinzet/social-links-profile](https://github.com/Rinzet/social-links-profile)
- Live Site URL: [https://rinzet.github.io/social-links-profile/](https://rinzet.github.io/social-links-profile/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive design with `clamp()` for scaling
- Mobile-first workflow

### What I learned

- How to use the CSS `clamp()` function for responsive scaling of containers and paddings.
- How to keep proportions of internal elements using relative units and clamp.
- How to fix an element (like `.attribution`) to the bottom of the viewport using `position: fixed`.
- Improved understanding of media queries for smooth scaling on larger screens.

```css
.container {
  width: 100%;
  max-width: clamp(280px, 80vw, 600px);
  padding: clamp(16px, 5vw, 40px);
  margin: 0 auto;
  box-sizing: border-box;
}
```

### Continued development

- Explore more advanced responsive techniques, such as CSS Grid and container queries.
- Experiment with more interactive states and accessibility improvements.
- Refine the scaling of typography and spacing for even better proportionality.

### Useful resources

- [MDN Web Docs - clamp()](https://developer.mozilla.org/en-US/docs/Web/CSS/clamp)
- [CSS-Tricks - Fluid Sizing with clamp()](https://css-tricks.com/using-clamp-for-fluid-typography/)
- [Frontend Mentor](https://www.frontendmentor.io/)

## Author

- Frontend Mentor - [@Rinzet](https://www.frontendmentor.io/profile/Rinzet)

## Acknowledgments

Thanks to the Frontend Mentor community for feedback

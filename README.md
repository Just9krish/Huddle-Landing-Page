# Frontend Mentor - Huddle landing page with alternating feature blocks solution

This is a solution to the [Huddle landing page with alternating feature blocks challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-alternating-feature-blocks-5ca5f5981e82137ec91a5100). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](https://github.com/Just9krish/Huddle-Landing-Page/blob/d08b325c61c994ab1c24fe511d0a3a98a6e9006b/design/desktop-preview.jpg)

### Links

- Solution URL: [Click here](https://www.frontendmentor.io/solutions/clipboardlandingpagebyjust9krish-lYazGTWJU)
- Live Site URL: [Click here](https://github.com/Just9krish/Huddle-Landing-Page)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- CSS animation

### What I learned

I learned how to use it to create a responsive layout with help of grid and flexbox, and also i used a simple animation for main button to move it like up and down. I am definitely gonna use it again in the future.

```html
<a class="btn btn-hero" href="#">get started for free</a>
```

```css
.btn-hero {
  margin: 2.5rem auto;
  padding: 1rem 0;
  width: 80%;
  transition: all 0.25s;
  animation: up-down 3s infinite;
}

@keyframes up-down {
    0% {
      transform: translateY(-10px);
    }
    50% {
      transform: translateY(0);
    }
    100% {
      transform: translateY(-10px);
    }

  }
```
### Continued development

I will continue to learn more about CSS Grid and how it can be used to create a more complex layout.

## Author

- Frontend Mentor - [@Just9krish](https://www.frontendmentor.io/profile/Just9krish)
- Instagram - [@Just9krish](https://www.instagram.com/just9krish/)
- Linkedin - [@rvamit2648](https://linkedin.com/in/amit-vishwakarma-bb54b222a)

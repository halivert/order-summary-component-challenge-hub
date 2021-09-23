# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend
Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj).
Frontend Mentor challenges help you improve your coding skills by building
realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![Mobile screenshot](./img/mobile.png)

### Links

- [Solution URL](https://github.com/halivert/order-summary-component-challenge-hub/)
- [Live Site URL](https://halivert.dev/order-summary-component-challenge-hub/)

## My process

### Built with

- Semantic HTML5 markup
- Sass
- Flexbox
- Mobile-first workflow
- Vite (I know this isn't needed 😆)

### What I learned

I'm proud of my background management

```scss
main {
  &::before {
    position: absolute;
    content: "";
    inset: 0;
    z-index: -1;
    background-image: url("/img/pattern-background-mobile.svg");
    background-size: 100%;
    background-repeat: no-repeat;

    @include desktop {
      background-image: url("/img/pattern-background-desktop.svg");
    }
  }
}
```

## Author

- Website - [Halí](https://halivert.dev)
- Frontend Mentor - [@halivert](https://www.frontendmentor.io/profile/halivert)
- Twitter - [@halivert](https://www.twitter.com/halivert)

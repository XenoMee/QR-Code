# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![desktopVersion](./images/QR_Code_Screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/XenoMee/QR-Code)
- Live Site URL: [Add live site URL here](https://xenomee.github.io/QR-Code/)

## My process

### Built with

- Semantic HTML5 markup
- BEM typing convention
- CSS reset
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

```html
<main>
    <section class="card">
      <img class="card__qr" src="./images/image-qr-code.png" alt="qr code">
      <div class="card__content">
        <h1 class="card__title">Improve your front-end skills by building projects</h1>
        <p class="card__description">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level.</p>
      </div>
    </section>
  </main>
```
```css
body{
    background-color: var(--clr-secondary-200);
    color: var(--clr-accent-400);
    font-family: var(--ff-base);
    font-weight: var(--fw-regular);
    font-size: .9rem;
    line-height: 1.5;
    min-height: 100svh;

    display: grid;
    place-content: center;
    padding: 0rem 1.5rem;
}

.card{
    --content-padding: 1.5rem;
    --content-spacing: 1rem;

    background-color: var(--clr-primary-100);
    padding: 1rem;
    border-radius: 1rem;
    max-width: 20.5rem;
}
```

## Author

- Website - [Adrian Trandafir](https://xenomee.github.io/Adrian-Trandafir/)
- Frontend Mentor - [@XenoMee](https://www.frontendmentor.io/profile/XenoMee)

## Acknowledgments

Shout out to Kevin Powell for helping me understand CSS variables and to reset my CSS but also for writing semantic HTML following BEM naming convention.
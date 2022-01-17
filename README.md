# Frontend Mentor - Equalizer landing page solution

This is a solution to the [Equalizer landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/equalizer-landing-page-7VJ4gp3DE). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Equalizer landing page solution](#frontend-mentor---equalizer-landing-page-solution)
  - [Table of contents](#table-of-contents)
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

![](./screenshot.jpg)

### Links

- Solution URL: [https://github.com/KrzysztofGrudzien/frontend-mentor-equalizer-landing-page](https://github.com/KrzysztofGrudzien/frontend-mentor-equalizer-landing-page)
- Live Site URL: [https://krzysztofgrudzien.github.io/frontend-mentor-equalizer-landing-page/](https://krzysztofgrudzien.github.io/frontend-mentor-equalizer-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Bem Methodology
- Mobile-first workflow

### What I learned
How to build realistic project based on Figma layout with design system using pure CSS and HTML.

```html
  <article class="article">
    <img src="./assets/illustration-app.png" alt="view of the app on the phone" class="article__img" />
    <div class="container-wrapper">
        <div class="container">
            <h2 class="article__title">Premium EQ</h2>
            <p class="article__description">
                Get expert-level control with a robust equalizer, volume mixer, and spatial audio. Take your
                listening experience to a whole new level and access all our incredible features!
            </p>
            <div class="amount">
                <span class="amount__price">$4</span>/<span class="amount__month">month</span>
            </div>
            <div class="article__links">
                <a href="#" class="article__link article__link--dark"
                    ><img src="./assets/icon-apple.svg" alt="" class="article__link-img" />iOS Download</a
                >
                <a href="#" class="article__link article__link article__link--light"
                    ><img src="./assets/icon-android.svg" alt="" class="article__link-img" />Android
                    Download</a
                >
            </div>
        </div>
    </div>
  <article>
```
```css
.social-media__link {
    margin-right: 2rem;
}

/* ------- PHONE ------- */

@media screen and (min-width: 375px) {
    .background-img {
        display: none;
    }
}

/* ------- TABLET ------- */

@media screen and (min-width: 768px) and (max-width: 1440px) {
    body {
        background: url('../assets/bg-main-tablet.png');
        background-position: right 30% top -35%;
        background-repeat: no-repeat;
        max-width: 1024px;
    }

    .background-img {
        display: block;
        right: -3.2rem;
        top: -2.5rem;
    }
```

### Continued development

## Author

- Website - [In progress]
- Frontend Mentor - [@KrzysztofGrudzien](https://www.frontendmentor.io/profile/KrzysztofGrudzien)
- E-mail - krzysztof.grudzien.fed@gmail.com

## Acknowledgments

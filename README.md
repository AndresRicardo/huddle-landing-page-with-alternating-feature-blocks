# Frontend Mentor - Chat app CSS illustration solution

This is a solution to the [Chat app CSS illustration challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
    -   [Useful resources](#useful-resources)
-   [Author](#author)
-   [Acknowledgments](#acknowledgments)

## Overview

This challenge was made using just HTML and CSS (SASS, Flexbox), i think develop it using Grid but it was not the best idea because the best tool to use in this case was flexbox, this project was thinking in mobile first.

### The challenge

Users should be able to:

-   View the optimal layout for the site depending on their device's screen size, mainly differentiating 2 sizes: mobile 375px and desktop since 800px

### Screenshot

![Mobile version screenshot](./screenshots/mobile-screenshot.png)

![Destop version screenshot](./screenshots/desktop-screenshot.png)

### Links

-   Solution URL: [Github repository](https://github.com/AndresRicardo/chat-app-css-illustration-master)
-   Live Site URL: [Github page](https://andresricardo.github.io/chat-app-css-illustration-master/)

## My process

Until now i am just learning web development, by now i just know html and css (flexbox and grid included), sass, not css frameworks, not css post-processores, not Javascript, not Js frameworks.

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   Css pre-processor sass
-   Mobile-first workflow

### What I learned

doing this challenge i learned basics of after and before elements, and z-index attribute.

```css
body {
    #after {
        z-index: -0;
        width: 420px;
        height: 700px;
        position: absolute;
        top: 0px;
        left: 0px;
        border-bottom-left-radius: 220px;
        border-bottom-right-radius: 220px;

        background: linear-gradient(
            to top,
            $color-Light-Violet,
            $color-Light_Magenta
        );
    }
}
#container {
    height: 100vh;
    background-image: none;
    flex-direction: row;
    justify-content: center;
    align-items: center;
}
#mobile {
    z-index: 1;
    width: 245px;
    margin: 0px 50px 0px auto;
}
#main {
    z-index: 1;
    width: 400px;
    margin: 0px auto 0px 50px;

    #page-title {
        text-align: left;
        margin-left: auto;
    }
    #page-description {
        text-align: left;
    }
}
```

### Continued development

Even if to me is more complex design mobile first, i preffer to continue develop of this way.
By now in short time, my next skills to develop are css grid, css frameworks (boostrap or tailwind), css pre-preocessor (sass), css post-processors (postcss), pure Javascript, typescript and css-framework (angular).

### Useful resources

-   [Developer mozilla](https://developer.mozilla.org/es/docs/Web/CSS/) - This helped me like general reference.

## Author

-   Website - [Richi](https://github.com/AndresRicardo)
-   Frontend Mentor - [@AndresRicardo](https://www.frontendmentor.io/profile/AndresRicardo)

## Acknowledgments

To my mom and dad jajajajja.

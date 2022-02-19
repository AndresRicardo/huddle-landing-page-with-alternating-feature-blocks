# Frontend Mentor - Huddle landing page with alternating feature blocks solution

This is a solution to the [Huddle landing page with alternating feature blocks challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-alternating-feature-blocks-5ca5f5981e82137ec91a5100). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

This challenge was made using just HTML and CSS (SASS, Flexbox and Grid).

### The challenge

Users should be able to:

-   View the optimal layout for the site depending on their device's screen size, mainly differentiating 2 sizes: mobile 375px and desktop since 800px

### Screenshot

![Mobile version screenshot](./screenshots/mobile-screenshot-1.png)

![Mobile version screenshot](./screenshots/mobile-screenshot-2.png)

![Destop version screenshot](./screenshots/desktop-screenshot.png)

### Links

-   Solution URL: [Github repository](https://github.com/AndresRicardo/huddle-landing-page-with-alternating-feature-blocks)
-   Live Site URL: [Github page](https://andresricardo.github.io/huddle-landing-page-with-alternating-feature-blocks/)

## My process

Until now i am just learning web development, by now i just know html and css (flexbox and grid included), sass, not css frameworks, not css post-processores, not Javascript, not Js frameworks.

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Css Flexbox
-   Css Grid
-   Css pre-processor sass
-   Mobile-first workflow

### What I learned

doing this challenge i learned basics of Css Grid.

```css
 #header {
        grid-template-columns: 4fr 6fr;
        grid-template-rows: auto 1fr;
        row-gap: 60px;
        column-gap: 50px;
        align-items: center;
        justify-content: space-between;
        padding: 45px 80px 30px 80px;

        #navbar {
            margin-bottom: 50px;
            grid-column: 1 / 3;

            margin: 0px;

            #navbar-logo {
                width: 200px;
                > img {
                    width: 100%;
                }
            }

            #navbar-button {
                width: 200px;
                height: 50px;
                font-size: 12px;
                font-weight: 700;
            }
        }
```

### Continued development

Even if to me is more complex design mobile first, i preffer to continue develop of this way.
By now in short time, my next skills to develop are css frameworks (boostrap or tailwind), css post-processors (postcss), pure Javascript, typescript and css-framework (angular).

### Useful resources

-   [Developer mozilla](https://developer.mozilla.org/es/docs/Web/CSS/) - This helped me like general reference.

## Author

-   Website - [Richi](https://github.com/AndresRicardo)
-   Frontend Mentor - [@AndresRicardo](https://www.frontendmentor.io/profile/AndresRicardo)

## Acknowledgments

To my mom and dad jajajajja.

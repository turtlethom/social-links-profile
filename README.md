# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
    - [Desktop](#desktop)
    - [Mobile](#mobile)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

#### Desktop
![](/assets/screenshots/sociallinksprofile-desktop.png)
#### Mobile
![](/assets/screenshots/sociallinksprofile-mobile.png)

### Links

- Live Site URL: [https://turtlethom.github.io/social-links-profile/](https://turtlethom.github.io/social-links-profile/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS utility classes

### What I learned

I found this challenge to be quite straightforward compared to other assignments I have completed, however I learned the importance of the `:focus` and `:focus-visible` selectors.
- Being able to provide clean navigation with keyboard input was eye-opening for me. I also discovered the `outline` CSS property.
- I had to do a bit of research in order to understand these selectors and properties, but I will be incorporating focusable elements into my projects from here on out.
- Ultimately, this project **assisted in how to improve accessibility for all visitors of a website**!

```css
.socials-menu li a:focus,
.socials-menu li a:focus-visible,
.socials-menu li a:hover {
    border-radius: var(--bord-radius);
    outline: none;
    background-color: hsl(var(--color-green));
    color: hsl(var(--color-grey-900));
}
```

### Useful resources

- [W3Schools](https://www.w3schools.com/css/css_outline.asp) - This introduced me to the documentation behind the CSS property `outline`. I found it interesting to see it encapsulates the `border` within the box model.
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus) - I used the documentation from Mozilla to understand what the :`focus`, `:focus-visible`, and `:focus-within` selectors were used for.

## Author

- Frontend Mentor - [@turtlethom](https://www.frontendmentor.io/profile/turtlethom)
- Twitter - [@wjamesthomas3](https://www.twitter.com/wjamesthomas3)

# Frontend Mentor - Intro section with dropdown navigation solution

This is a solution to the [Intro section with dropdown navigation challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/intro-section-with-dropdown-navigation-ryaPetHE5). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the relevant dropdown menus on desktop and mobile when interacting with the navigation links
- View the optimal layout for the content depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](.images/screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

To be able to launch the page in localhost, you have to run the command in the terminal 

``npm install``

and then use 

``npm run dev``

and use the 'localhost://1234' provided by parcel.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Sass and JavaScript

### What I learned

I learned how to manipulate a block via a click on an image.

```js
let arrow = document.querySelectorAll('.arrow');

for (let i = 0; i < arrow.length; i++) {

  arrow[i].addEventListener('click', (e) => {

    let arrowParent = e.target.parentElement.parentElement;
    arrowParent.classList.toggle('showMenu');

  });
}
```

### Useful resources

- [stackoverflow](https://stackoverflow.com/) - Stackoverflow helped me with the implementation and logic of an algorithm.

## Author

- Website - [David Baffray](https://david-baffray.github.io/)
- Frontend Mentor - [@David-BAFFRAY](https://www.frontendmentor.io/profile/David-BAFFRAY)
- Twitter - [@Np_Ng67](https://twitter.com/Np_Ng67)
- Linkedin - [David BAFFRAY](https://www.linkedin.com/in/david-baffray-189b6422b/)

# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshots

![Desktop Preview](/images/desktop.png)
![Mobile Preview](/images/mobile.png)

### Links

- Solution URL: [Github](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- SASS
- Flexbox
- Mobile-first workflow

### What I learned

- For this project I used SASS, where I took advantage of nested styling, and file seperation. More specifically, I wrote my CSS in seperated files for variables, global settings and main style sheet.

- What I found was that when I tried to use a seperate file for the media queries as well (/css/\_queries.scss), adding it to the top of my main stylesheet (/css/style.scss) made the media queries to go first in the final processed .css file. So the style applied there was not taken in account, as it came before everything and was overritten.

- At the end I just wrote my media queries at the bottom of the main stylesheet just like normal CSS styling.

## Author

- Github - [ChrisEski](https://github.com/ChrisEski)
- Frontend Mentor - [@ChrisEski](https://www.frontendmentor.io/profile/ChrisEski)
- Twitter - [@ChrisEski91](https://twitter.com/ChrisEski91)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

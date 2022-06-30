# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

In the 3 Column Preview Card challenge, I was tasked to mirror the design of an example preview card with various car types.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [https://github.com/pgc0004/3-Column-Preview-Card-Solution-using-CSS-Grid-and-Flexbox.git]
- Live Site URL: [https://3-column-preview-card-solution-using-css-grid-and-flexbox.netlify.app]

## My process

1. Began with HTML layout of the main background and the card's container. I used CSS Flexbox to center the container. Then created three seperate div elements with the classes main-sedans, main-suvs, and main-luxury. I used CSS grid to seperate the container into three equal parts for each div class. (A Mobile First Workflow).

2. Continued with appropriatly styling the three classes and moving towards the Desktop CSS layout.

3. Lastly, the text and background color variables were added and implimented in the Global section.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

1. Learned to used CSS Grid to seperate the container into three equal parts.

2. Better understood the Mobile First workflow.

3. Additionally, learn the benefits of using padding instead of margins in certain situations.

Proud of using CSS Grid

```css
.container {
  height: auto;
  width: 20rem;
  margin: 5rem 0;

  display: grid;
  grid-template-rows: 1fr 1fr 1fr;
}
```

### Continued development

I will contnue to learn the basics of CSS Grid to better impliment it into my future challenges.

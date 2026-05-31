# Frontend Mentor - Chat app CSS illustration solution

This is a solution to the [Chat app CSS illustration coding challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5vN68I7d). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the component depending on their device's screen size.
- See a highly semantic and accessible HTML structure combined with professional CSS architecture.

### Screenshot

[Insert your screenshot here, e.g., ./design/desktop-preview.jpg]

### Links

- Solution URL: [Add your GitHub repository URL here](https://github.com/your-username/your-repo-name)
- Live Site URL: [Add your live site URL here](https://your-username.github.io/your-repo-name)

## My process

### Built with

- Semantic HTML5 markup (utilizing `<main>`, `<section>`, and `<aside>`)
- Advanced CSS architecture using **Sass (SCSS)**
- **BEM (Block Element Modifier)** naming convention for maintainable classes
- CSS Flexbox & CSS Grid
- Mobile-first workflow
- **Fluid Typography** using the CSS `clamp()` function for automated responsiveness

### What I learned

During this project, I strengthened my understanding of writing scalable CSS using modern Sass techniques. Here are some key highlights from my implementation:

1. **Sass Architecture & Compilation Fixes:**
   I learned how to properly set up a decoupled Sass structure using `@use` instead of `@import`. I also learned how to handle complex operations like pixel-to-rem conversions smoothly using native Sass math functions (`math.div`).

2. **Advanced BEM & Semantic Markup:**
   Instead of using arbitrary class names, I applied strict BEM guidelines. This allowed me to modularize components like incoming and outgoing chat bubbles perfectly:

```html
<div class="chat-msg chat-msg--incoming">
  <p class="chat-msg__text">That sounds great. I’d be happy with that.</p>
</div>
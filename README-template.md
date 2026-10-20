# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

- Build out the project to the designs provided

### Links

- Solution URL: [GitHub repository](https://github.com/valerii-tarasenko/profile-card-component)
- Live Site URL: [Live site](https://valerii-tarasenko.github.io/profile-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

In this project, I gained a better understanding of CSS element positioning. Specifically, I learned how `position: absolute` works in relation to a parent with `position: relative`, how to position large decorative backgrounds outside the viewport using negative margins, and how to clip them using `overflow: hidden`. I also learned how to center an avatar that extends beyond the edge of a card header, without relying on pixel-based offsets:

```css
.card__container {
  position: relative;
}

.image__victor {
  position: absolute;
  left: 50%;
  bottom: 0;
  transform: translate(-50%, 50%);
}
```

### Continued development

Moving forward, I want to continue improving my knowledge of positioning (`absolute`, `relative`, `fixed`, `z-index`) and responsive layout—specifically Flexbox, media queries, and working with various screen sizes.

### AI Collaboration

I used Claude to better understand how to position elements correctly. It helped me figure out why an image was overlapping the text, how to place background circles in the corners, and how to remove unwanted scrolling on the mobile version. The most effective approach was sending screenshots and code; Claude would explain the root cause of the issue rather than just providing a ready-made solution. Even so, the specific spacing values ​​still required manual fine-tuning in DevTools to match the design.

## Author

- Frontend Mentor - [@valerii-tarasenko](https://www.frontendmentor.io/profile/valerii-tarasenko)
- GitHub - [valerii-tarasenko](https://github.com/valerii-tarasenko)

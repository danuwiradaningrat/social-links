# Frontend Mentor - Social links profile solution

This is my solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). This challenge helped me improve my understanding of layout structuring, styling interactive elements, and making responsive designs.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the social profile card with links
- See hover and focus states for all interactive elements
- Experience a responsive layout across screen sizes

### Screenshot

![](my-preview.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/danuwiradaningrat/social-links)
- Live Site URL: [Live Demo](https://danuwiradaningrat.github.io/social-links/)

## My process

### Built with

- Semantic HTML5
- Vanilla CSS (no framework)
- Flexbox
- Mobile-first responsive design
- Custom button hover & focus state styling

### What I learned

While building this project, I reinforced a few important fundamentals:

- How to center elements using `flexbox` both horizontally and vertically.
- The importance of `min-height: 100vh` and spacing (e.g., padding) to create a centered, scroll-safe layout.
- How to style and animate hover/focus states to match accessibility standards.
- Making designs responsive using `max-width`, percentage-based sizing, and `media queries`.

Here’s a sample of the responsive button styles I used:

```css
.card-button button {
  background-color: #333;
  color: white;
  font-weight: 600;
  padding: 14px;
  border: none;
  border-radius: 8px;
  width: 100%;
  cursor: pointer;
  transition: background 0.3s, color 0.3s;
}

# Frontend Mentor | Profile Card Component Solution

This is my solution to the [Profile Card Component Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). This challenge helped me improve my CSS layout skills, especially using grid and custom properties, while ensuring responsive and aesthetically pleasing results.
![image](https://github.com/user-attachments/assets/a1d03472-870e-4f56-aa13-7fcb80b2a477)


## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The Challenge

- Build out the profile card component based on the provided design and ensure that it looks good across various screen sizes.

### Screenshot

![Project Screenshot](./screenshot.jpg)

_This screenshot shows the completed project with all required elements styled to match the design._

### Links

- **Solution URL**: [GitHub Repository](https://github.com/Pichikachandu/Profile-Card-Component-Solution)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties (variables)
- CSS Grid for layout
- Mobile-first workflow
- [Google Fonts - Kumbh Sans](https://fonts.google.com/specimen/Kumbh+Sans)

### What I Learned

This project helped reinforce my understanding of responsive design and layout. Here are a few examples:

- **CSS Grid for component layout**:
  ```css
  .stats {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 1rem;
      justify-content: center;
      align-items: center;
  }
  ```

- **Using CSS custom properties** for better theme management:
  ```css
  :root {
      --Dark-cyan: hsl(185, 75%, 39%);
      --Very-dark-desaturated-blue: hsl(229, 23%, 23%);
      --Dark-gray: hsl(0, 0%, 59%);
  }
  ```

### Continued Development

I plan to keep exploring responsive design and CSS Grid layouts in future projects, as well as integrating JavaScript for more interactive elements in similar projects.

### Useful Resources

- [CSS Tricks - A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - Helped me understand grid layout basics and advanced concepts.
- [MDN Web Docs on CSS Custom Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) - Great reference for CSS variables.

## Author

- Frontend Mentor - [@Pichikachandu](https://www.frontendmentor.io/profile/Pichikachandu)
- GitHub - [@Pichikachandu](https://github.com/Pichikachandu)

## Acknowledgments

Thanks to [Frontend Mentor](https://www.frontendmentor.io/) for providing these practical challenges that help us grow as developers.

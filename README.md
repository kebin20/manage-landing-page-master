# Frontend Mentor - Manage landing page solution

This is a solution to the [Manage landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/manage-landing-page-SLXqC6P5). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- See all testimonials in a horizontal slider
- Receive an error message when the newsletter sign up `form` is submitted if:
  - The `input` field is empty
  - The email address is not formatted correctly


### Links

- Solution URL: [GIthub Repo](https://github.com/kebin20/manage-landing-page-master)
- Live Site URL: [Manage Landing Page](https://kebin20.github.io/manage-landing-page-master/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Tailwind CSS](https://tailwindcss.com/) - CSS Library

### What I learned

I learnt how to setup custom themes and configuration in tailwind CSS from the following code:


```
/** @type {import('tailwindcss').Config} */
module.exports = {
  tailwindConfig: "./styles/tailwind.config.js",
  content: ["./*.html"],
  theme: {
    screens: {
      sm: "480px",
      md: "768px",
      lg: "976px",
      xl: "1440px",
    },
    extend: {
      colors: {
        brightRed: "hsl(12, 88%, 59%)",
        brightRedLight: "hsl(12, 88%, 69%)",
        brightRedSupLight: "hsl(12, 88%, 95%)",
        darkBlue: "hsl(228, 39%, 23%)",
        darkGrayishBlue: "hsl(227, 12%, 61%)",
        veryDarkBlue: "hsl(233, 12%, 13%)",
        veryPaleRed: "hsl(13, 100%, 96%)",
        veryLightGray: "hsl(0, 0%, 98%)",
      },
    },
  },
  plugins: [],
};
```

### Continued development

I will use this project to further aid me to familiarize myself with the Tailwind classes and create more projects efficiently

### Useful resources

- [Traversy Media](https://www.example.com) - This YouTube Tailwind CSS tutorial video by Brad Traversy helped me a lot in setting up Tailwind


## Author

- Frontend Mentor - [@kebin20](https://www.frontendmentor.io/profile/kebin20)


## Acknowledgments

This was project was fully aided by the video produced by Traversy Media.
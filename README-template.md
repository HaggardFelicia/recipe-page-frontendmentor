# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Recipe page solution](#frontend-mentor---recipe-page-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![screenshot of desktop media query](./src/assets/images/localhost_5173_(desktop).png)
![screenshot of mobile media query](./src/assets/images/localhost_5173_(mobile).png)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/responsive-recipe-page-7zktdr6rcH)
- Live Site URL: [Add live site URL here](https://recipe-page-frontendmentor.haggardwebdev.space/)

## My process

### Built with

- Semantic HTML5 markup
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Vite](https://vite.dev/) - React framework
- [TailwindCSS v4.1](https://tailwindcss.com/) - For css styling

### What I learned

I learned that in Tailwind CSS the ul disc won't show unless you add padding to the left of the disc.

See code snippet below:

```css
ul{
  @apply list-disc pl-5;
}
```

### Continued development

- I want to continue focusing on mobile-first development. I have been stuck in the set of desktop-first development.
- I also want to focus on accessibility.

### Useful resources

- [TailwindCSS Docs](https://tailwindcss.com/docs/installation/using-vite) - This always helps when working with tailwind.
- [Stack Overflow](https://stackoverflow.com/) - This is an amazing place to get help with all thing dev related!

## Author

- Website - [Felicia Haggard](https://www.haggardwebdev.space/)
- Frontend Mentor - [@HaggardFelicia](https://www.frontendmentor.io/profile/HaggardFelicia)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

- [Github Thread](https://github.com/tailwindlabs/tailwindcss/discussions/11276) - This is where I recieved help with the tailwind css ul disc issue.

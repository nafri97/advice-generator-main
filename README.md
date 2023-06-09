# Frontend Mentor - Advice generator app solution

This is a solution to the [Advice generator app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/advice-generator-app-QdUG-13db). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Generate a new piece of advice by clicking the dice icon

### Screenshot

![Desktop](./screenshot_Desktop.jpg)
![Mobile](./screenshot_Mobile.jpg)

### Links

- Solution URL: [Github Repository](https://Github.com/advice-generator-main)
- Live Site URL: [Github Page](https://nafri97.github.io/advice-generator-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- Typescript


### What I learned

So many I learned. Here,s some sniplets:

```Ts
  const min: number = 1;
  const max: number = 244;
  let randomNumber: number = Math.floor(Math.random() * (max - min + 1) + min);
```
```Ts
let idS = id.toString().padStart(3, '0');
```
```Ts
interface Slip {
  id: number;
  advice: string;
};
```


### Continued development

I want to learn more using React Js, this project I just trying Typescript. but it seems I have to strengthen my fundamental of Javascript. before I transform to Typescript.

### Useful resources

- [React Reference](https://react.dev/reference/react) - This helped me to understand React syntax.
- [W3schools-Typescript](https://www.w3schools.com/typescript/) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Author

- Github - [nafri97](https://www.github.com/nafri97)
- Frontend Mentor - [@nafri97](https://www.frontendmentor.io/profile/nafri97)
- Twitter - [@irfanrizkis](https://www.twitter.com/irfanrizkis)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

#   a d v i c e - g e n e r a t o r 
 
 #   a d v i c e - g e n e r a t o r 
 
 #   a d v i c e - g e n e r a t o r 
 
 
# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://github.com/omerome83/Stats-Preview-Card-Component](https://github.com/omerome83/Stats-Preview-Card-Component)
- Live Site URL: [https://omerome83.github.io/Stats-Preview-Card-Component/](https://omerome83.github.io/Stats-Preview-Card-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This was a challenging one, but not without lessons learned. Figuring out the layout for the stats as well as getting the image on the right to display properly were my biggest roadblocks. But what I learned is when you're in deep in a project with little hope of figuring things out, it's okay to start over fresh and create the project from beginning. I did that twice when I got stuck and each time, something was "fixed" that I was having issues with or a simple Google search helped.

To get the page to become responsive correctly I used this media query:

```css
@media (max-width: 1000px) {
  .main-container {
    flex-direction: column-reverse;
  }
}
```

### Continued development

Furthering my experience with Flexbox and learning CSSGrid to design different styles of layouts.

### Useful resources

- [W3Schools](https://www.w3schools.com/cssref/css3_pr_flex-direction.asp) - Understanding the syntax of Flexbox commands as well as once again being a great resource.
- [Slack](https://www.slack.com) - The Frontend Mentor community was also a big help in pointing me in the right direction. As well as showing me another way on how to layout the stats of the page using ul and li elements.

## Author

- Website - [Romel Williams](https://github.com/omerome83)
- Frontend Mentor - [@omerome83](https://www.frontendmentor.io/profile/omerome83)

## Acknowledgments

Special thanks to Grace from the Frontend Mentor community for your assistance. I definitely appreciate your guidance and advice on this project.

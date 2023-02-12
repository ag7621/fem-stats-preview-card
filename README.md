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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Desktop preview image for Profile card component challenge](/images/desktop-preview.png "Desktop preview")
![Mobile preview image for Profile card component challenge](/images/mobile-preview.png "Mobile preview")

### Links

- Solution URL: [Solution](https://github.com/ag7621/fem-stats-preview-card)
- Live Site URL: [Live site](https://ag7621.github.io/fem-stats-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

In this challenge I was tasked with creating a responsive site for a mobile and desktop view. I started with a mobile first approach initially setting the content using padding, but later found more trouble keeping things responsive as I transitioned into the desktop view. After several iterations and troubleshooting I reworked my code to use grid and adjusted the content with a mix of line-height and gap. This gave me much better results and didn't require so much micromanaging the positioning of the card content.

Previous challenges I've completed have also involved creating responsive websites, but a less complex as the body content and image change positions as it grows. This isn't difficult to do using `grid`, but what I found most troublesome was trying to let the card grow naturally and not become disproportioned in the process. I attempted to use common breakpoints to alleviate this such as 768px, but failed to create a transition that I was happy with since the body content would create a space taller than the image height. In the end I created some custom breakpoints that hopefully suit the transition from mobile to desktop much better, but it's not a solution that I'm confident is a correct one.

### Continued development

I very much enjoyed the step up in difficulty with this challenge, but have much more to learn in creating responsive websites particularly with the transitions as it grows. I'm not sure if my approach to building responsive sites is correct, but it is something I plan to remedy with code reviews and studying. In hindsight I should have tried to do more with the `justify-content` and `align-items` perhaps for positioning text, but felt I had more control in my approach trying to create as close to a pixel perfect solution as I could. Another area for me to focus on is continued development using BEM properly which I feel slightly more confident as I complete each new challenge.

I tried something new on the suggestion from a previous challenge to separate my css files for readability. I split my `style.css` into 3 files, adding a `reset.css` and `variables.css`into a styles folder. I've read that it's not the best approach having multiple files the browser has to call on, but thought I would give it a try. If i'm not mistaken something like SASS might be able to handle this better and is something I will look into as well.

### Useful resources

- [BEM cheat sheet](https://9elements.com/bem-cheat-sheet/) - This helped me understand the basics of how BEM looks and how to name classes.
- [A complete guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - This was a useful reference in remembering grid properties like grid-area and such.
- [Kevin Powell Youtube](https://www.youtube.com/@KevinPowell) - Amazing channel by veteran web developer Kevin Powell which helped me to understand CSS much better.
- [Josh W Comeau CSS reset](https://www.joshwcomeau.com/css/custom-css-reset/) - A CSS reset referred to in a video by Kevin Powell.

## Author

- Frontend Mentor - [@ag7621](https://www.frontendmentor.io/profile/ag7621)

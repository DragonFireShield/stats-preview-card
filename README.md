# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](screenshot.png)

### Links

- Solution URL: [GitHub Spaces](https://your-solution-url.com](https://dragonfireshield.github.io/stats-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

It's quite easy to add a filter to your backgrounds plus you set a fallback color at the same time.

```
  .image {
      padding: 10em;
      border-radius: .5em .5em 0 0;
      background: var(--soft-violet) url(./images/image-header-mobile.jpg);
      background-size: cover;
      background-blend-mode: multiply;
  }
```

### Continued development

Centering content and positioning footers feels easier to me when using position absolute. Using flex however, this time resulted in a nice centered card with the footer just below screen. (Not sure if this looks the same on all devices). I need to figure out what the best practices are for containing the content on your page. For example, I'm sure some if not all of my layouts would break if I were to add more content to them.

### Useful resources

- [Background Images with HTML & CSS](https://www.youtube.com/watch?v=zHZRFwWQt2w) - Decided to use this technique to make it easier

## Author

- Frontend Mentor - [@dragonfireshield](https://www.frontendmentor.io/profile/dragonfireshield)
- Twitter - [@shieldfordragon](https://www.twitter.com/shieldfordragon)

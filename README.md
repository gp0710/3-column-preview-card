# Responsive 3-column Preview Card Component 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [solution here](https://github.com/gp0710/3-column-preview-card)
- Live Site URL: [live site here](https://gp0710.github.io/3-column-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

At a glance, this card looks relatively simple and easy to create. Should take 30min to an hour, no? This card took me 3-4 hours to create. It was confusing with all the div parent and child components in my HTML because when I tried to use the "padding" declaration, my div would increase in size and stray out of view of the viewport. 

The problem was the width declaration. It was better to omit the width declaration:  

```css
.sedans {
  width: 100%;
}
```

Another issue I had was when building out the responsive features of the card. 

For example:
```css {
  @media and (min-width: 375px); {
    
  }
}
```

Can you see the problem? I put the semi-colon at the end of the selector! -facepalm- These little errors can really make or break your code. 

### Conclusion 

All in all, I had a fun time creating this responsive card because of the mistakes I've made. In the future, I would like to use SASS to reduce repetitive CSS code. 

## Author

- Website - [gp0710](https://github.com/gp0710)

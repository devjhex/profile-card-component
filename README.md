# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./screenshot.jpg)

![Design preview for the Profile card component coding challenge](./design/desktop-preview.jpg)

### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/responsive-profile-preview-card-component--nYFBNBKsy)
- Live Site URL: [Live Site](https://devjhex-profile-card-component-rust.vercel.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned
I learned how to use the background size property with two values, that is to say for two different images which i had no clue about in the past. It helped to position two different images in different areas of the component for example:

```css
.body{
  background-image:url("/images/bg-pattern-bottom.svg"), url("/images/bg-pattern-top.svg");
 
  /* I didn't know this was possible */

  /*---*/
   background-size:contain, contain;
   background-position:top 50px right 100px, bottom 50px left 100px;
   /*---*/
}
```


### Useful resources

- [MDN](https://developer.mozilla.org/) - This site is the one which helped me to get to know about the additional values that could be added to the background properties and it really helps me to know many other things concerning CSS hence I really recommend this.

## Author
- Frontend Mentor - [@Dev-Jhex](https://www.frontendmentor.io/profile/Dev-Jhex)
- Twitter - [@devJhex](https://www.twitter.com/devJhex)

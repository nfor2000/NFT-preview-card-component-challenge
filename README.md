# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot




### Links
- Live Site URL: [](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Media queries

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned


```css
.nft{
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
    width: 20%;
    height: 480px;
    padding: 0.7rem;
    border-radius: 20px;
    background: hsl(216, 50%, 16%);
    -webkit-box-shadow: 0 0 40px #000;
    -moz-box-shadow: 0 0 40px #000;
    box-shadow:0 40px 40px rgba(0,0,0,0.4);
}
.image:hover.image::after{
    content:url(images/icon-view.svg);
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
    width: 100%;
    background:hsl(178, 100%, 50%,50%) ;
    z-index:11 ;
    position: relative;
    top:-102%;
    border-radius: 10px;
}
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

## Author
- Frontend Mentor - [@nfor2000](https://www.frontendmentor.io/profile/nfor2000)
- Twitter - [@PreslyNfor](https://www.twitter.com/yourusername)


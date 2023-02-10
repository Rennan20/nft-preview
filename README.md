# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [The challenge](#the-challenge)
- [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: (https://www.frontendmentor.io/solutions/nft-preview-card-using-transition-efects-5lOMCzZHbZ)
- Live Site URL: (https://rennan20.github.io/nft-preview/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

```css
.container .main-image div {
  border-radius: 1rem;
  position: absolute;
  top: 0;
  background-color: hsl(178, 100%, 50%, 60%);
  width: 100%;
  height: calc(100% - 4px);
  z-index: 999;
  opacity: 0;
  transition: opacity 0.3s ease-in-out;
}

.container .main-image div:hover {
  opacity: 1;
  cursor: pointer;
}

.container .main-image div img {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}
```

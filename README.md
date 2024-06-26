# Frontend Mentor - Blog preview card

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

- See hover and focus states for all interactive elements on the page

### Screenshot

_1. Desktop display_

![](./assets/images/Blog_preview_card_desktop_view.png)

_2. Desktop hover stage display_

![](./assets/images/Blog_preview_card_desktop_hover.png)
_It doesn't show the mouse pointer :<_

_3. Mobile display_

![](./assets/images/Blog_preview_card_mobile_view.png)

### Links

<!-- - Solution URL: [Add solution URL here](https://your-solution-url.com) -->
- Live Site URL: [Blog preview card page](https://auri222.github.io/blog-preview-card-html-css/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- How to build an appropriate HTML structure 

```html
<div class="card">
  <div class="card-img">
    <img src="./assets/images/illustration-article.svg" alt="Card image" />
  </div>

  <div class="card-header">
    <span class="badge">Learning</span>
    <p class="date">Published 21 Dec 2023</p>
  </div>

  <div class="card-body">
    <h4 class="card-title">HTML & CSS foundations</h4>
    <p class="card-content">
      These languages are the backbone of every website, defining structure,
      content, and presentation.
    </p>
  </div>

  <div class="card-footer">
    <img src="./assets/images/image-avatar.webp" alt="Greg Hooper" />
    <span class="username">Greg Hooper</span>
  </div>
</div>
```

- How to use a static font in CSS

```css
@font-face {
  font-family: 'Figtree';
  font-weight: 500 800;
  src: url('./assets/fonts/Figtree-VariableFont_wght.ttf') format("truetype-variations");
}
```
> Here I faced an error when I published the page on Github, which couldn't load the static font. Mostly when I was setting @font-face. The  CSS code above is correct.

### Continued development

- To build this card by using CSS grid (but right now flexbox is my option).

### Useful resources

- [Self-hosting fonts explained (including Google fonts) // @font-face tutorial by Kevin Powell's Youtube channel](https://www.youtube.com/watch?v=zK-yy6C2Nck) - This helped me understand how to use self-hosting fonts for a better performance.
- [MDN Web Docs](https://developer.mozilla.org/en-US/) - This taught me how to use border and box-shadow properties in CSS. 

## Author

- Frontend Mentor - [@auri222](https://www.frontendmentor.io/profile/auri222)


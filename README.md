# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). 

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

![](./assets/images/Screenshot%20Blog-preview-card.png)


### Links

- Solution URL: [https://github.com/j4n1na/Blog-Preview-Card.git]
- Live Site URL: [https://j4n1na.github.io/Blog-Preview-Card/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Avatar image sizing & object-fit
I discovered that to avoid stretching, images need a square container (equal width and height)

Hover & focus states for interactive elements
I learned how to style hover states on elements such as the post title (e.g., changing its color on :hover) to give clear visual feedback. 

```css
h1{
    font-weight: 800;
    font-size: 25px;
    cursor: pointer;
}

h1:hover{
color: hsl(47, 88%, 63%);

}
```


### Useful resources

- [Resource 1](https://www.w3schools.com/css/css3_shadows_box.asp) - Box shadow
- [Resource 2](https://www.w3schools.com/cssref/pr_border.php) - Border property
- [Resource 3](https://www.w3schools.com/css/css_text_spacing.asp) - Line height and text spacing in general
- [Resource 4](https://www.youtube.com/watch?v=XvjWWwx2O7w) - How To Create Hover Over Cursor Effects On A Webpage Using 1 Line Of CSSLine height and text spacing in general
- [Resource 5](https://www.w3schools.com/CSSref/sel_hover.php) - CSS :hover Pseudo-class



## Author

- Frontend Mentor - [@j4n1na](https://www.frontendmentor.io/profile/j4n1na)

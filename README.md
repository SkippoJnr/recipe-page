# Frontend Mentor - recipe-page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot
### Desktop view
![desktop-view](https://github.com/SkippoJnr/recipe-page/blob/408161655beaf2b5b5a695cd5692f4e3780b17e9/screenshots/desktop-view.jpeg)





## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow


### What I learned

Making websites responsive on various screen sizes using media queries, and styling ordered and unordered list tags. 


```css
/* styling of ul */
.recipe-section .preparation-time ul li {
  padding: 10px 0;
  margin: 0 20px; /* Adjust spacing between items */
  position: relative;
}

.recipe-section .preparation-time ul {
  list-style: none; /* Remove default list style */
}

.recipe-section .preparation-time li::before {
  content: "•"; /* Use a bullet character */
  color: #986a7e; /* Change to your desired color */
  font-size: 25px; /* Change to your desired size */
  position: absolute; /* Position absolute for centering */
  left: -20px;
  top: 5px;
}
```




## Author

- Frontend Mentor - [@SkippoJnr](https://www.frontendmentor.io/profile/Skippojnr)




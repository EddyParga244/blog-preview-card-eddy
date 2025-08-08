# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

### Links

- Github repository: (https://github.com/EddyParga244/blog-preview-card-eddy)
- Github deployment: (https://eddyparga244.github.io/blog-preview-card-eddy/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to make a Flexbox inside another Flexbox, it was the part that gave me the most trouble for me, since
I had to make the profile picture being aligned with it's user.

```html
<div class="media">
  <img id="profile" src="./assets/images/image-avatar.webp" alt="profile picture" />
  <h5 id="user">Greg Hooper</h5>
</div>
```
```css
.media {
    display: flex;
    align-items: flex-start;
}

.media #user {
    flex: 1;
    padding: 1px;
    margin-left: 10px;
    margin-top: 5px;
    font-weight: bolder;
}
```

### Continued development

I plan to continue using flexbox and grid in upcoming proyects 

### Useful resources
- [MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout/Typical_use_cases_of_flexbox#media_objects) - This page helped me to work around the media object of the user

## Author

Eduardo Parga Vela
Start date: 07/08/2025
End date: 08/08/2025

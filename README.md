# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview
Solution of Blog preview card by using HTML and CSS 
### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [http://127.0.0.1:5500/index.html](https://your-solution-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Pseudo-Class
**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I learnt alot from this challenge but specially at the footer part i learnt that how align the avatar image exact in horizontal with the avatar name.

below are the code snippets which i want to highlight:

```html
 <footer class="avatar">
        <img src="assets/images/image-avatar.webp" alt="Greg Hooper-img">
        <p class="avatar-name">Greg Hooper</p>
      </footer>
```
```css
footer{
    padding: 20px 0 5px;
    text-align: left;
}
footer img{
    width: 35px;
}
footer .avatar-name{
    display: inline-block;
    position: relative;
    bottom: 12px;
    font-weight: 800;
    padding-left: 8px;
    color: hsl(0, 0%, 7%);
}
h1:hover{
    color:hsl(47, 88%, 63%);
}
```

### Continued development

I want to focus on media quaries specially!


## Author

- Frontend Mentor - [@basitali07](https://www.frontendmentor.io/profile/yourusername)


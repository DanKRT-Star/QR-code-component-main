
# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help me improve my coding skills by building realistic projects.

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

### Screenshot

![Design preview for the QR code component coding challenge](./images/Screenshot%202025-07-07%20105403.jpg)

### Links

- Solution URL: https://github.com/DanKRT-Star/QR-code-component-main
- Live Site URL: [QR code page](https://qr-code-component-main-one-liard.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

While working on this project, I practiced using Flexbox to center content both vertically and horizontally, used CSS variables for color management, and integrated Google Fonts into the project. I also paid attention to using border-radius, aspect-ratio for images, and organizing HTML/CSS structure clearly and maintainable.

Here is a code snippet I am proud of:

```html
<div class="QR-card">
  <img src="./images/image-qr-code.png" alt="QR code for frontend mentor">
  <h3>Improve your front-end skills by building projects</h3>
  <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
</div>
```

```css
.QR-card {
  background-color: var(--white);
  padding: 10px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  border-radius: 20px;
  text-align: center;
  width: 250px;
  font-size: 15px;
  margin-bottom: 10px;
}
.QR-card img {
  object-fit: cover;
  width: 100%;
  aspect-ratio: 1/1;
  border-radius: 10px;
}
```


### Continued development

I want to continue practicing responsive design, experiment more with CSS Grid and advanced CSS effects to make the interface look better on various devices.


### Useful resources

- [MDN Web Docs - Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox) - Helped me understand Flexbox better.
- [Google Fonts](https://fonts.google.com/) - Used to embed the Outfit font into the project.


## Author

- Frontend Mentor - [@DanKRT-Star]https://www.frontendmentor.io/profile/DanKRT-Star
- Facebook - [Lê Mạnh Đan](https://www.facebook.com/le.manh.an.887330)
- Gmail - [Lê Mạnh Đan] (tonyle1207@gmail.com)
- Github - [Lê Mạnh Đan] (https://github.com/DanKRT-Star)

## Acknowledgments

This project helped me practice basic HTML/CSS and organize project files neatly.

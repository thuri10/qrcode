# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What Learned](#what-learned)


## Overview

### Screenshot
Below is a screenshot of the complete challenge solution.

![Image](./screenshot.png)


### Links
- Solution URL: [Solution](https://github.com/thuri10/qrcode)
- Live Site URL: [Demo](https://thuri10.github.io/qrcode)

## My process

### Built with

- Semantic HTML5 markup
- CSS 
- Flexbox
- Mobile-first workflow

### What Learned
- When centering a Card in an empty page, you need to setup height of the parent container, i.e 100vh. Example of the above trick is highlighted in container class

```css
.container {
    max-width: 1440px;
    width: 90%;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
}
```
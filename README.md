# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview]
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

desktop_look.PNG
mobile_look.PNG

### Links

- Live Site URL: [https://qr-scanner-1st-frontend-mentor-task.vercel.app/]

## My process

- I start with HTML first and after done with html, i move from HTML to CSS. 

### Built with

- HTML
- CSS

### What I learned

From this task i learn about basics of HTML and CSS properties like div,img,p,font properties,text properties,background properties,position and spacing

To see how you can add code snippets, see below:

```html
<div class="qr_main">
    <div class="qr_img">
      <img src="images/image-qr-code.png" alt="" class="img">
    </div>
    <div class="content">
      <p class="bFont">Improve your front-end skills by building projects</p>
      <p class="nFont">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>
  </div>
```
```css
*{
        background-color: hsl(212, 45%, 89%);
        border-radius: 5%;
        text-align: center; 
        font-family: 'Outfit';
      }
    .qr_main{
      position: relative;
      margin: auto;
      top: 100px;
      width: 300px;
      background-color: hsl(0, 0%, 100%);
      padding: 10px;
    }
    .qr_img{
      background-color: hsl(0, 0%, 100%);
    }
    .img{
      width: 100%;
    }
    .content{
      background-color: hsl(0, 0%, 100%);
      
    }
    .bFont{
      font-size: 20px;
      background-color: hsl(0, 0%, 100%);
      
      font-weight: 700;
      padding: 0px 20px;
    }
    .nFont{
      font-size: 15px;
      background-color: hsl(0, 0%, 100%);
      padding: 0px 20px;
      color: hsl(220, 15%, 55%);
    }
```

## Author

- Frontend Mentor - [@ParthMovaliya(https://www.frontendmentor.io/profile/ParthMovaliya)


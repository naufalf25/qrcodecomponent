# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![images/my-screenshot.png]

### Links

- Solution URL: [https://github.com/naufalf25/qrcodecomponent]
- Live Site URL: [https://naufalf25.github.io/qrcodecomponent/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>QR Code Component Challenge Hub</title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="style.css" type="text/css">
    </head>
    <body>
        <div class="container">
            <div class="qrcode">
                <img src="images/image-qr-code.png" alt="qrcode">
            </div>
            <div class="text-head">
                <p>Improve your front-end skills by building projects</p>
            </div>
            <div class="text-body">
                <p>Scan the QR code to visit Frontend Mentor and take your coding
                skills to the next level</p>
            </div>
        </div>
    </body>
</html>
```
```css
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    background-color: #D5E1EF;
}

.container {
    margin: 0;
    position: absolute;
    left: 50%;
    right: 50%;
    top: 50%;
    bottom: 50%;
    margin-right: -50%;
    transform: translate(-50%, -50%);
    width: 304px;
    height: 472px;
    background-color: #FFF;
    border-radius: 20px;
    box-shadow: 0px 8px 24px rgba(149, 157, 165, 0.2);
}

.qrcode img {
    width: 100%;
    padding: 15px;
    border-radius: 25px;
}

@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap');

.text-head, .text-body {
    padding: 5px 25px;
    font-family: 'Outfit' , sans-serif;
    text-align: center;
}

.text-head p {
    font-weight: 700;
    font-size: 22px;
}

.text-body p {
    font-weight: 300;
    font-size: 15px;
}
```

### Useful resources

- [https://getcssscan.com] - This helped me to get solutions for my CSS.
- [https://fonts.google.com] - This is the best place to get another font for my website.

## Author

- Frontend Mentor - [https://www.frontendmentor.io/profile/naufalf25]
- Instagram - [https://www.instagram.com/naufal_railfans25/]
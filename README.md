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
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![QR Code Solution Screenshot](/images/QR%20code%20component%20Screenshot.png)

### Links

- Solution URL: [Solution URL](https://github.com/Celie987/qr-code-component)
- Live Site URL: [live site URL](https://celie987.github.io/qr-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Compared to the first challenge, I have learned to better pay attention to the design and to stick to it. I also paid attention to refactor the css to ensure not having unnecessary lines on it.

I have also tried to stick to the semantic html and to avoid the usage of :

```html
<div>
```

And so I am happy to finaly having replaced the div containing the QR Code by the picture tag.

```html
<figure class="qr-code"><img src="images/image-qr-code.png" alt="QR Code">
</figure>
```

And from a css perspective, I am proud to have found the code to have my main element centered onto the screen :

```css
main{
    position:absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
} 
```

As well as having finally solved the last issue that I had onto the positioning of the flex elements through the usage of top and bottom margin.

### Continued development

Working through baby steps, I will continue to make some Newbies frontendmentor challenge before moving to junior ones and and parallel will start learning javascript.

### Useful resources

- [Mozilla Developer Network](https://developer.mozilla.org/en-US/) - Enable me to find semantic html tags and to go deeper in the comprehension of them.
- [Freecodecamp YouTube Chain](https://www.youtube.com/freecodecamp) - Trainings, bootcamps and courses available for newbies.

## Author

- Frontend Mentor - [@Celie987](https://www.frontendmentor.io/profile/Celie987)

## Acknowledgments

Thanks to Zach Gollwitzer, who let me discover those Clallenges through his Frontend Web Development Bootcamp Course available on freecodecamp.

And also a big thanks to Dave Gray for his 2 very well structured courses on html and css on freecodecamp. It enables to start with very strong basics and development principles.

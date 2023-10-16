# Frontend Mentor - QR code component solution

This is my solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). A simple element made with HTML and CSS.

## Table of contents

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

![mobile version](/images/mobile_screenshot.jpg)
![desktop version](/images/desktop_screen-shot.jpg)

### Links

- Solution URL: [github]([https://your-solution-url.com](https://github.com/stankuns/qr-code-element))
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Variables | Custom properties
- VS Code
- CSS Reset

### What I learned

Despite being a simple element made with HTML and CSS, it was very good to revise some coding techniques with html and css, without worrying about responsiveness or interaction with the site.

Some interesting things to remember.

The code to insert in the header of the home page and access the chosen font:

```html
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">  
  <link rel="stylesheet" href="style.css">
```
An initial attempt at using css custom properties:

```css
:root {
    --ff-primary: 'Outfit', sans-serif; 

    --fs-primary: 16px;
    --fs-secondary: 13px;
    --fs-attribution: 11px;

    --fw-regular: 400;
    --fw-semi-bold: 500;
    --fw-bold: 700;

    --ta-primary: center;

    
    --clr-white: hsl(0, 0%, 100%);
    --clr-light: hsl(212, 45%, 89%);
    --clr-medium: hsl(220, 15%, 55%);
    --clr-dark: hsl(218, 44%, 22%);
    --clr-link: hsl(228, 45%, 44%);
    
    --a-link: none;

}
```
It's one of many ways to centre the element on the page:

```css
.card {
    background-color: var(--clr-white);
    width: 250px;
    height: 400px;
    padding: 1em;
    border-radius: 0.75em;
    position: absolute;
    transform: translate(-50%, -50%);
    top: 50%;
    left: 50%;
}
```

### Continued development

Soon, I hope to explore more CSS custom properties and also other ways to centre an element on the page.


### Useful resources

- [Modern CSS](https://piccalil.li/blog/a-modern-css-reset) - A Modern CSS Reset by Andy Bell.
- [Center DIV](https://blog.hubspot.com/website/center-div-css#center-div-horizontally-css) - It helped me think of alternatives to centre the element on the page.
- [CSS](https://www.kevinpowell.co/) - great source of lessons on css

## Author

- Website - [Fernando Stankuns](https://www.fernando.arq.br)
- Frontend Mentor - [@ystankuns](https://www.frontendmentor.io/profile/yourusername)
- Instagram - [@stankuns](https://www.instagram.com/stankuns/)
- GitHub - [@stankuns](https://github.com/stankuns)


## Acknowledgments

Thanks to everyone who teaches and makes their code available on the internet, especially Kevin Powell who is a great and kind master of CSS and coding.


# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Links

- Solution URL: https://www.frontendmentor.io/solutions/product-preview-card-component-solution-using-html-and-css-SQoHfHevwI#comment-635c491e1ef20b01905b93ec
- Live Site URL: https://guidoghg.github.io/Practice/

### Built with

- Visual Studio Code
- FlexBox
- [Styled Components] (https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap)

### What I learned

   What I learned was using CSS3 to make the main style of the page for some people may be easy but for me was challenging to 
   be able to come up with code only from my notes and my research to do what was requested.

@media (max-width: 600px){
    .mobileProduct{
        display: flex;
        flex-direction: column;
        width: 23rem;
        border-top-right-radius: 1rem;
        border-top-left-radius: 1rem;
    }

    .card {
        display: flex;
        flex-direction: column;
        background-color: var(--white);
        border-radius: 1rem;
        height: 43rem;
        width: 23rem;
        align-items: center;
        justify-content: flex-end;
    }

    .desktopProduct {
        display: none;
    }

    .text {
        display: flex;
        flex-direction: column;
        align-items: center;
        margin: 1rem;
    }

}
 
 I'm very proud of this snippet because it's what makes it responsive for mobile use.

### Useful resources

- [Example resource 1] blackbox.io/search - This helped me for getting some code snippets.

## Author

- Website - [Guido Guasch](https://github.com/guidoghg)
- Frontend Mentor - [@guidoghg](https://www.frontendmentor.io/profile/guidoghg)

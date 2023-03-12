# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./Product.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/robinpunn/frontend-mentor/tree/main/product-preview-card-component-main)
- Live Site URL: [Netlify - Product Preview](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned about the <picture> and <source> tags which I used to display the two images based on the screen size. I recently learned about mobile first development so I used that approach for this project.

```html
    <picture class="image">
        <source
          media="(min-width: 600px)"
          srcset="./images/image-product-desktop.jpg"
        />
        <img src="./images/image-product-mobile.jpg" alt="image-product" />
      </picture>
```

### Continued development

With future challenges, I want to work on using CSS Grid. I am also still confused about the ::before and ::after pseudo-elements so I plan to use them if applicable.

### Useful resources

- [W3Schools Picture Tag](https://www.w3schools.com/tags/tag_picture.asp) - I learned how to display different images based on screen size using the <picture> and <source> tags.

## Author

- Website - [Robin Punnoose](https://www.robinpunn.com)
- Frontend Mentor - [@robinpunn](https://www.frontendmentor.io/profile/robinpunn)
- LinkedIn - [@robin-punnoose](https://www.linkedin.com/in/robin-punnoose)


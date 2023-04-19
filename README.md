# card-component2
Created with CodeSandbox


This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties


### What I learned

I learned to how overlay picture on the picture. and how is working the position absolute.


```html
  <div class="imagen-card">
          <img
            src="image-equilibrium.jpg"
            alt="image-equilibrium"
            class="imagen"
          />
          <div class="overlay">
            <img src="icon-view.svg" alt="icon-view.svg" class="icon-view" />
          </div>
```
```css
   .overlay {
      position: absolute;
      top: 0;
      bottom: 0;
      left: 0;
      right: 24px;
      height: 302px;
      width: 302px;
      opacity: 0;
      transition: 0.5s ease;
      background: #00fff8;
      mix-blend-mode: normal;
      border-radius: 8px;
    }
    .card:hover .overlay {
      opacity: 0.5;
    }

    .icon-view {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      -ms-transform: translate(-50%, -50%);
      width: 44px;
      height: 33px;
    }
```






### Continued development
I'm planing to work with to overlay function, i'm not learned it so well.


### Useful resources

- (https://ka.khanacademy.org/computing/computer-programming/html-css/html-css-further-learning/a/html-css-further-learning-what-to-learn-next) - This helped me for learned css and html more.  really liked this pattern and will use it going forward.
- (https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_image_overlay_icon) - This is an amazing article which helped me finally understand 'overlay'. I'd recommend it to anyone still learning this concept.







# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor]

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
Building NFT preview card component view on disktop and mobile 

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements



## My process
 - Build the sturcture with HTML.
 - Adding CSS.
 - Adding the Active view CSS
 - Adding media Qureiy for mobile diveces.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Microsoft Edge


### What I learned

- Adding the Active view section using CSS attributes such as postion, display, opacity, transition and more

see below:

```html
<div class="product">
      <div class="hover">
        <img src="images/icon-view.svg" alt="">
      </div>
      <a href="">
        <img class="card-img" src="images/image-equilibrium.jpg" alt="">
      </a>
</div>
```
```css
.card-img{
    position: relative;
    border-radius: 20px;
    -webkit-border-radius: 20px;
    -moz-border-radius: 20px;
    -ms-border-radius: 20px;
    -o-border-radius: 20px;
    padding: 10px;
    margin-top: 10px;
    width: 100%;
}


.hover{
    position: absolute;
    z-index: 1;
    background-color: hsla(178, 100%, 50%, 0.364);
    display: flex;
    justify-content: center;
    align-items: center;
    height:260px ;
    width: 260px;
    opacity: 0;
    border-radius: 10px;
    -webkit-border-radius: 10px;
    -moz-border-radius: 10px;
    -ms-border-radius: 10px;
    -o-border-radius: 10px;
    top:15px;
    left:20px;
}

.hover:hover{
    opacity: 1;
    cursor: pointer;
    
}
```




## Author

- Zinah Zwayen - [Zinah Zwayen ]
- Frontend Mentor - [@ZinahZwayen ](https://www.frontendmentor.io/profile/ZinahZwayen )


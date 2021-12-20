# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
Recreate an NFT preview card component 
![](/design/desktop-design.jpg)
### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/images/card-view.png)

### Links

- Solution URL: [solution URL](https://github.com/Maianki/nft-preview-card-component-main/blob/main/index.html)
- Live Site URL: [live site URL](https://nft-prvw-card-component.netlify.app)

## My process

I started with writing all my HTML that I could possibly figure out seeing the challenge screenshots. Then I started adding required CSS for each part of the project. I was not aware how to change image on hover to add the preview feature so I searched on google and stumbled upon an article that I have linked in the [resources section](#useful-resources). Finally I had some problems with the footer of my card as the avatar and text around it was not getting aligned in the same line. So I tried few tricks and eventually end up getting the desired result using flexboxes.
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

I learnt how to center an element vertically and horizontally using flexbox. I also learnt how to align an image and text in a same line using flex that I used in the footer of my card componenet. I came across an amazing article about how to change image on hover that I used to add the preview on hover.

Some code snippets, see below:

```html
 <div id="card-footer">
      <img id="avatar-img" src="images/image-avatar.png" alt="avatar"> 
      <span id="creation">Creation of </span> <span id="dev-name"> Jules Wyvern</span>  
      </div>
```
```css
 #card-footer{
      display: flex;
      justify-content: left;
      background-color: hsl(216, 50%, 16%);
      width:auto;
     
      padding-left:0px;
      margin-left: 1px;
      box-sizing:border-box;
    }

    #avatar-img{
      width:20px;
      height:20px;
      border:2px solid var(--Cyan);
      border-radius:50%;
      display: inline-block;
      background:hsl(216, 50%, 16%);
      margin: 0 0;
      margin-right:.5rem;
    }
    
   #creation{
     background:green;
     padding-left:5px;
     color:var(--soft-blue);
     background-color: hsl(216, 50%, 16%);
   }
   #footer-text{
     vertical-align: top;
     font-size: 1em;
     display: inline-block;
     margin-left:1rem;
   }
    #dev-name{
      padding-left:4px;
      background-color: hsl(216, 50%, 16%);
    }
```

### Continued development

I would practice more projects where I can use flexbox and change image on hover.

### Useful resources

- [How to change image on hover with CSS](https://www.tutorialrepublic.com/faq/how-to-change-image-on-hover-with-css.php) - This article helped me in adding the preview when someone hovers on the card. I'd recommend it to anyone still learning this concept.


## Author

- Website - [Ankit Kumain](https://ankitkumain.netlify.app/)
- Twitter - [@Ankit_k10](https://twitter.com/Ankit_k10)




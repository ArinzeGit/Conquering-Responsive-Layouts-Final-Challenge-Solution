# Conquering Responsive Layouts - Final Challenge Solution

This is my solution to the final challenge of the [Conquering Responsive Layouts](https://courses.kevinpowell.co/conquering-responsive-layouts) course by [Kevin Powell](https://www.youtube.com/@KevinPowell). Kevin Powell is a web designer, front-end developer and YouTube tutor with almost 1 million subscribers and about 900 video tutorials focused mainly on CSS.

## Table of contents

- [Overview](#overview)
  - [The design specifications](#the-design-specifications)
  - [My additional features](#my-additional-features)
  - [Solution screenshots](#solution-screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The design specifications

**The given design is for big screens over 1000pixels:**  
![Big screen layout](design%20specifications/big-screen-layout.PNG)

**Additional specifications including typography and layout of middle section for small and medium screens:**  
![Additional specifications](design%20specifications/additional-specifications.PNG)

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### My additional features

- I implemented `navigation toggle button` for mobile (small screen) such that navigation is hidden until toggled on
- I improvised the layout for the navigation, header and footer sections for small and medium screens as they were not given in the design.

### Solution screenshots

**Small screen - nav toggle on:**  
![Small screen nav](solution%20screenshots/small-screen-nav.PNG)

**Small screen - nav toggle off:**  
![Small screen 1](solution%20screenshots/small-screen-1.PNG)  
![Small screen 2](solution%20screenshots/small-screen-2.PNG)

**Medium screen:**  
![Medium screen 1](solution%20screenshots/medium-screen-1.PNG)  
![Medium screen 2](solution%20screenshots/medium-screen-2.PNG)

**Big screen:**  
![Big screen 1](solution%20screenshots/big-screen-1.PNG)  
![Big screen 2](solution%20screenshots/big-screen-2.PNG)

### Links

- [GitHub Repository](https://github.com/ArinzeGit/Conquering-Responsive-Layouts-Final-Challenge-Solution)
- [Live Site URL](https://arinzegit.github.io/Conquering-Responsive-Layouts-Final-Challenge-Solution/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- [Flexbox](https://www.w3.org/TR/css-flexbox-1/) - CSS web layout model
- JavaScript

### What I learned

- I learned that it is good practice to write `mobile-first` CSS. `Desktop-first` CSS makes you write complex layout properties only to have to overwrite them in the media queries for smaller screens. In `mobile-first` CSS, mobile layouts mostly use default values of properties and media queries are rather used to add complexities for bigger screens. However the desktop design is used to write HTML so as to make provision for the complex desktop layout.
- I learned to use minimum number of media query `breakpoints` for a more maintainable code.

### Continued development

- Mobile-first CSS
- CSS Flexbox
- Media queries

I found these techniques very useful. I will continue focusing on them in future projects to refine and perfect them.

### Useful resources

- [CSS em and rem explained](https://youtu.be/_-aDOAMmDHI?si=szJH_WBPtS_7hFjx) - This YouTube video helped me understand `em` and `rem` units. I'd recommend it to anyone still learning this concept.
- [Flexbox basics](https://www.youtube.com/playlist?list=PL4-IK0AVhVjMSb9c06AjRlTpvxL3otpUd) - This 3-part YouTube playlist gave me better understanding of `flexbox`. I'd recommend it to anyone still learning this concept.
- [min(), max(), and clamp() are CSS magic!](https://youtu.be/U9VF-4euyRo?si=rCy2AUDM3HfvkVbS) - This YouTube video helped me understand the `min()`, `max()` and `clamp()` CSS functions. I'd recommend it to anyone still learning them. I found `min()` most usefull. You can use it set `width` in `percentage` and `max-width` in `px` all in one line of code!

## Author

- GitHub - [@ArinzeGit](https://github.com/ArinzeGit)
- Frontend Mentor - [@ArinzeGit](https://www.frontendmentor.io/profile/ArinzeGit)
- LinkedIn - [@Dennings-Owoh](https://www.linkedin.com/in/dennings-owoh-4839971b1/)
- Instagram - [@\_.arinze.\_](https://www.instagram.com/_.arinze._/)
- Twitter - [@Arinze98433402](https://twitter.com/Arinze98433402)

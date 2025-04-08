# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://github.com/anujohnbethel/social-links-profile-main](https://github.com/anujohnbethel/social-links-profile-main)
- Live Site URL: [https://social-links-profile-main-anujohn.netlify.app/](https://social-links-profile-main-anujohn.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```html
  --1) data-style="hover" 
  --2) aria-label="Social Meida Links"
<nav class="sociallink-links" aria-label="Social Meida Links">
        <ul class="grid-group text-align-center">
          <li><a class="button" data-style="hover" href="#" target="_blank">GitHub</a></li>
          <li><a class="button" data-style="hover" href="#" target="_blank">Frontend Mentor</a></li>
          <li><a class="button" data-style="hover" href="#" target="_blank">LinkedIn</a></li>
          <li><a class="button" data-style="hover" href="#" target="_blank">Twitter</a></li>
          <li><a class="button" data-style="hover" href="#" target="_blank">Instagram</a></li>
        </ul>
</nav>
```
```css
--1)  
body.container {

  --max-width: 300px;
  --container-padding:1rem;

  width:min(var(--max-width),(100% - var(--container-padding)*2));
  margin-inline: auto;
  

}


```
```js

```


### Continued development

No futher plan yet

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- https://piccalil.li/blog/a-more-modern-css-reset/ - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- https://www.kevinpowell.co/articles/ - This is an amazing articles which helped me.
- https://www.scottohara.me/blog/2017/04/14/inclusively-hidden.html
- https://a11y-guidelines.orange.com/en/articles/accessible-hiding/index.html#main-content - Accessible hiding and aria-hidden example

## Author

- Website - [Anu John](https://www.your-site.com)
- Frontend Mentor - [@anujohnbethel](https://www.frontendmentor.io/profile/anujohnbethel)

## Acknowledgments

-- Resetting styles - Andy Bell, https://piccalil.li/blog/a-more-modern-css-reset/
-- Articles of Kevin Powell - https://www.kevinpowell.co/articles/
-- Youtubes of Kevin Powell - https://www.youtube.com/@KevinPowell

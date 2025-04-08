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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://github.com/anujohnbethel/social-links-profile-main)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

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

# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
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

- View the optimal layout depending on their device's screen size. There is a mobile layout and a desktop layout.
- See hover and focus states for interactive elements. In particular, there is a button whose background-color should change on hover.

### Screenshots

![Desktop screenshot](images/screenshot_desktop.png)
![Mobile screenshot](images/screenshot_mobile.png)

### Links

- Solution URL: [https://github.com/harnettd/product-review-card](https://github.com/harnettd/product-review-card)
- Live Site URL: [https://harnettd.github.io/product-review-card/](https://harnettd.github.io/product-review-card/)

## My process

### Built with

- HTML5
- CSS
- [Bootstrap 5](https://getbootstrap.com/)

### What I learned

In completing this challenge, I learned how to

- move HTML elements using the `relative` value of the CSS `position` property

- define a responsive grid using Bootstrap 5, *e.g.,* 

```html
<div class="container-fluid">
    <div class="row g-0">
      <div class="col-sm">
        <div class="..."></div>
      </div>
      <div class="col-sm">
        <div class="..."></div>
      </div>
    </div>
```

- use a media query to create a device breakpoint, *e.g.,* 

```css
@media only screen and (max-width: 620px) {
  ...  
}
```
### Continued development

- I used Bootstrap 5 to define a responsive grid. No doubt, there are alternatives that I should learn to use as well.
- This is the first time that I used a media query---a pretty simple one at that. I plan to learn more about how and why media queries are used in web pages.

### Useful resources

- [Bootstrap 5 Grid System](https://getbootstrap.com/docs/5.3/layout/grid/) - Reading this webpage helped me define a responsive grid.
- [W3Schools Typical Device Breakpoints](https://www.w3schools.com/howto/howto_css_media_query_breakpoints.asp) - This is where I found the code snippet I needed to define a device breakpoint.
- [GPick](http://www.gpick.org/) - I used this tool to determine onscreen colours.

## Author

- Github - [Derek Harnett](https://github.com/harnettd)
- Frontend Mentor - [@harnettd](https://www.frontendmentor.io/profile/harnettd)

## Acknowledgments

- Thanks to [Frontend Mentor](https://www.frontendmentor.io/) for posting this challenge.

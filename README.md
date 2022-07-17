# Frontend Mentor - Stats Preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Stats Preview card component solution](#frontend-mentor---stats-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
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

- View the optimal layout for the app depending on their device's screen size

### Screenshot

🖥 Desktop:

![](/images/desktop.png)


📱 Mobile:

![](/images/mobile.png)


### Links

- Solution URL: [My solution](https://www.frontendmentor.io/solutions/stats-preview-card-component-with-html-and-css-Y_0wTbyR4)
- Live Site URL: [My live site](https://purplehippo911.github.io/StatsPreview/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learnt about two new html elements which I've never used before. The `<picture>` and `<source>`-elemnents. And I also got to practice on using promises with api's.     


```html
<picture>
        <source
            class="desktop"
            media="(min-width: 601px)"
            srcset="images/pattern-divider-desktop.svg"
        />
        <source
            class="mobile"
            media="(max-width: 550px)"
            srcset="images/pattern-divider-mobile.svg"
        />
        <img
            class="hero__pattern-divider"
            src="images/pattern-divider-desktop.svg"
            alt="Icon divider"
        />
</picture>
```

### Continued development

I will continue on learning more about js, so that I can become more comfortable using it. I'm currently learning asynchrounus js, and after that I'm thinking on starting with npm stuff.

### Useful resources

- [w3schools](https://www.w3schools.com/htmL/html_images_picture.asp) - This helped me understand a bit more about how to use the `<picture>`-element in HTML. 

## Author

- Frontend Mentor - [@purplehippo911](https://www.frontendmentor.io/profile/purplehippo911)

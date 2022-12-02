# Frontend Mentor - Single-price-grid-component solution
NEWBIE - FREE - HTML& CSS challenge 


This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![image](https://user-images.githubusercontent.com/119393713/204953185-e6a53cff-1cd1-47ed-94a1-b9444e48f868.png)
![image](https://user-images.githubusercontent.com/119393713/204953028-c750dfe1-6496-452e-970b-087a3575b60c.png)

### Links

- Solution URL: [https://github.com/TalasaDev/single-price-grid-component.git](https://your-solution-url.com)
- Live Site URL: [https://talasadev.github.io/single-price-grid-component/](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

In this challenge I focus on the accurated representation of the original UX/UI design into the development of the project. For the layout, I used grid display with 1fr for the mobile design and 1fr 1fr for the desktop design.  

One of the tricky parts of the project was the $29 price aligned with the "per month" text:

```html
<div class="price" style="font-size:2.1rem; font-weight: 700">

        &dollar;29 <span> per month</span>

</div>
```
```css
    .price {
      display: flex;
      align-items: center;
      margin-bottom: 10px;
    }

    .price span {
      margin-left: 10px;
    }
```
```

I used "opacity" property and hsl() notation to get improve the precision of the color palette. 

Hsl(Hue, Saturation, Lightness) or Hsl(Hue, Saturation, Lightness, alpha) is a functional notation that expresses an RGB color (Red, Blue, Green) according to its hue, saturation, and lightness components. An optional alpha component represents the color's transparency which is direct opposite to the opacity property. A 100% transparency, or 1, is equivalent to 0% opacity, or 0. 


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.


### Continued development

Still much to learn about layout and positioning of the elements using CSS properties. Practice, practice, practice. 
 

## Author

- Website - [coming soon](https://www.coming soon.com)
- Frontend Mentor - [@talasa-dev](https://www.frontendmentor.io/profile/talasa-dev)
- Twitter - [@coming soon... ](https://www.twitter.com/yourusername)



## Acknowledgments







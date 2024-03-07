# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Useful resources](#useful-resources)
-   [Author](#author)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout depending on their device's screen size
-   See hover and focus states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

-   Solution URL: [Add solution URL here](https://your-solution-url.com)
-   Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid
-   Mobile-first workflow

### What I learned

I learned about the `<picture>` HTML tag, and how to use different images based on media size with the `srcset` attribute.

```html
<picture class="product__img">
	<source
		srcset="images/image-product-desktop.jpg"
		media="(min-width: 600px)" />

	<img
		src="images/image-product-mobile.jpg"
		alt="Perfume bottle on table, leaves decorating it" />
</picture>
```

I also learned some techniques for screen reader accessibility using a special utlity class

```css
.visually-hidden:not(:focus):not(:active) {
	clip: rect(0 0 0 0);
	clip-path: inset(50%);
	height: 1px;
	overflow: hidden;
	position: absolute;
	white-space: nowrap;
	width: 1px;
}
```

### Useful resources

-   Guide by Kevin Powell - [Youtube](https://www.youtube.com/watch?v=B2WL6KkqhLQ) - I followed a guide by Kevin Powell to learn about media queries and responsive design while doing this challenge.

-   CSS Reset by Josh Comeau - [Blog](https://www.joshwcomeau.com/css/custom-css-reset/)

## Author

-   Website - [Taxato](https://taxato.github.io/TGS-Portfolio)
-   Frontend Mentor - [@Taxato](https://www.frontendmentor.io/profile/taxato)

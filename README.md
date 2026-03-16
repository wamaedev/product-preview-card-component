# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 
The goal of this project was to recreate a product card layout using semantic HTML and CSS while keeping the design responsive and visually accurate.

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/Screenshot%202026-03-16%20193923.png)

### Links

- Solution URL: [https://github.com/wamaedev/product-preview-card-component](https://your-solution-url.com)
- Live Site URL: [https://jade-moonbeam-552599.netlify.app/](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 
- CSS
- Flexbox
- Google Fonts
- Responsive design principles

### What I learned

While building this project, I practiced structuring a component using semantic HTML and styling it using Flexbox.

One thing I focused on was creating a clean structure for the product card and separating different elements like the product category, title, description, and pricing.

```html
<section class="product-card">

  <article class="product-info">

    <img src="./images/image-product-desktop.jpg" alt="Gabrielle Chanel perfume bottle">

    <div class="product-content">
      <p class="product-category">PERFUME</p>

      <h1 class="product-title">
        Gabrielle Essence Eau De Parfum
      </h1>

      <p class="product-description">
        A floral, solar and voluptuous interpretation composed by
        Olivier Polge, Perfumer-Creator for the House of CHANEL.
      </p>

      <div class="price">
        <span class="current-price">$149.99</span>
        <span class="old-price">$169.99</span>
      </div>

      <button>Add to Cart</button>
    </div>

  </article>

</section>
```
```css
.product-info {
  display: flex;
  gap: 25px;
  background-color: white;
  border-radius: 5px;
}
```
This helped me understand how Flexbox simplifies layout alignment and spacing.

### Continued development

In future projects I want to continue improving in:

- Responsive design using media queries

- Better layout techniques using Flexbox and Grid

- Writing cleaner and more maintainable CSS

- Improving accessibility in my HTML structure

### Useful resources

- [Frontend Mentor](https://www.frontendmentor.io/) - The design challenge and starter files
- [Google Fonts](https://fonts.google.com/) - Used to import the Montserrat and Fraunces fontsthis concept.

### AI Collaboration

I used ChatGPT during this project to help with:

- Reviewing and improving my HTML structure

- Refactoring parts of my CSS

- Understanding better layout practices using Flexbox

- Improving the documentation for my project

AI was helpful for identifying small improvements and explaining best practices while I was learning.

## Author

- Website - [Presbury Wamae](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/wamaedev)
- GitHub - [@wamaedev](https://github.com/wamaedev)


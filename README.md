# Frontend Mentor - Product Preview Card Component Solution

This is my solution to the [Product Preview Card Component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The Challenge

The goal was to build a product preview card component that closely matches the provided design.

Users should be able to:

- View an optimal layout depending on their device's screen size.
- See hover and focus states for interactive elements.

### Screenshot

![alt text](image.png)

### Links

- Solution URL: [Add your GitHub repository URL here](https://github.com/)
- Live Site URL: [Add your live website URL here](https://pages.github.com/)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties and color values
- CSS Flexbox
- CSS Media Queries
- Responsive web design
- Font Awesome icons

### What I Learned

During this project, I improved my understanding of CSS Flexbox and responsive design. I practiced centering a component horizontally and vertically, arranging elements inside a card, and adapting the layout to different screen sizes using media queries.

I also learned how to style product pricing, including displaying the original price with a strikethrough effect, and how to integrate Font Awesome icons into a button.

One of the main techniques I practiced was using media queries to change the card's layout on smaller screens:

```css
@media (max-width: 600px) {
  .container {
    display: flex;
    flex-direction: column;
    width: 90%;
    height: 90vh;
  }

  .container img {
    width: 100%;
    min-height: 50%;
  }
}
```

This allows the product image and content to stack vertically on smaller screens instead of remaining side by side.

I also practiced using Flexbox to center the card within the viewport:

```css
body {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100vw;
  height: 100vh;
}
```

### Continued Development

In future projects, I want to focus on:

- Improving responsive layouts across a wider range of screen sizes.
- Writing cleaner and more maintainable CSS.
- Using CSS custom properties to make colors and other values easier to manage.
- Improving accessibility through semantic HTML and appropriate alternative text.
- Implementing hover and focus states for interactive elements.
- Improving my understanding of typography, spacing, and layout techniques.

### Useful Resources

- [MDN Web Docs - CSS Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout) - Helped me understand how to arrange elements and align the card's content.
- [MDN Web Docs - Using Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries) - Useful for learning how to adapt layouts to different screen sizes.
- [Font Awesome](https://fontawesome.com/) - Used to add the shopping cart icon to the Add to Cart button.
- [The Markdown Guide](https://www.markdownguide.org/) - A useful reference for formatting README files.

### Author

- GitHub - [@Klejdi81](https://github.com/Klejdi81)
- Frontend Mentor - [@Klejdi81](https://www.frontendmentor.io/)

## Acknowledgments

Thanks to [Frontend Mentor](https://www.frontendmentor.io/) for providing the design challenge and an opportunity to practice HTML and CSS by building a realistic component.

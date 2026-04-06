# Frontend Mentor - Intro component with sign up form solution

This is a solution to the [Intro component with sign up form challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/intro-component-with-signup-form-5cf91bd49edda32581d28fd1). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
- [Built with](#built-with)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Receive an error message when the `form` is submitted if:
  - Any `input` field is empty. The message for this error should say _"[Field Name] cannot be empty"_
  - The email address is not formatted correctly (i.e. a correct email address should have this structure: `name@host.tld`). The message for this error should say _"Looks like this is not an email"_

### Screenshot

![Intro component with signup form solution](./screenshot.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com)
- Live Site URL: [Live Demo](https://your-live-site-url.com)

## Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Flexbox
- Mobile-first workflow
- Responsive design
- BEM naming convention
- Google Fonts (Poppins)

### What I learned

This project helped me deepen my understanding of several key concepts:

**CSS Grid & Flexbox**: Creating a responsive layout that transitions from a single column (mobile) to two columns (desktop) using CSS Grid with media queries.

```css
.card {
  display: grid;
  grid-template-columns: 1fr;
}

@media (min-width: 900px) {
  .card {
    grid-template-columns: 1fr 1fr;
  }
}
```

**Form validation & accessibility**: Building an accessible form with proper labels, required fields, and error message handling for empty fields and invalid email formats.

```html
<input
  type="email"
  id="email"
  placeholder="Email Address"
  class="card__form-input"
  required
/>
```

**Responsive Design**: Implementing a mobile-first workflow ensuring the component looks perfect across different screen sizes (375px - 1440px).

**BEM Naming Convention**: Organizing CSS classes using the Block Element Modifier methodology for better code maintainability and scalability.

### Continued development

Areas I want to improve in future projects:

- **JavaScript form validation**: Implementing client-side form validation with real-time error feedback and custom error messages
- **Advanced CSS animations**: Adding smooth transitions and animations for hover states and form interactions
- **Accessibility improvements**: Enhancing form accessibility with ARIA labels and better keyboard navigation
- **Performance optimization**: Optimizing images and CSS for faster load times
- **Cross-browser testing**: Ensuring consistent experience across different browsers and devices

### Useful resources

- [MDN Web Docs - CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout) - Comprehensive guide to CSS Grid layout
- [MDN Web Docs - Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout) - Essential resource for understanding Flexbox
- [BEM Naming Convention](https://en.bem.info/) - Methodology for organizing and naming CSS classes
- [Frontend Mentor](https://www.frontendmentor.io) - Great platform for practicing front-end development with real-world projects
- [Google Fonts - Poppins](https://fonts.google.com/specimen/Poppins) - The font family used in this project

## Author

- Frontend Mentor - [@Diego Quevedo](https://www.frontendmentor.io/profile/yourusername)
- GitHub - [Diego Quevedo](https://github.com/yourusername)

## Acknowledgments

- Challenge provided by [Frontend Mentor](https://www.frontendmentor.io) - A great platform for improving front-end development skills through realistic coding challenges.
- Design inspiration and assets provided by Frontend Mentor's design team.
- Thanks to the Frontend Mentor community for support and feedback.

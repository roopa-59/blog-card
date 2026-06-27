# Frontend Mentor - Blog Preview Card Solution

This is my solution to the **Blog Preview Card** challenge on Frontend Mentor. The goal of this project was to recreate the provided design as accurately as possible using semantic HTML and CSS while following responsive design principles.

Through this project, I practiced building a clean card layout, using Flexbox for alignment, applying spacing consistently, and implementing hover effects.

---

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

---

## Overview

### The Challenge

Users should be able to:

- View the blog preview card matching the provided design.
- See hover states for interactive elements.
- Experience a responsive layout across different screen sizes.

### Screenshot

> Add your screenshot here.

```md
![Project Screenshot](./screenshot.png)
```

### Links

- **Solution URL:** https://www.frontendmentor.io/solutions/your-solution-link
- **Live Site URL:** https://roopa-59.github.io/blog-card/

---

# My Process

## Built With

- Semantic HTML5
- CSS3
- Flexbox
- Responsive Design
- Google Fonts (Figtree)

---

## What I Learned

This project helped me understand several important CSS concepts.

### 1. Inline Elements and the Box Model

Initially, I used a `<span>` element for the "Learning" tag. I tried applying `margin-top`, but it had no visible effect because `<span>` is an inline element.

I learned that vertical margins do not behave as expected on inline elements. Changing it to `display: inline-block` allowed the box model properties to work correctly.

```css
.tag {
  display: inline-block;
  margin-top: 1rem;
}
```

---

### 2. Using Flexbox for Alignment

I used Flexbox to align the author's avatar and name horizontally while keeping them vertically centered.

```css
.author {
  display: flex;
  align-items: center;
  gap: 1rem;
}
```

This made the layout cleaner and easier to manage.

---

### 3. Choosing CSS Units

During this project, I learned when to use different CSS units.

- `rem` for spacing and typography
- `%` for responsive widths
- `px` for shadows and thin borders

Replacing fixed pixel values with `rem` made the layout more scalable and accessible.

---

### 4. Responsive Layout

Instead of giving the card a fixed width, I used both `width` and `max-width`.

```css
.card {
  width: 90%;
  max-width: 24rem;
}
```

This allows the card to shrink on smaller screens while maintaining a consistent maximum width on larger screens.

---

## Continued Development

In future projects, I would like to improve the following skills:

- Writing cleaner and more organized CSS
- Using CSS variables for colors and spacing
- Learning CSS Grid layouts
- Improving accessibility by adding better focus styles
- Following a mobile-first workflow more consistently

---

## Useful Resources

- **Frontend Mentor** – Helped me practice building real-world UI components.
- **MDN Web Docs** – Used to understand CSS properties and HTML semantics.
- **Google Fonts** – Used to include the Figtree font family.

---

## AI Collaboration

I used ChatGPT as a learning assistant throughout this project.

It helped me:

- Understand why some CSS properties were not working.
- Debug layout issues.
- Learn the difference between `px`, `rem`, and `%`.
- Understand Flexbox alignment.
- Improve my CSS structure and responsiveness.

Instead of generating the complete solution, I used AI mainly to understand concepts, identify mistakes, and learn best practices while implementing the project myself.

---

# Author

- GitHub: https://github.com/roopa-59
- Frontend Mentor: https://www.frontendmentor.io/profile/roopa-59

# Frontend Mentor - Four Card Feature Section Solution

This repository contains my solution to the [Four Card Feature Section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). The goal was to build a responsive feature section matching the provided design.

## Table of Contents

* [Overview](#overview)
* [My Process](#my-process)
* [Built With](#built-with)
* [What I Learned](#what-i-learned)
* [Continued Development](#continued-development)
* [Useful Resources](#useful-resources)
* [Author](#author)
* [Acknowledgments](#acknowledgments)

## Overview

### The Challenge

Develop a feature section with four cards that:

* Stack vertically on mobile.
* Transform into a diamond-shaped layout on desktop (min-width: 768px).
* Match the design’s typography, colors, spacing, and decorative elements.

### Screenshot

![Desktop Layout](./Screenshot%202025-06-08%20181638.png)

### Links

* **Solution URL**: [GitHub Repository](https://github.com/syarief02/four-card-feature-section)
* **Live Demo**: [View on GitHub Pages](https://syarief02.github.io/four-card-feature-section)

## My Process

1. **Setup & Planning**: Reviewed the provided design assets and spec from Frontend Mentor.
2. **HTML Structure**: Created semantic HTML5 markup for the feature section and individual cards.
3. **Mobile-First Styling**:

   * Applied CSS variables for color and typography consistency.
   * Used Flexbox to stack cards in a single column.
   * Added pseudo-elements (`::before`) for the colored stripe on each card.
   * Positioned icons with `position: absolute` inside each card.
4. **Card Group Wrappers**:

   * Wrapped certain cards in container `<div>`s to control grouping and alignment on desktop.
   * Applied custom margins to each card class (`.card-supervisor`, `.card-karma`, etc.) to fine-tune spacing.
5. **Desktop Breakpoint (min-width: 768px)**:

   * Kept using Flexbox; adjusted wrapper flex directions and orders.
   * Rearranged card order and applied specific margins to achieve the diamond layout—no CSS Grid used.
6. **Testing & Refinement**:

   * Verified responsiveness at multiple screen widths.
   * Tweaked spacing and margin values for pixel-perfect alignment.

## Built With

* **HTML5**
* **CSS Custom Properties** (Variables)
* **Flexbox** for layout
* **Pseudo-elements** (`::before`) for decorative stripes
* **Absolute positioning** for icons
* **Mobile-first workflow**

## What I Learned

* Creating complex layouts purely with Flexbox by manipulating `order` and custom margins.
* Using pseudo-elements to add decorative elements without extra HTML.
* Positioning elements inside cards with `position: absolute` while keeping the card responsive.
* Managing breakpoints to transform layout dramatically without adding new markup.

## Continued Development

* Add focus and hover interactions for better accessibility and UX.
* Explore toggling a dark theme by switching CSS variables.
* Implement CSS transitions for smooth hover effects.

## Useful Resources

* [Four Card Feature Section Challenge Brief](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK)
* [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - CSS-Tricks
* [MDN Pseudo-elements](https://developer.mozilla.org/en-US/docs/Web/CSS/::before) - Documentation on `::before` and `::after`

## Author

* **GitHub**: [syarief02](https://github.com/syarief02)
* **Frontend Mentor**: [@syarief02](https://www.frontendmentor.io/profile/syarief02)

## Acknowledgments

Thanks to Frontend Mentor for this challenge and to the community for inspiration!

# Product preview card

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Useful resources](#useful-resources)

## Overview

### Screenshot

#### Mobile View port (width < 784px)
![Screenshot for Product Preview Card in mobile viewport](./documentation/screenshots/product-preview-card___mobile-view-port.png)

#### Tablet View port (width < 1440px)
![Screenshot for Product Preview Card in tablet viewport](./documentation/screenshots/product-preview-card___tablet-view-port.png)

#### Desktop View port (width >= 1440px)
![Screenshot for Product Preview Card in desktop viewport](./documentation/screenshots/product-preview-card___desktop-view-port.png)


### Links

- Solution URL: [https://github.com/Ahmed-Araby/product-preview-card](https://github.com/Ahmed-Araby/product-preview-card)
- Live Site URL: [https://ahmed-araby.github.io/product-preview-card/](https://ahmed-araby.github.io/product-preview-card/)

## My process

### Built with

- typography optimization
- Responsive Images
- converting figma design to frontend page
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### Useful resources
* https://web.dev/learn/performance/optimize-web-fonts
* responsive images
  * https://web.dev/learn/design/responsive-images
  * https://www.theodinproject.com/lessons/node-path-advanced-html-and-css-responsive-images#aspect-ratio-knowledge-check
  * https://css-tricks.com/a-guide-to-the-responsive-images-syntax-in-html/
  * https://medium.com/hceverything/applying-srcset-choosing-the-right-sizes-for-responsive-images-at-different-breakpoints-a0433450a4a3
  * https://webdesign.tutsplus.com/quick-tip-how-to-use-html5-picture-for-responsive-images--cms-21015t
  * https://imagekit.io/responsive-images/#ect-rtt-and-downlink
  * https://www.debugbear.com/blog/properly-size-images
* https://zellwk.com/blog/media-query-units/
* awsome tutorials with walk through the process of converting the figma design of this challenge to html, css and js with the correct semantics
  * https://fedmentor.dev/posts/html-plan-product-preview/ 
  * https://uxplanet.org/challenge-006-product-preview-card-component-2de1d66fb4f6

### Notes
* hiding an element with visibility: hidden; property, will only hide the element visually but it still exist in the DOM tree and preserve its space in the document flow
* setting display: none; property, will remove the element from the document flow (hide it) but the element is still exist in the DOM tree and occupies memory.
* removing the element with JS code using remove() or removeChild() methods will delete the element completely from the DOM tree and free up memory (offcourse this mean the element is not part of the document flow any more and it is not displayed in the screen).

### TODO, performance enhancement and consistency
- [ ]set fallback font
- [ ] use build tool to minimize size of requested files
- [ ] compare the speed of retrieving the font file from google fonts vs hosting them on github pages
- [ ] host the fonts on a local server, introduce artifical delay, request the fonts from the local server, and play around with the font-display property

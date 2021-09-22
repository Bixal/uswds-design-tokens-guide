---
layout: default
title: Layout and spacing
nav: Language
permalink: /language/layout-and-spacing/
sidenav: language-side-nav
---
# {{ page.title }}
{: .bixal-font-serif}

- USWDS uses a mobile-first, twelve-column grid system.
- Spacing units are mostly based on an 8-pt grid
  - There are also some "half-unit" and pixel values for small size needs.
- There also semantic, screen size values that correspond to breakpoints, like `mobile` and `desktop-lg`. These can be handy for sizing elements in larger multiples of 8 while considering how screen size may affect the design.
- *Use the grid in your designs*. Understanding how much horizontal space elements should take at varying screen sizes is critical for adopting a responsive-first mindset.
  - Use responsive variants with design tokens and utility classes to adapt your design at different breakpoints. For example, an element with the `grid-col-12` and `desktop:grid-col-6` will take up the full 12 columns at mobile-and-up sizes, until it gets to desktop when it will switch to taking up only half the grid with 6 columns.
  - Responsive variants can also be applied to spacing tokens.
- Familiarizing yourself with the multiple of width, height, maring, and padding utility classes can be very helpful when it comes to setting expectations and ensuring quality of your design in the broswer.
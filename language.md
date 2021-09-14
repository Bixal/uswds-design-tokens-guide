---
layout: default
title: Learn the language
nav: Language
permalink: /language/
sidenav:
    - title: Concept 1
      url: "#concept-1"
    - title: Concept 2
      url: "#concept-2"
---
# {{ page.title }}

## What is a token?

From [USWDS](https://designsystem.digital.gov/design-tokens/):

> _Design tokens are a limited set of discrete options, just like a scale of musical notes is drawn from the spectrum of all possible frequencies. Or like the presets on a car radio — not every option, just a specific selection._

- A token is a set of name and value pairs.
- The names are the words we use in our design that make it easier to understand and apply those _discrete options_.
- For example, instead of describing our type using pixel sizes, we use t-shirt sizes, like `sm`, `md`, and `lg`. When describing colors, we use palettes based on their function, like `primary-dark` or `warning-light.`
- The value of the pair is set to a default, but it can be changed if needed.

## System tokens & theme tokens

- System tokens are the complete set of name/value pairs defined in USWDS.
- They provide a lot of flexbility but are generally intended to be used as a foundation for a more limited palette of options.
- Theme tokens are the more limited palette intended for general use in a project.
- For example, the color system tokens include 10 grades for 25 different hues of the color wheel. You probably don't need 250 colors available for immediate use in your project. The theme color tokens use a handful of grades for specific purposes like `primary`, `secondary`, `accent-cool`, `accent-warm`, and `base`. This provides a more practical and useful palette.
- For typography, there are 21 preset systems tokens, but a theme set of 9 options with sizes ranging from `3xs` to `3xl`.
- The default values of the theme tokens reference the system token names.
- The theme and system tokens concept primarily applies to color and type size.

## Utility classes

- Utility classes are how the Design System translates between the language of design tokens and the browser.
- For example, `base-dark` is defined in the Design System, but applying the CSS class of `text-base-dark` or `border-base-dark` is how you apply that color token to an element on a web page.
- It's helpful to be aware of utility classes and what they offer because you can reference them in your design files or documentation to make your intent clear to developers.

## Typesetting

- Understanding font normalization and how it affects typesetting
- Defining type styles using font-family, font-size, and line-height
- Other type considerations: weight, letterspacing, and measure (line-length)

## Color

- Understanding color grades and accessibility
- Defining theme and state tokens (unless they don't work for your project)
- Unless you have to use specific brand color values, consider using colors from the system token palette to benefit from the accessible contrast features.
  - Use the [USWDS Color Tool](https://civicactions.github.io/uswds-color-tool/) from Civic Actions to find system token colors similar to existing colors on a project that you may want to migrate.

## Layout and spacing

- USWDS uses a mobile-first, twelve-column grid system.
- Spacing units are mostly based on an 8-pt grid
  - There are also some "half-unit" and pixel values for small size needs.
- There also semantic, screen size values that correspond to breakpoints, like `mobile` and `desktop-lg`. These can be handy for sizing elements in larger multiples of 8 while considering how screen size may affect the design.
- *Use the grid in your designs*. Understanding how much horizontal space elements should take at varying screen sizes is critical for adopting a responsive-first mindset.
- Familiarizing yourself with the multiple of width, height, maring, and padding utility classes can be very helpful when it comes to setting expectations and ensuring quality of your design in the broswer.

## Other styling and utilities

- There are a variety of other tokens:
  - Border
  - Outline
  - Shadow
  - Paragraph styles, like `text-align` and `text-indent`
  - Display styles for positioning and overflow
- Flexbox provides even more powerful tools for working within the grid, but it is more complicated and takes some getting used to.

## Components & tokens


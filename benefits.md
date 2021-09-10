---
layout: default
title: Benefits
permalink: /benefits/
sidenav:
    - title: Introducing design tokens
      url: "#introducing-design-tokens"
    - title: Keys and values
      url: "#keys-and-values"
---
# {{ page.title }}

USWDS visual design is based on consistent palettes of typography, spacing units, color, and other discrete elements of style we call design tokens.
{: .usa-intro}

## Introducing design tokens

Anything we see on a website is built from elements of style: elements like color, spacing, typography, line height, and opacity. The CSS rules associated with these elements can accept a broad continuum of values — in the case of color, there are over 16 million separate colors in the RGB color space. Font size, line height, spacing, and others can accept a similarly wide range of values.

This degree of choice can slow down design work and make communication between designer and developer unnecessarily granular. USWDS seeks to maximize design efficiency and improve communication with design tokens: the discrete palettes of values from which we base all our visual design.

Design tokens are a limited set of discrete options, just like a scale of musical notes is drawn from the spectrum of all possible frequencies. Or like the presets on a car radio — not every option, just a specific selection.

## Keys and values

You can think of a design token as a key that unlocks a specific value. Often, the specific value is less important than its effect. Each token is a quoted string or, with only the exceptions of 1px and 2px, a unitless number — and the mechanism by which the final display value is unlocked is a function, mixin, or utility class.

We can’t include tokens directly in our Sass, like max-width: 1, rather we use a helper function like max-width: measure(1) or a mixin like @include u-measure(1). All USWDS design tokens have helper mixins and functions to use them in component Sass.
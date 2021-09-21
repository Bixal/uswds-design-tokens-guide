---
layout: default
title: System tokens & theme tokens
nav: Language
permalink: /system-tokens-and-theme-tokens/
sidenav:
    - title: What is a token?
      url: "what-is-a-token"
    - title: System tokens & theme tokens
      url: "system-tokens-and-theme-tokens"
    - title: Utility classes
      url: "utility-classes"
    - title: Typesetting
      url: "typesetting"
    - title: Color
      url: "color"
    - title: Layout and spacing
      url: "layout-and-spacing"
    - title: Other styling and utilities
      url: "other-styling-and-utilities"
    - title: Components & tokens
      url: "components-and-tokens"
---
# {{ page.title }}
{: .bixal-font-serif}

- System tokens are the complete set of name/value pairs defined in USWDS.
- They provide a lot of flexbility but are generally intended to be used as a foundation for a more limited palette of options.
- Theme tokens are the more limited palette intended for general use in a project.
- For example, the color system tokens include 10 grades for 25 different hues of the color wheel. You probably don't need 250 colors available for immediate use in your project. The theme color tokens use a handful of grades for specific purposes like `primary`, `secondary`, `accent-cool`, `accent-warm`, and `base`. This provides a more practical and useful palette.
- For typography, there are 21 preset systems tokens, but a theme set of 9 options with sizes ranging from `3xs` to `3xl`.
- The default values of the theme tokens reference the system token names.
- The theme and system tokens concept primarily applies to color and type size.
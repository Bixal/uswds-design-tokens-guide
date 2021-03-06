---
layout: default
title: Components & tokens
nav: Language
permalink: /language/components-and-tokens/
sidenav: language-side-nav
---
# {{ page.title }}
{: .bixal-font-serif}

- Components are essentially HTML elements with specific classes applied.
- For example, you can render a default USWDS button using this code: `<button class="usa-button">Default</button>`. The class `usa-button` includes the basic styling and functionality.

> <button class="usa-button">Default</button>

- You can use design tokens and utility classes to build on top of that component foundation to customize it to your needs. For example, to use the default button but change the border radius, you can simply add the a utility like this: `<button class="usa-button radius-0">Default</button>`

> <button class="usa-button radius-0">Default</button>

- You can also take it further: `<button class="usa-button bg-accent-cool text-ink border-05 border-ink padding-x-5 radius-pill hover:border-05 hover:border-accent-cool hover:bg-accent-cool-darker">Default</button>`
  - This builds on usa-button by changing the text and background colors, adding a border, changing the border radius, and increasing the horizontal padding.

> <button class="usa-button bg-accent-cool text-ink border-05 border-ink padding-x-5 radius-pill hover:border-05 hover:border-accent-cool hover:bg-accent-cool-darker">Default</button>
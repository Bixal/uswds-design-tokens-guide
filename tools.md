---
layout: default
title: Use the tools
nav: Tools
permalink: /tools/
sidenav:
    - title: Applications 1
      url: "#application-1"
    - title: Applications 2
      url: "#application-2"
---
# {{ page.title }}

## USWDS Component Library in Figma

## Figma tokens plug-in
#### What is Figma Tokens? ####
The Figma Tokens plugin allows you to integrate tokens into your designs in Figma. There are three approaches to begin using the Tokens plugin:
  1. Create your tokens from scratch, 
  2. Import your existing styles into the Tokens plugin, 
  3. Or create tokens using the built-in JSON editor. 

#### Importing tokens ####
- If you're working with an existing design system and you've already defined font styles, colors, spacing, etc. in Figma, then use the import feature to generate tokens based on those existing styles. 
- This can be the easiest way to start using tokens because the plugin will auto-generate the tokens based on what you have in your system, instead of starting from nothing. 

![import button on tokens plugin](/assets/img/import-styles.jpeg)

- After importing existing styles to create tokens, you can adjust the token names with your developer and come up with the naming conventions that make the most senese for you.

- If your developer is already using tokens, you can use the JSON editor in the tokens plugin to import and begin designing from what they already have. 

![json editor in plugin](/assets/img/json-view.png)

#### Some Considerations ####
- While this plugin can work magic in building collaboration between design and development, it does have some glitches. Sometimes editing solely with the tokens does not work as expected. 

- Ideally, after the tokens are created, you can assign your layers tokens and control layer appearance by changing the tokens. 

- For example, typography tokens. If you are starting from scratch, you would create a font-family token, a line-height token, and a size-token. Next, you would combine these tokens to create a typography token. 

- Let's say you created a token for Heading 1. Each place that you have a Heading 1 text layer, select the token from the plugin and assign that token to all of the H1 text layers. From here, when you want to make changes to H1 you would update the token and it will then update the appearance of all H1 layers in your design. This is where things can get sticky and may not always update the appropriate text layers. 

- Another consideration is the tokens are **not** connected to your saved styles in Figma. Therefore, if you want to continue to use your saved styles they must be updated separately each time you update your tokens, or vice versa. Alternatively, you may choose to only use the Figma Tokens plugin as your source of truth instead of balancing both the tokens and styles. If that is the case, then you only need to rely on the tokens and updates made there. 

#### Download the Plugin ####
[Download](https://docs.tokens.studio/) the plugin. You may need to refresh Figma in order to see the plugin.  

#### Try it out ####
Duplicate the [USWDS component library](https://www.figma.com/community/file/817531077036545462) and try importing tokens with the Figma Token plugin. After you see the tokens populate, assign your layers tokens and see how you can edit your design by changing the values of the tokens. 

#### Looking for more information on the plugin? ####
Check out this [video tutorial](https://youtu.be/Ka1I5TphDb0). 

## Other Figma plug-ins

- **Lorem ipsum**: generates filler text for text layers
- **Stark**: accessibility checker
- **Unsplash**: free, high-quality photos
- **Able**: another accessibility plugin to check contrast
- **Rename It**: allows you to batch rename layers and frames to keep your files organized


## USWDS Boilerplate on CodePen

## USWDS Boilerplate on GitHub

## USWDS Page Templates project
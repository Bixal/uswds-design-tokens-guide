---
layout: default
title: USWDS Boilerplate on CodePen
nav: Tools
permalink: /tools/uswds-boilerplate-on-codepen/
sidenav: tools-side-nav
---
# {{ page.title }}

CodePen is a web-based editor for experimenting with and prototyping HTML, CSS, and JavaScript. It's the easiest way to start getting familiar with USWDS code snippets and design tokens because you don't have to worry about dev environments and hosting. All you do is put some code in the relevant boxes and it just works.

## Getting started

1. You can edit CodePens without an account, but since you'll probably want to save your work, we recommend you [sign up for a free account](https://codepen.io/accounts/signup/user/free).
1. Open our [USWDS Boilerplate pen](https://codepen.io/pglevy/pen/abBgJbe).
1. To save a copy, press the `fork` button on the right side of the toolbar at the bottom of the page.
1. The name will default to the same as the original, but you can rename it by pressing the pencil icon next to the name.

![Default view of the USWDS Boilerplate pen on CodePen]({{ site.baseurl }}/assets/img/boilerplate-editors.png){: .border-base-light .border-1px}

## Understanding the settings

- This pen has all the settings needed to use the default version of USWDS.
- If you want, you can view these by pressing the `Settings` button.
- The HTML settings link to a hosted version of the CSS.
- The JS settings link to the a hosted version of the JS file that is needed for some components to work.
- There are no CSS settings by default.

![CodePen settings panel]({{ site.baseurl }}/assets/img/pen-settings.png){: .border-base-light .border-1px}

## Understanding the default code

- This boilerplate makes use of CodePen's [include feature](https://blog.codepen.io/documentation/adding-external-resources/#html-can-be-an-external-resource-too-6), which allows you to use code from one pen inside another.
- We use this for the header and footer so there is not as much code in the main file to get confused with.
- If you don't want to use these, you can delete them or comment them out (`command-forward slash`).
- There are two options for the header: you can delete or comment out the one you don't want to use.
- To see the pens for the headers and footer, go to the links for those pens in your browser.

## Creating your own page with USWDS components

- Go to the USWDS Components page and find the component you want to use.
- Open the `Component code` accordion to see the code that is used to render the component on the page. (This is collapsed by default.)
    - In some cases, there will be some extra code for headings or variations of the component.
    - It may take some practice to grab only what you need.
- Copy and paste the code snippet into your codepen.

It should show up on the page after a second or two.

![Selecting a code snippet on the USWDS Alert Component page]({{ site.baseurl }}/assets/img/alert-code-snippet.png){: .border-base-light .border-1px}

![The USWDS Alert Component in a CodePen]({{ site.baseurl }}/assets/img/alert-component.png){: .border-base-light .border-1px}

## Troubleshooting and tips

### Collapse your code to reduce noise

- Each HTML element (like a paragraph or a heading or a div) in CodePen is like its own accordion.
- You can click the triangle icon next to any line number to collapse the content within the element on that line.
- This helps limit the amount of code you have to look at while you're trying to figure things out.

### Format frequently to avoid errors

- After you paste in a snippet or make some changes, select the `Format HTML` command in the dropdown menu for the HTML editor.
- This makes all the code nice and neat so you can more easily see how all the nested elements are related to each other.
- This can make it easier to see where you might have missed a closing tag on an element or other syntax errors.
- HTML is pretty forgiving, so there are many errors, but if there is a problem, CodePen will give you some type of error message.

### Change your view for a new perspective

- The default layout is helpful for working with code and seeing the results right away.
- There are other views avaible, for example, you can change the layout of your editors or hide them completely.
- Press the `Change view' button to see your options.
- You may want to stack the editors on top of your results view to see the full wdith of your design.
- There is also a full page view, which is nice to open in a separate tab so you can quickly move between editing code/content and seeing the whole page.

![CodePen view with editors on top of the results preview]({{ site.baseurl }}/assets/img/editors-on-top.png){: .border-base-light .border-1px}

![Full page view of CodePen]({{ site.baseurl }}/assets/img/full-page-view.png){: .border-base-light .border-1px}
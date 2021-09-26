---
layout: default
title: Understand the benefits
nav: Benefits
permalink: /benefits/
---
# {{ page.title }}

You’ve heard of design tokens. You know they’re good for you. But is it really worth investing the time?
{: .font-sans-lg .bixal-font-sans-serif .measure-3}

Check out these tips for making the case:

<ul>
{% for item in site.data.benefits-side-nav %}
<li>
<a href="{{ site.baseurl }}{{ item.url }}" class="text-bold">{{ item.title }}</a>
</li>
{% endfor %}
</ul>
---
layout: default
title: Learn the language
nav: Language
permalink: /language/
---
# {{ page.title }}
{: .bixal-font-serif}

The U.S. Web Design System has its own vocabulary and syntax. To vibe with your team, you gotta speak the lingo.
{: .font-sans-lg .bixal-font-sans-serif .measure-3}

These are some tips and practices we recommend:

<ul>
{% for item in site.data.language-side-nav %}
<li>
<a href="{{ site.baseurl }}{{ item.url }}" class="text-bold">{{ item.title }}</a>
</li>
{% endfor %}
</ul>
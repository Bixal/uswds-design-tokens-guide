---
layout: default
title: Use the tools
nav: Tools
permalink: /tools/
---
# {{ page.title }}

Now that you know, it’s time to level up your toolset with plug-ins and templates to make it real.
{: .font-sans-lg .bixal-font-sans-serif .measure-3}

<ul>
{% for item in site.data.tools-side-nav %}
<li>
<a href="{{ site.baseurl }}{{ item.url }}" class="text-bold">{{ item.title }}</a>
</li>
{% endfor %}
</ul>
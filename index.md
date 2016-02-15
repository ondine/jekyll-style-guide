---
layout: default
---

## {{ site.description }}
{: .lead }

### Why write this?

Jekyll's increadibly flexible, but in some instances, the lack of common conventions make things harder for users. For one, there are many common design patterns that are still relatively unknown to new users (e.g., using `permalink: /about/` in `about.md`, rather than creating `/about/index.md`). For another, when writing a plugin or theme intended to be used across sites, should it look for `site.title` or `site.name`? `site.description` or `site.tagline`? Moar options, moar problems.

### Guides

<ul>
{% for doc in site.docs %}
  <li><a href="{{ doc.url }}">{{ doc.title }}</a></li>
{% endfor %}
</ul>
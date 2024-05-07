---
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

There is an [XML Version]({{ base_path }}/sitemap.xml) available as well.

{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}
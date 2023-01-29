---
layout: page
title: Releases
---

<ul>
{% for release in site.github.releases %}
  <li>
    <a href="{{ release.html_url }}">{{ release.tag_name }}</a>
    <p>{{ release.body }}</p>
  </li>
{% endfor %}
</ul>

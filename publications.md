---
layout: default
title: "Publications & Technical Reports"
---

## Publications & Technical Reports

<ul>
  {% for pub in site.publications %}
    <li>
      <a href="{{ pub.url | relative_url }}">{{ pub.title }}</a>
      <br><small>{{ pub.authors }} — {{ pub.journal }}, {{ pub.year }}</small>
    </li>
  {% endfor %}
</ul> 
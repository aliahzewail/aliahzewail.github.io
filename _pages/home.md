---
layout: home
author_profile: true
---

<h2>Recent News!</h2>

<ul style="list-style: none; padding-left: 0;">
  {% for item in site.data.news %}
    <li style="margin-bottom: .6rem;">
      <strong>[{{ item.date }}]</strong> {{ item.text }}
    </li>
  {% endfor %}
</ul>


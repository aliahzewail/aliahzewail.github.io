---
layout: home
author_profile: true
---

## News

<ul class="taxonomy__index">
  {% for item in site.data.news %}
    <li>
      <strong>{{ item.date }}:</strong> {{ item.text }}
    </li>
  {% endfor %}
</ul>

<small>
  For a full list of activities, see my <a href="/cv/">CV</a>.
</small>

<hr class="hr--small">

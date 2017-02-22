

---
layout: default
description: Dan's Simple E-Portfolio
---


<div id="pages">
  <h2>GitHub Code Pages</h2>
  <ul>
    {% for page in site.html_pages %}
      {% if page.title %}
        <li><a href="{{ https://github.com/SofterCode/ITBAProjects }}">{{ ITBA Projects Repository }}</a></li>
      {% endif %}
    {% endfor %}
  </ul>
</div>

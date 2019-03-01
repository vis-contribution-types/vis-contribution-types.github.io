---
layout: default
---

{% for item in site.contribution_types %}
  <div class="type-name"><a href="{{ item.id }}">{{item.name}}</a></div>
  <span class="type-description">{{item.description}}</span>
{% endfor %}

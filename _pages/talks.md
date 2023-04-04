---
permalink: /talks/
title: Talks
---

Some presentations that I've given.



<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Talks" }}</h3>
  

{% assign entries_layout = page.entries_layout | default: 'list' %}
<div class="entries-{{ entries_layout }}">
  {% for post in site.categories['Talk'] limit:5 %}
    {% include archive-single.html type=entries_layout %}
  {% endfor %}
</div>

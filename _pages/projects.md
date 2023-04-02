---
permalink: /projects/
title: "Projects"
---

This is the page for my notable projects that I'd like to show off.


<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Project Updates" }}</h3>
  

{% assign entries_layout = page.entries_layout | default: 'list' %}
<div class="entries-{{ entries_layout }}">
  {% for post in site.categories['Project'] limit:5 %}
    {% include archive-single.html type=entries_layout %}
  {% endfor %}
</div>

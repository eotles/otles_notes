---
permalink: /press/
title: Press
---

All the news that's fit to print.
Always love sharing my work with others. Feel free to reach out if you'd like to talk.



<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Press" }}</h3>
  

{% assign entries_layout = page.entries_layout | default: 'list' %}
<div class="entries-{{ entries_layout }}">
  {% for post in site.tags['Press'] limit10 %}
    {% include archive-single.html type=entries_layout %}
  {% endfor %}
</div>

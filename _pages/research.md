---
permalink: /research/
title: "Research"
---

My research is at the intersection of AI & healthcare, with a focus on the interface between clinical workflows and predictive models. I utilize methods from the domains of clinical informatics, machine learning, and operations research. My work spans the healthcare AI lifecycle with projects advancing from model development/evaluation, technical integration, and connection with clinical workflows.

<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Research Updates" }}</h3>
  

{% assign entries_layout = page.entries_layout | default: 'list' %}
<div class="entries-{{ entries_layout }}">
  {% for post in site.tags['Research'] limit:5 %}
    {% include archive-single.html type=entries_layout %}
  {% endfor %}
</div>

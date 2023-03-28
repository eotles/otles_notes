---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
author_profile: false

#sidebar:
#  nav: "blogsidebar"

# DON'T EDIT PERMALINK - WEIRD PAGINATION ISSUE OTHERWISE
# https://github.com/mmistakes/minimal-mistakes/issues/627#issuecomment-536759630
# permalink: /blog/

background_row:
  - image_path: assets/images/home/home_gallery_icons-01.svg
    alt: "Heart icon with ECG tracing"
    title: "Medicine"
    excerpt: "Medical Scientist Training Program @ University of Michigan Medical School. MD expected May '24."
    
  - image_path: /assets/images/home/home_gallery_icons-02.svg
    alt: "Icon representing variable X1"
    title: "Engineering"
    excerpt: "PhD in AI & Operations Research @ University of Michigan College of Engineering. Defended August '22."
    
  - image_path: /assets/images/home/home_gallery_icons-03.svg
    alt: "Computer icon"
    title: "Health IT"
    excerpt: "Deep experience integrating AI in healthcare; millions of predictions on patients. Ex-Epic engineer."

    
    
research_row:
  - image_path: /assets/images/home/home_gallery_icons-04.svg
    alt: "line chart icon"
    title: "Research"
    excerpt: 'My research is at the intersection of AI & healthcare, with a focus on the interface between clinical workflows and predictive models. I utilize methods from the domains of clinical informatics, machine learning, and operations research. My work spans the healthcare AI lifecycle with projects advancing from model development/evaluation, technical integration, and connection with clinical workflows.'
    url: "/categories/research/"
    btn_label: "More Research"
    btn_class: "btn--primary"
    
projects_row:
  - image_path: /assets/images/home/home_gallery_icons-05.svg
    alt: "network graph icon"
    title: "Projects"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "/categories/#projects/"
    btn_label: "More Projects"
    btn_class: "btn--primary"
    
press_row:
  - image_path: /assets/images/home/home_gallery_icons-06.svg
    alt: "newspaper icon"
    title: "Press"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "/categories/#press"
    btn_label: "See Press"
    btn_class: "btn--primary"
    
    
intro: 
  - excerpt: '*Medicine is a science of uncertainty and an art of probability.* William Osler<br> 
    *All models are wrong, but some are useful.* George Box'
---


{% include feature_row id="hero_row" type="left" %}

{% include feature_row id="background_row" %}

{% include feature_row id="research_row" type="right" %}

{% include feature_row id="projects_row" type="left" %}

{% include feature_row id="press_row" type="right" %}



{% include feature_row id="intro" type="center" %}

---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: exo_home
classes: wide
author_profile: false

#sidebar:
#  nav: "blogsidebar"

# DON'T EDIT PERMALINK - WEIRD PAGINATION ISSUE OTHERWISE
# https://github.com/mmistakes/minimal-mistakes/issues/627#issuecomment-536759630
# permalink: /blog/


hero_row:
  - image_path: /assets/images/exo_headshot_square.png
    alt: "Erkin Otles"
    title: "Hello, World!"
    excerpt: 'My name is Erkin Ötleş & I’m a physician-engineer. This is my website focused on engineering & medicine.
    
    
    I am currently at the University of Michigan, completing my final year of combined MD-PhD training.
    Previously I worked as an engineer at Epic and led a healthcare data science team.
    I am an expert in developing & implementing artificial intelligence tools in healthcare.
    
    
    '
    url: "/about/"
    btn_label: "More About Me"
    btn_class: "btn--primary"

background_row:
  - image_path: assets/images/home/home_gallery_icons-01.svg
    alt: "Heart icon with ECG tracing"
    title: "Medicine"
    excerpt: "Medical Scientist Training Program @ University of Michigan Medical School. MD expected May '24."
    url: /about/#medicine
    
  - image_path: /assets/images/home/home_gallery_icons-02.svg
    alt: "Icon representing variable X1"
    title: "Engineering"
    excerpt: "PhD in AI & Operations Research @ University of Michigan College of Engineering. Defended August '22."
    url: /about/#engineering
    
  - image_path: /assets/images/home/home_gallery_icons-03.svg
    alt: "Computer icon"
    title: "Health IT"
    excerpt: "Deep experience integrating AI in healthcare; millions of predictions on patients. Ex-Epic engineer."
    url: /about/#health-IT


highlights_row:
  - title: "Research"
    excerpt: 'I focus on the interface between clinical workflows & predictive models. I utilize methods from the domains of clinical informatics, machine learning, & operations research.'
    url: "/categories/#research/"
    
  - title: "Projects"
    excerpt: 'My projects range from health system AI implementation to iOS application development.'
    url: "/categories/#projects/"
    
  - title: "Press"
    excerpt: 'my work has been covered in outlets like the Wall Street Journal and Wired.'
    url: "/categories/#press"
    
    
quotes: 
  - excerpt: '*Medicine is a science of uncertainty and an art of probability.* <br> - William Osler - <br> 
    *All models are wrong, but some are useful.* <br> - George Box -'
---


{% include feature_row id="hero_row" type="left" %}

{% include exo_feature_row id="background_row" %}

#container {
  background: #ffffff;
}

<div id="quote_box">
  <div id="content">
    Nice quote.
  </div>
</div>

{% include exo_feature_row id="highlights_row" %}

{% include feature_row id="quotes" type="center" %}

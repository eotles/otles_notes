---
permalink: /
layout: single
author: false

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
    
  - image_path: /assets/images/home/home_gallery_icons-02.svg
    alt: "Icon representing variable X1"
    title: "Engineering"
    excerpt: "PhD in AI & Operations Research @ University of Michigan College of Engineering. Defended August '22."
    
  - image_path: /assets/images/home/home_gallery_icons-03.svg
    alt: "Computer icon"
    title: "Health IT"
    excerpt: "Deep experience integrating AI in healthcare; millions of predictions on patients. Ex-Epic engineer."


intro: 
  - excerpt: '*Medicine is a science of uncertainty and an art of probability.* William Osler<br> 
    *All models are wrong, but some are useful.* George Box'

    
    
research_row:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Research"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
    
news_row:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "News"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---


{% include feature_row id="hero_row" type="left" %}

{% include feature_row id="background_row" %}



{% include feature_row id="intro" type="center" %}

{% include feature_row id="research_row" type="right" %}

{% include feature_row id="news_row" type="left" %}


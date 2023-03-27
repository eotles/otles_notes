---
title: "Hello, World!"
permalink: /
layout: single
author: false

intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'

education_row:
  - image_path: assets/images/empty_550x1.png
    alt: "University of Michigan logo"
    title: "University of Michigan"
    excerpt: "Medical Scientist Training Program (MD/PhD), Industrial & Operations Engineering."
    
  - image_path: /assets/images/empty_550x1.png
    alt: "Jump Around Bucky"
    title: "University of Wisconsin"
    excerpt: "Master of Engineering (M.Eng.), Industrial & Systems Engineering - Decision Science and Operations Research & Computer Science. Bachelor of Science, Industrial & Systems Engineering."
    
  - image_path: /assets/images/empty_550x1.png
    alt: "Jump Around Bucky"
    title: "University of Wisconsin"
    excerpt: "Master of Engineering (M.Eng.), Industrial & Systems Engineering - Decision Science and Operations Research & Computer Science. Bachelor of Science, Industrial & Systems Engineering."

hero_row:
  - image_path: /assets/images/exo_headshot_square.png
    alt: "Erkin Otles"
    title: "Hello, World!"
    excerpt: 'My name is Erkin Ötleş & I’m a physician-engineer (in training). This is my website focused on engineering & medicine. `type="left"`'
    
    
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---


Let's put some text here

{% include feature_row id="hero_row" type="left" %}

{% include feature_row id="intro" type="center" %}

# Education
{% include feature_row id="education_row" %}



{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}


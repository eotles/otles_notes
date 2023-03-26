---
title: "Hello, World!"
permalink: /
layout: splash
author: false

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/dia_stain_glass.png
  caption: "Stained glass at the DIA."
excerpt: "My name is Erkin Ötleş & I'm a physician-engineer (in training). This is my website focused on engineering & medicine."

intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'

education_row:
  - image_path: assets/images/U-M_Logo-PMS.svg
    alt: "University of Michigan logo"
    title: "University of Michigan"
    excerpt: "Medical Scientist Training Program (MD/PhD), Industrial & Operations Engineering."
  - image_path: /assets/images/cropped_jump_around_bucky.png
    alt: "Jump Around Bucky"
    title: "University of Wisconsin"
    excerpt: "Master of Engineering (M.Eng.), Industrial & Systems Engineering - Decision Science and Operations Research & Computer Science. Bachelor of Science, Industrial & Systems Engineering."
    url: "#test-link"

feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
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

<section id="intro">
  <div class="row">
    <div class="container">
      <h2>Hi, I'm Erkin Otles.</h2> 
      <h4>I'm a MD/PhD Student. My research focuses on using machine learning to improve health. I love numbers (and space)!!</h4>

    </div>
  </div>
</section>


<div class="row education">
  <a href="#" id="education"></a>
  <div class="container">
    <h2>Education</h2>
    <hr></hr>

    <div class="col-md-6">
      <h4>University of Michigan<span class="gray"> / 2016 - 2022</span></h4>
      <p>Medical Scientist Training Program (MD/PhD), Industrial and Operations Engineering</p>
    </div>

    <div class="col-md-6">
      <h4>University of Wisconsin - Madison<span class="gray"> / 2015, 2011</span></h4>
      <p>Master of Engineering (M.Eng.), Industrial and Systems Engineering - Decision Science and Operations Research &amp; Computer Science</p>
                <p>Bachelor of Science, Industrial and Systems Engineering</p>
            </div></p>
    </div>

  </div>
</div>


Let's put some text here

{% include feature_row id="intro" type="center" %}

{% include feature_row id="education_row" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}


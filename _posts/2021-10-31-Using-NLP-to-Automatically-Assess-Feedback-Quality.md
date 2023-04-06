---
title: "Using Natural Language Processing to Automatically Assess Feedback Quality: Findings From 3 Surgical Residencies"
categories:
  - Blog
  - Research
tags:
  - Blog
  - Research
  - medicine
  - healthcare
  - artificial intelligence
  - machine learning
  - natural language processing
  - medical education
  - SIMPL
---

Academic Medicine. Can be found [here](https://journals.lww.com/academicmedicine/Fulltext/2021/10000/Using_Natural_Language_Processing_to_Automatically.30.aspx).


<iframe src="{{ site.url }}{{ site.baseurl }}/assets/papers/using_NLP_to_automatically_assess_feedback_quality.pdf" 
    style="aspect-ratio: 8.5 / 11;"
    width="100%" 
>
</iframe>

[Download paper.]({{ site.url }}{{ site.baseurl }}/assets/papers/using_NLP_to_automatically_assess_feedback_quality.pdf)


## Abstract
### Purpose 
Learning is markedly improved with high-quality feedback, yet assuring the quality of feedback is difficult to achieve at scale. Natural language processing (NLP) algorithms may be useful in this context as they can automatically classify large volumes of narrative data. However, it is unknown if NLP models can accurately evaluate surgical trainee feedback. This study evaluated which NLP techniques best classify the quality of surgical trainee formative feedback recorded as part of a workplace assessment.

### Method 
During the 2016–2017 academic year, the SIMPL (Society for Improving Medical Professional Learning) app was used to record operative performance narrative feedback for residents at 3 university-based general surgery residency training programs. Feedback comments were collected for a sample of residents representing all 5 postgraduate year levels and coded for quality. In May 2019, the coded comments were then used to train NLP models to automatically classify the quality of feedback across 4 categories (effective, mediocre, ineffective, or other). Models included support vector machines (SVM), logistic regression, gradient boosted trees, naive Bayes, and random forests. The primary outcome was mean classification accuracy.

### Results 
The authors manually coded the quality of 600 recorded feedback comments. Those data were used to train NLP models to automatically classify the quality of feedback across 4 categories. The NLP model using an SVM algorithm yielded a maximum mean accuracy of 0.64 (standard deviation, 0.01). When the classification task was modified to distinguish only high-quality vs low-quality feedback, maximum mean accuracy was 0.83, again with SVM.

### Conclusions 
To the authors’ knowledge, this is the first study to examine the use of NLP for classifying feedback quality. SVM NLP models demonstrated the ability to automatically classify the quality of surgical trainee evaluations. Larger training datasets would likely further increase accuracy.

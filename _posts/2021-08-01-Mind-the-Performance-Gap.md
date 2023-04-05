---
title: "Mind the Performance Gap: Dataset Shift During Prospective Validation"
categories:
  - Blog
  - Research
tags:
  - Blog
  - Research
  - machine learning
  - artificial intelligence
  - healthcare
  - medicine
  - electronic health record
---

Our 2021 Machine Learning for Healthcare Conference paper! It discusses a special kind of dataset shift that is particularly pervasive and pernicious when developing and implementing ML/AI models for use in healthcare. Here's a link to the [Mind the Performance Gap paper](https://proceedings.mlr.press/v149/otles21a/otles21a.pdf) that I authored with Jeeheh Oh, Benjamin Li, Michelle Bochinski, Hyeon Joo, Justin Ortwine, Erica Shenoy, Laraine Washer, Vincent B. Young, Krishna Rao, and Jenna Wiens.


<iframe src="{{ site.url }}{{ site.baseurl }}/assets/papers/mind_the_performance_gap.pdf" 
    style="aspect-ratio: 8.5 / 11;"
    width="100%" 
>
</iframe>

## Abstract
Once integrated into clinical care, patient risk stratification models may perform worse com- pared to their retrospective performance. To date, it is widely accepted that performance will degrade over time due to changes in care processes and patient populations. However, the extent to which this occurs is poorly understood, in part because few researchers re- port prospective validation performance. In this study, we compare the 2020-2021 (’20-’21) prospective performance of a patient risk stratification model for predicting healthcare- associated infections to a 2019-2020 (’19-’20) retrospective validation of the same model. We define the difference in retrospective and prospective performance as the performance gap. We estimate how i) “temporal shift”, i.e., changes in clinical workflows and patient populations, and ii) “infrastructure shift”, i.e., changes in access, extraction and transfor- mation of data, both contribute to the performance gap. Applied prospectively to 26,864 hospital encounters during a twelve-month period from July 2020 to June 2021, the model achieved an area under the receiver operating characteristic curve (AUROC) of 0.767 (95% confidence interval (CI): 0.737, 0.801) and a Brier score of 0.189 (95% CI: 0.186, 0.191). Prospective performance decreased slightly compared to ’19-’20 retrospective performance, in which the model achieved an AUROC of 0.778 (95% CI: 0.744, 0.815) and a Brier score of 0.163 (95% CI: 0.161, 0.165). The resulting performance gap was primarily due to in- frastructure shift and not temporal shift. So long as we continue to develop and validate models using data stored in large research data warehouses, we must consider differences in how and when data are accessed, measure how these differences may negatively affect prospective performance, and work to mitigate those differences.

---
title: "Dynamic prediction of work status for workers with occupational injuries: assessing the value of longitudinal observations"
categories:
  - Blog
  - Research
tags:
  - Blog
  - Research
  - occupational health
  - return to work
  - medicine
  - healthcare
  - artificial intelligence
  - machine learning
---

Journal of the American Medical Informatics Association manuscript, can be found [here](https://doi.org/10.1093/jamia/ocac130).

<img src="{{ site.url }}{{ site.baseurl }}/assets/post_assets/2022-JAMIA-RTW/JAMIA_RTW_Ötleş_2022_graphical_abstract.png" alt="Graphical abstract for JAMIA return to work manuscript." >

<iframe width="560" height="315" src="https://www.youtube.com/embed/k8762xJbi8g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


<iframe src="{{ site.url }}{{ site.baseurl }}/assets/papers/dynamic_prediction_of_work_status_for_workers_with_occupational_injuries.pdf" 
    style="aspect-ratio: 8.5 / 11;"
    width="100%" 
>
</iframe>

[Download abstract.]({{ site.url }}{{ site.baseurl }}/assets/papers/dynamic_prediction_of_work_status_for_workers_with_occupational_injuries.pdf)

## Abstract
### Objective
Occupational injuries (OIs) cause an immense burden on the US population. Prediction models help focus resources on those at greatest risk of a delayed return to work (RTW). RTW depends on factors that develop over time; however, existing methods only utilize information collected at the time of injury. We investigate the performance benefits of dynamically estimating RTW, using longitudinal observations of diagnoses and treatments collected beyond the time of initial injury.

### Materials and Methods
We characterize the difference in predictive performance between an approach that uses information collected at the time of initial injury (baseline model) and a proposed approach that uses longitudinal information collected over the course of the patient’s recovery period (proposed model). To control the comparison, both models use the same deep learning architecture and differ only in the information used. We utilize a large longitudinal observation dataset of OI claims and compare the performance of the two approaches in terms of daily prediction of future work state (working vs not working). The performance of these two approaches was assessed in terms of the area under the receiver operator characteristic curve (AUROC) and expected calibration error (ECE).

### Results
After subsampling and applying inclusion criteria, our final dataset covered 294 103 OIs, which were split evenly between train, development, and test datasets (1/3, 1/3, 1/3). In terms of discriminative performance on the test dataset, the proposed model had an AUROC of 0.728 (90% confidence interval: 0.723, 0.734) versus the baseline’s 0.591 (0.585, 0.598). The proposed model had an ECE of 0.004 (0.003, 0.005) versus the baseline’s 0.016 (0.009, 0.018).

### Conclusion
The longitudinal approach outperforms current practice and shows potential for leveraging observational data to dynamically update predictions of RTW in the setting of OI. This approach may enable physicians and workers’ compensation programs to manage large populations of injured workers more effectively.

---
title: "Early identification of patients admitted to hospital for covid-19 at risk of clinical deterioration: model development and multisite external validation study"
categories:
  - Blog
  - Research
tags:
  - Blog
  - Research
  - covid
  - deterioration index
  - early warning system
  - medicine
  - healthcare
  - artificial intelligence
  - machine learning
---

British Medical Journal. Can be found [here](https://doi.org/10.1136/bmj-2021-068576).


<iframe src="{{ site.url }}{{ site.baseurl }}/assets/papers/early_identification_of_covid_inpatients_at_risk_of_clinical_deterioration.pdf" 
    style="aspect-ratio: 8.5 / 11;"
    width="100%" 
>
</iframe>

[Download paper.]({{ site.url }}{{ site.baseurl }}/assets/papers/early_identification_of_covid_inpatients_at_risk_of_clinical_deterioration.pdf)

## Key Points
### Question
How accurately does the Epic Sepsis Model, a proprietary sepsis prediction model implemented at hundreds of US hospitals, predict the onset of sepsis?

### Findings
In this cohort study of 27 697 patients undergoing 38 455 hospitalizations, sepsis occurred in 7% of the hosptalizations. The Epic Sepsis Model predicted the onset of sepsis with an area under the curve of 0.63, which is substantially worse than the performance reported by its developer.

### Meaning
This study suggests that the Epic Sepsis Model poorly predicts sepsis; its widespread adoption despite poor performance raises fundamental concerns about sepsis management on a national level.

## Abstract
### Importance
The Epic Sepsis Model (ESM), a proprietary sepsis prediction model, is implemented at hundreds of US hospitals. The ESM’s ability to identify patients with sepsis has not been adequately evaluated despite widespread use.

### Objective
To externally validate the ESM in the prediction of sepsis and evaluate its potential clinical value compared with usual care.

### Design, Setting, and Participants
This retrospective cohort study was conducted among 27 697 patients aged 18 years or older admitted to Michigan Medicine, the academic health system of the University of Michigan, Ann Arbor, with 38 455 hospitalizations between December 6, 2018, and October 20, 2019.

### Exposure
The ESM score, calculated every 15 minutes.

### Main Outcomes and Measures
Sepsis, as defined by a composite of (1) the Centers for Disease Control and Prevention surveillance criteria and (2) International Statistical Classification of Diseases and Related Health Problems, Tenth Revision diagnostic codes accompanied by 2 systemic inflammatory response syndrome criteria and 1 organ dysfunction criterion within 6 hours of one another. Model discrimination was assessed using the area under the receiver operating characteristic curve at the hospitalization level and with prediction horizons of 4, 8, 12, and 24 hours. Model calibration was evaluated with calibration plots. The potential clinical benefit associated with the ESM was assessed by evaluating the added benefit of the ESM score compared with contemporary clinical practice (based on timely administration of antibiotics). Alert fatigue was evaluated by comparing the clinical value of different alerting strategies.

### Results
We identified 27 697 patients who had 38 455 hospitalizations (21 904 women [57%]; median age, 56 years [interquartile range, 35-69 years]) meeting inclusion criteria, of whom sepsis occurred in 2552 (7%). The ESM had a hospitalization-level area under the receiver operating characteristic curve of 0.63 (95% CI, 0.62-0.64). The ESM identified 183 of 2552 patients with sepsis (7%) who did not receive timely administration of antibiotics, highlighting the low sensitivity of the ESM in comparison with contemporary clinical practice. The ESM also did not identify 1709 patients with sepsis (67%) despite generating alerts for an ESM score of 6 or higher for 6971 of all 38 455 hospitalized patients (18%), thus creating a large burden of alert fatigue.

### Conclusions and Relevance
This external validation cohort study suggests that the ESM has poor discrimination and calibration in predicting the onset of sepsis. The widespread adoption of the ESM despite its poor performance raises fundamental concerns about sepsis management on a national level.

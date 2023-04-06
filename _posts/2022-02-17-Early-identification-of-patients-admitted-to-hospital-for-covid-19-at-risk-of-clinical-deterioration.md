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

## Abstract
### Objective
To create and validate a simple and transferable machine learning model from electronic health record data to accurately predict clinical deterioration in patients with covid-19 across institutions, through use of a novel paradigm for model development and code sharing.

### Design
Retrospective cohort study.

### Setting
One US hospital during 2015-21 was used for model training and internal validation. External validation was conducted on patients admitted to hospital with covid-19 at 12 other US medical centers during 2020-21.

### Participants
33,119 adults (≥18 years) admitted to hospital with respiratory distress or covid-19.

### Main outcome measures
An ensemble of linear models was trained on the development cohort to predict a composite outcome of clinical deterioration within the first five days of hospital admission, defined as in-hospital mortality or any of three treatments indicating severe illness: mechanical ventilation, heated high flow nasal cannula, or intravenous vasopressors. The model was based on nine clinical and personal characteristic variables selected from 2686 variables available in the electronic health record. Internal and external validation performance was measured using the area under the receiver operating characteristic curve (AUROC) and the expected calibration error—the difference between predicted risk and actual risk. Potential bed day savings were estimated by calculating how many bed days hospitals could save per patient if low risk patients identified by the model were discharged early.

### Results
9291 covid-19 related hospital admissions at 13 medical centers were used for model validation, of which 1510 (16.3%) were related to the primary outcome. When the model was applied to the internal validation cohort, it achieved an AUROC of 0.80 (95% confidence interval 0.77 to 0.84) and an expected calibration error of 0.01 (95% confidence interval 0.00 to 0.02). Performance was consistent when validated in the 12 external medical centers (AUROC range 0.77-0.84), across subgroups of sex, age, race, and ethnicity (AUROC range 0.78-0.84), and across quarters (AUROC range 0.73-0.83). Using the model to triage low risk patients could potentially save up to 7.8 bed days per patient resulting from early discharge.

### Conclusion
A model to predict clinical deterioration was developed rapidly in response to the covid-19 pandemic at a single hospital, was applied externally without the sharing of data, and performed well across multiple medical centers, patient subgroups, and time periods, showing its potential as a tool for use in optimizing healthcare resources.

---
title: "Predicting Emergency Department Patient Throughput Times Utilizing Machine Learning"
categories:
  - Blog
  - Research
tags:
  - Blog
  - Research
  - emergency medicine
  - medicine
  - healthcare
  - health system engineering
  - artificial intelligence
  - machine learning
  - operations research
---

Annals of Emergency Medicine research forum abstract. Work done in conjunction with Drs. Brian Patterson and Laura Albert. [Link to paper.](https://doi.org/10.1016/j.annemergmed.2015.07.310)


<iframe src="{{ site.url }}{{ site.baseurl }}/assets/papers/predicting_emergency_department_patient_throughput.pdf" 
    style="aspect-ratio: 8.5 / 11;"
    width="100%" 
>
</iframe>

## Abstract
### Study Objectives
Patient throughput time in the emergency department is a critical metric affecting patient satisfaction and service efficiency. We performed a retrospective analysis of electronic medical record (EMR) derived data to evaluate the effectiveness of multiple modeling techniques in predicting throughput times for patient encounters in an academic emergency department (ED). Analysis was conducted using various modeling techniques and on differing amounts of information about each patient encounter. We hypothesized that more comprehensive and inclusive models would provide greater predictive power.
### Methods
Retrospective medical record review was performed on consecutive patients at a single, academic, university-based ED. Data were extracted from an EMR derived dataset. All patients who presented from January 1, 2011 to December 31, 2013 and met inclusion criteria were included in the analysis. The data were then partitioned into two sets: one for developing models (training) and a second for analyzing the predictive power of these models (testing). The Table lists model types used. The primary outcome measured was the ability of the trained models to accurately predict the throughput times of test data, measured in terms of mean absolute error (MAE). Secondary outcomes were R2 and mean squared error (MSE). Model factors included a mix of patient specific factors such as triage vital signs, age, chief complaint; factors representing the state of the ED such as census and running average throughput time; and timing factors such as time of day, day of week, and month. The most comprehensive models included a total of 29 distinct factors.
### Results
Of the 134,194 patients that were seen in the 3-year period of the study 128,252 met the inclusion criteria; the mean throughput time was 183.327 min (SD 1⁄4 98.447 min). Compared to using a single average throughput time as a naïve model (MAE 1⁄4 80.801 min), univariate models provided improved predictive abilities. More sophisticated models, using machine learning methods and including all available factors provided greater predictive power with the lowest MAE achieved at 73.184 min.
### Conclusion
We have demonstrated that including information about incoming patients and the state of the ED at the time of an arrival can aid in the prediction of individual patients’ throughput times. The Multiple Linear Regression model, including all available factors, had the highest predictive accuracy, reducing mean absolute error by over 9% compared to the naïve model. While this represents an improvement in the current state of the art, we believe there is room for further work to generate high quality individual patient predictions. More sophisticated models based on ED workflows may lead to greater predictive power to prospectively estimate patient throughput times at arrival.

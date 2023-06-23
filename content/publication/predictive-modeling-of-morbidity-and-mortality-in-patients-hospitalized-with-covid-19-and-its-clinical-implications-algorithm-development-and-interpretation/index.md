---
title: "Predictive modeling of morbidity and mortality in patients hospitalized
  with COVID-19 and its clinical implications: algorithm development and
  interpretation"
publication_types:
  - "2"
authors:
  - admin
  - Wenke Liu
  - Xiaoshan Chen
  - Michael P McRae
  - John T McDevitt
  - David Fenyö
doi: 10.2196/29514
abstract: ""
draft: false
featured: true
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-07-09T00:00:00Z
---
Background: The COVID-19 pandemic began in early 2021 and placed significant strains on health care systems worldwide. There remains a compelling need to analyze factors that are predictive for patients at elevated risk of morbidity and mortality.

Objective: The goal of this retrospective study of patients who tested positive with COVID-19 and were treated at NYU (New York University) Langone Health was to identify clinical markers predictive of disease severity in order to assist in clinical decision triage and to provide additional biological insights into disease progression.

Methods: The clinical activity of 3740 patients at NYU Langone Hospital was obtained between January and August 2020; patient data were deidentified. Models were trained on clinical data during different parts of their hospital stay to predict three clinical outcomes: deceased, ventilated, or admitted to the intensive care unit (ICU).

Results: The XGBoost (eXtreme Gradient Boosting) model that was trained on clinical data from the final 24 hours excelled at predicting mortality (area under the curve \[AUC]=0.92; specificity=86%; and sensitivity=85%). Respiration rate was the most important feature, followed by SpO2 (peripheral oxygen saturation) and being aged 75 years and over. Performance of this model to predict the deceased outcome extended 5 days prior, with AUC=0.81, specificity=70%, and sensitivity=75%. When only using clinical data from the first 24 hours, AUCs of 0.79, 0.80, and 0.77 were obtained for deceased, ventilated, or ICU-admitted outcomes, respectively. Although respiration rate and SpO2 levels offered the highest feature importance, other canonical markers, including diabetic history, age, and temperature, offered minimal gain. When lab values were incorporated, prediction of mortality benefited the most from blood urea nitrogen and lactate dehydrogenase (LDH). Features that were predictive of morbidity included LDH, calcium, glucose, and C-reactive protein.

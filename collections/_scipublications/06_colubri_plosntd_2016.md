---
layout: page
title: "Transforming clinical data into actionable Ebola prognosis models"
journal: PLOS Neglected Tropical Diseases
info: Published March 18, 2016
doi: 10.1371/journal.pntd.0004549
authors: Colubri A, Silver T, Fradet T, Retzepi K, Fry BW, Sabeti PC
permalink: /scipublications/colubri_plosntd_2016
---

**Background:** Assessment of the response to the 2014–15 Ebola outbreak indicates the need for innovations in data collection, sharing, and use to improve case detection and treatment. Here we introduce a Machine Learning pipeline for Ebola Virus Disease (EVD) prognosis prediction, which packages the best models into a mobile app to be available in clinical care settings. The pipeline was trained on a public EVD clinical dataset, from 106 patients in Sierra Leone.

**Methods/Principal Findings:** We used a new tool for exploratory analysis, Mirador, to identify the most informative clinical factors that correlate with EVD outcome. The small sample size and high prevalence of missing records were significant challenges. We applied multiple imputation and bootstrap sampling to address missing data and quantify overfitting. We trained several predictors over all combinations of covariates, which resulted in an ensemble of predictors, with and without viral load information, with an area under the receiver operator characteristic curve of 0.8 or more, after correcting for optimistic bias. We ranked the predictors by their F1-score, and those above a set threshold were compiled into a mobile app, Ebola CARE (Computational Assignment of Risk Estimates).

**Conclusions/Significance:** This method demonstrates how to address small sample sizes and missing data, while creating predictive models that can be readily deployed to assist treatment in future outbreaks of EVD and other infectious diseases. By generating an ensemble of predictors instead of relying on a single model, we are able to handle situations where patient data is partially available. The prognosis app can be updated as new data become available, and we made all the computational protocols fully documented and open-sourced to encourage timely data sharing, independent validation, and development of better prediction models in outbreak response.

DOI: [10.1371/journal.pntd.0004549](https://doi.org/10.1371/journal.pntd.0004549){:target="_blank"}
---
title: 2.Explainable AI in biological age estimation 
summary: Applying SHAP (SHapley Additive exPlanations) method to identify factors influencing biological age using wearable data
tags:
  - SHAP (SHapley Additive exPlanations) method 
  - Explainable AI method
  - Interpretability
  - XGBoost model
  - Wearable
  - Accelerometery
  - Physical activity
  - Sleep
  - Energy expenditure
  - Circadian rhythm
date: '2024-05-03'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by AdobeStock
  focal_point: Smart

#links:
  #- icon: twitter
    #icon_pack: fab
    #name: Follow
    #url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

# Publications
* XGBAge: Prediction and Identification of Factors Influencing Biological Age Using Wearable Accelerometer Data, *IEEE EMBC 2024 (Upcoming)*

Current biological age models depend on unstructured inputs and employ opaque AI/ML models, which obscures the rationale behind specific predictions for certain individuals. This lack of clarity complicates the process of pinpointing triggers for potential interventions and designing them effectively. This becomes particularly compelling in the realm of digital biomarker data related to longevity, where intervention studies still lack compelling evidence regarding their efficacy. Employing explainable AI methods would serve a pivotal role in uncovering these risk factors, thereby contributing to the development of more efficient interventions aimed at promoting longevity. 

To this end, and with a focus of enabling interpretability, we developed an ML model for biological age prediction utilizing structured and specifically crafted features from 7-day, 24-hour accelerometer data of 73,000 adults in the UK Biobank. 
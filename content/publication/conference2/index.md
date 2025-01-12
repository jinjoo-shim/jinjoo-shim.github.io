---
title: 'XGBAge: Prediction and Identification of Factors Influencing Biological Age Using Wearable Accelerometer Data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Elgar Fleisch
  - Filipe Barata

# Author notes (optional)
author_notes:
  #- 'Equal contribution'
  #- 'Equal contribution'

date: '2024-12-17'
doi: 'http://doi.org/10.1109/EMBC53108.2024.10781878'

# Schedule page publish date (NOT publication's date).
#publishDate: '2023-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference-journal']

# Publication name and optional abbreviated publication name.
publication: In *2024 46th Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC)*
#publication_short: In *Scientific Reports*

abstract: Biological age (BA) reflects an individual’s biological state, serving as a precise indicator of mortality and age-related outcomes. Recent studies have leveraged wearable accelerometer data coupled with artificial intelligence (AI) and machine learning (ML) to predict BA. However, existing predictive models face challenges as they depend on unstructured inputs and opaque models, which obscures the rationale behind specific predictions and identifying risk factors for interventions. To address this, and with a focus of enabling interpretability, we developed an ML model for BA prediction utilizing structured and specifically crafted features from 7-day, 24-hour accelerometer data of 73,000 adults in the UK Biobank aged 40-70 years. Our XGBoost model is parsimonious and simple with 21 parameters and exhibits robust predictive performance (MAE<5years). Utilizing the SHAP method, we identified the key determinants of BA predictions, emphasizing the pivotal role of timing of activities alongside physical activity levels in understanding biological aging. Case studies showcased the model’s interpretability and personalized interventions aimed at mitigating advanced aging. This study explores an interpretable AI application for BA estimation. With digitization potential through the scalability of wearables and smartwatches, it opens avenues for promoting healthy aging at a population level.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: 
- digital biomarker
- digital age
- biological age
- wearables
- machine learning
- explainable AI
- interpretable ML
- SHAP 
- XGBoost
- NHANES
- UK Biobank

# Display this page in the Featured widget?
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Jinjoo Shim'
  focal_point: ""
  preview_only: false


---
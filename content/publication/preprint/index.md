---
title: "Predicting Time Series with Adjusting Feature Weight: An Integrated Method Based on Large Language Models and SHAP"
authors:
- admin
- Corey Kewei XU
date: "2024-10-18T00:00:00Z"
doi: "https://doi.org/10.1109/MLNLP63328.2024.10800570"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: Conference Paper

# Publication name and optional abbreviated publication name.
publication: In *2024 7th International Conference on Machine Learning and Natural Language Processing (MLNLP)*
publication_short: In *MLNLP 2024*

abstract: Social computing, an emerging interdisciplinary field, is centered on understanding and predicting human social behaviors and their patterns. Despite the important role of time series prediction in social computing, existing model-driven approaches often ignore the significant impact that data feature weights can have on time series prediction tasks. This limitation leads to many predictive models performing well on standard test data but failing to achieve the expected accuracy on real-world social computing data. Recent studies have shown that Large Language Models (LLMs) possess strong pattern recognition and reasoning capabilities for sequences. However, effectively applying their amazing text reasoning abilities to social computing and time series forecasting remains challenging. To solve these two significant research gaps, this study proposes an innovative time series forecasting model based on LLMs and SHAP. This model is an adaptive multimodal supervised learning framework that can both combine time series data with token embedding data and dynamically adjust feature weights after a few training iterations to recognize the feature patterns hidden behind real-world data. By the proposed model structure, this model can focus on features with the greatest influence on the prediction results, hence improving prediction performance with stability and promoting LLMs' application in time series prediction related to social computing. Besides conventional performance testing, this study also proposes an evaluation indicator for measuring the feature weight adjustment effect of time series models. This effectively enriches model evaluation dimensions and allows for diversified evaluation of time series models.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Large Language Models

featured: true

#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: 
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---



---
title: "A New Paradigm for Medium-Range Severe Weather Forecasts: Probabilistic Random Forest–Based Predictions"
authors:
- admin
- Russ S. Schumacher
- Israel L. Jirak
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2023-02-02T00:00:00Z"
doi: "https://doi.org/10.1175/WAF-D-22-0143.1"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Weather and Forecasting, 38, 251-272"
#publication_short: "WAF"

#abstract: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Machine Learning
featured: false

# links:
# - name: ""
#url: 'https://journals.ametsoc.org/view/journals/wefo/38/2/WAF-D-22-0143.1.xml'
#url_pdf: https://journals.ametsoc.org/view/journals/wefo/38/2/WAF-D-22-0143.1.xml
#url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
## Abstract
Historical observations of severe weather and simulated severe weather environments (i.e., features) from the Global Ensemble Forecast System v12 (GEFSv12) Reforecast Dataset (GEFS/R) are used in conjunction to train and test random forest (RF) machine learning (ML) models to probabilistically forecast severe weather out to days 4–8. RFs are trained with ∼9 years of the GEFS/R and severe weather reports to establish statistical relationships. Feature engineering is briefly explored to examine alternative methods for gathering features around observed events, including simplifying features using spatial averaging and increasing the GEFS/R ensemble size with time lagging. Validated RF models are tested with ∼1.5 years of real-time forecast output from the operational GEFSv12 ensemble and are evaluated alongside expert human-generated outlooks from the Storm Prediction Center (SPC). Both RF-based forecasts and SPC outlooks are skillful with respect to climatology at days 4 and 5 with diminishing skill thereafter. The RF-based forecasts exhibit tendencies to slightly underforecast severe weather events, but they tend to be well-calibrated at lower probability thresholds. Spatially averaging predictors during RF training allows for prior-day thermodynamic and kinematic environments to generate skillful forecasts, while time lagging acts to expand the forecast areas, increasing resolution but decreasing overall skill. The results highlight the utility of ML-generated products to aid SPC forecast operations into the medium range.

## Significance Statement
Medium-range severe weather forecasts generated from statistical models are explored here alongside operational forecasts from the Storm Prediction Center (SPC). Human forecasters at the SPC rely on traditional numerical weather prediction model output to make medium-range outlooks and statistical products that mimic operational forecasts can be used as guidance tools for forecasters. The statistical models relate simulated severe weather environments from a global weather model to historical records of severe weather and perform noticeably better than human-generated outlooks at shorter lead times (e.g., day 4 and 5) and are capable of capturing the general location of severe weather events 8 days in advance. The results highlight the value in these data-driven methods in supporting operational forecasting.
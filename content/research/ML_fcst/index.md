---
title: Machine Learning for Forecasting
summary: Coming Soon!
tags:
  - ML_fcst
date: '2023-08-18T00:00:00Z'

# Optional external URL for project (replaces project detail page).
# external_link: ''

image:
  caption: Machine learning-based day 2 forecasts of excessive rainfall associated with Hurricane Ida with overlapping observations
  focal_point: Smart

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/draaronhill
#url_code: ''
#url_pdf: ''
#url_slides: ''
#url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Postprocessing numerical weather prediction (NWP) model output to improve point-based and localized forecasts has been a topic of research for over 50 years (e.g., MOS). Statistical models are used to deduce relationships between pre-defined predictors and the phenomena of interest. Machine learning (ML) has emerged within atmospheric science as a new method to postprocess large NWP datasets to explicitly predict events that are unresolvable by NWP model output (e.g., extreme precipitation, tornadoes). One benefit of ML models is they are capable at learning the underlying spatio-temporal biases in NWP model output, thereby "correcting" biases in ML-based forecasts. I am interested in applying ML and deep learning (DL) techniques with global convection-parameterizing and convection-allowing models to create probablistic hazard outlooks (e.g., <a href="http://journals.ametsoc.org/doi/pdf/10.1175/MWR-D-19-0344.1"><b>Hill et al. 2020a</b></a>, <a href="https://doi.org/10.1175/WAF-D-21-0026.1"><b>Hill and Schumacher 2021</b></a>, <a href="https://doi.org/10.1175/BAMS-D-20-0186.1"><b>Schumacher et al. 2021</b></a>, <a href="https://doi.org/10.1175/WAF-D-22-0143.1"><b>Hill et al. 2023</b></a>) that are beneficial to operational forecast centers (e.g., Storm Prediction Center, Weather Prediction Center). This work is being supported by two grants from the National Oceanic and Atmospheric Administration Joint Technology Transfer Initiative program.
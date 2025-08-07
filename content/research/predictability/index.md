---
title: Forecast Sensitivity and Predictability
summary: Improving forecasts of convection through understanding how forecasts are sensitive to small-scale changes in the environment
tags:
  - predictability
date: '2023-08-18T00:00:00Z'

# Optional external URL for project (replaces project detail page).
# external_link: ''

#image:
#  caption: Machine learning-based day 2 forecasts of excessive rainfall associated with Hurricane Ida with overlapping observations
#  focal_point: Smart

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
Understanding the evolution of errors during the forecast process is crucial to understanding how to reduce analysis errors and mitigate hazardous weather impacts. Traditional techniques to map initial condition uncertainties and perturbations to forecast variables is rooted in the tangent linear model, which translates initial perturbations through a differentiable forecast model to a later forecast time. Adjoint sensitivity has traditionally been used to estimate how perturbations at an initial-time may propagate onto a forecast variable, describing dynamically-consistent sensitivity regions at large scales. In the late 2000s, ensemble sensitivity was proposed that maps the dynamically sensitive regions (I.e., adjoint sensitivity) to initial conditions uncertainties from and ensemble of numerical weather prediction solutions, thereby relating fast error growth to areas that are most uncertain. Ensemble sensitivity can be employed to any initial condition-perturbed ensemble prediction system to estimate how initial uncertainties may evolve onto a chosen forecast metric, e.g., tropical cyclone position, intensity of severe convection, or areal rainfall. 

Data assimilation procedures, which combine first-guess four-dimensional snap shots of the atmosphere with observations, have evolved significantly over the last two decades to improve forecasts at all scales of motion. Dr. Hill is particularly interested in the ensemble Kalman filter (EnKF), which has a broad application at convective scales, and methodological parameters that control inflation, localization, and ensemble spread, which help to create reliable ensemble forecasts. At smaller scales, observations of atmospheric prcesses become critical for convection-allowing model forecasts when convective processes are explicitly simulated. However, the selection of additional observations to improve forecasts is often subjective, even though objective methods exist to select observations in dynamically relevant regions. Ensemble sensitivity analysis provides a framework to determine additional observing locations that dynamically relate earlier state variables (e.g., 2-m temperature) and a particular forecast metric (e.g., reflectivity) to reduce forecast uncertainty after the new observation is assimilated. Dr. Hill has examined sensitivity-based targeting at convection-allowing resolutions in idealized simulations (e.g., Hill et al. 2020b) and continues to explore its utility for real-data cases and storm-scale applications. 

More broadly, the predictability of severe convective storms and their hazards are a function of the initial conditions and chosen model architecture. As a result, there is an inherent, practical limit to predictability beyond a certain threshold (usually determined ~2 weeks) after which the chaotic nature of the atmosphere saturates all error sources and predictability is lost. However, we are increasingly learning that the application of AI in this space has vast potential to both improve our understanding of atmospheric hazards and potentially increase our practice predictability limits. The CHAOS group is increasingly using machine learning and other AI tools to increase the practical prediction and predictability of severe weather hazards, including concurrent/compounding hazards. 

<h3>Current Projects:</h3>
<ul>
<li>Collaborative Research: What drives the most extreme rainstorms in the contiguous
US?. Support: <b><u>National Science Foundation</u></b>.</li>

<li>Collaborative Research: Mesoscale Predictability Across Climate Regimes.
Support: <b><u>National Science Foundation</u></b>.</li>

<li>Predicting Co-occurring Tornado and Flash Flood Events. Support: <b><u>University of Oklahoma</u></b>.</li>
</ul>
<h3>Past Projects:</h3>
Medium-range excessive rainfall forecasts with machine learning models. Support: <b><u>National Oceanic and Atmospheric Administration Joint Technology Transfer Initiative</u></b>.

Generating calibrated forecast guidance for severe weather beyond day 1. Support: <b><u>National Oceanic and Atmospheric Administration Joint Technology Transfer Initiative</u></b>.

<h3>Papers:</h3>
<ul>
<li><a href=/publication/osses>Factors influencing ensemble sensitivity-based targeted observing prediction at convection-allowing resolutions</a></li>
<<li><a href=/publication/vse_portable/> Influence of a portable near-surface observing network on experimental ensemble forecasts of deep convection hazards during VORTEX-SE</a></li>
<li><a href=/publication/esa_dryline/>Ensemble sensitivity analysis for mesoscale forecasts of dryline convection initiation</a></li>



</ul>

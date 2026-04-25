# Data 555 Capstone Project
Dashboard created using 2026 Captone project by Chris Annunziato and Robert Lyles.
##Project Overview
The goal of this research is to study estimation of population-averaged (PA) log odds ratios when data are generated from a probit random-effects model, and to compare competing estimation strategies:
1.	Kernel Density Estimation (KDE)–based weighted averaging (proposed method)
2.	Generalized Estimating Equations (GEE) with logit link
3.	Stratified GEE approaches
4.	Mixed model–based estimators
5.	Bootstrap inference for PA parameters
## Data Description
This study uses fully simulated data generated via a clustered probit random intercept model with 200 clusters and 4 observations per cluster. Exposure distributions differ by sex group and follow normal distributions with different means. A total of 500 Monte Carlo datasets were generated to evaluate estimator performance. The study population is entirely synthetic and does not correspond to a real world dataset. All data were generated programmatically in SAS.
## Real World Impact
This project demonstrates how population-averaged effect estimates can vary depending on model specification and subgroup structure. 
These findings are relevant for improving the accuracy of causal interpretation in clustered or heterogeneous data settings.

## Link to Dashboard
https://github.com/cannun2/capstone_dashboard

## How to Run
Download the file and open the Capstone.Rmd file. Hit knit to create the dashboard.
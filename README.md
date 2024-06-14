# Transmission potential of mpox in Mainland China, June-July 2023

Code and data for Akhmetzhanov AR, Wu PH 2023 "Transmission potential of mpox in Mainland China, June-July 2023: estimating reproduction number during the initial phase of the epidemic" *medRxiv* 2023.09.23.23296017 ([doi:10.1101/2023.09.23.23296017](https://doi.org/10.1101/2023.09.23.23296017))

## I. Abstract
Despite reporting very few mpox cases early in 2023, Mainland China observed a surge with over 500 cases during the summer. Amid ambiguous prevention strategies and stigma surrounding mpox, the epidemic escalated silently. This study aims to quantify the epidemic scale and assess the transmission dynamics by estimating the effective reproduction number (R_e) during its early phase. Publicly available data were aggregated to retrieve daily mpox incidences in Mainland China, and the R_e value was. estimated using an exponential growth model. The mean R_e value was found to be 1.76 (95% credible interval: 1.51-2.06), suggesting a case doubling time of approximately two weeks. This estimate was compared with R_e values from 16 other national outbreaks in 2022 selected based on a cumulative incidence exceeding 700 symptomatic cases by the end of that year. The R_e estimates for these outbreaks ranged from 1.17 for Portugal to 2.88 for Colombia. The pooled mean was 1.66 (1.40-1.92), aligning closely with the R_e for Mainland China. These findings underscore the need for immediate and effective control measures, including targeted vaccination campaigns, to mitigate further spread and impact.

## II. Code scripts
* [A. Main analysis for Mpox in China.ipynb](https://nbviewer.org/github/aakhmetz/Mpox-in-MainlandChina-2023/blob/main/scripts/A.%20Main%20analysis%20for%20Mpox%20in%20China.ipynb)
* [B1. Sensitivity analysis - varied time windows for China.ipynb](https://nbviewer.org/github/aakhmetz/Mpox-in-MainlandChina-2023/blob/main/scripts/B1.%20Sensitivity%20analysis%20-%20varied%20time%20windows%20for%20China.ipynb)
* [B2. Sensitivity analysis - latest update.ipynb](https://nbviewer.org/github/aakhmetz/Mpox-in-MainlandChina-2023/blob/main/scripts/B2.%20Sensitivity%20analysis%20-%20latest%20update.ipynb)

## III. Output

Estimates of the effective reproduction number during the initial phases of the outbreaks
<img width="1159" alt="Screenshot 2024-01-08 at 8 56 12 PM" src="https://github.com/aakhmetz/Mpox-in-MainlandChina-2023/assets/2173206/8729579f-d34d-49e1-9419-a06f8ff9ef7a">


## Additional details
* The folder **data** contains all data used for our analysis.
* The folder **data sources** contains two screenshots of the WHO data that was then digitized

---------
**Thank you for your interest to our work!** 

Few words of caution: We would like to note that our code is not supposed to work out of box, because the links used in the notebooks were user-specific as well as the password for our computation cluster was hidden. Our main intent was to show the relevance of the methods used in our paper.

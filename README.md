## Time Series Analysis of Nutrient Concentration in Chesapeake Bay

### Repository Contents
    chesapeake_bay_nutrient_pollution
    └───images
        │   STL visualization for nitrogen: nitrogen.png
        │   STL visualization for phosphorus: phosphorus.png
    │   README.md
    │   .Rmd
    │   .Rproj

### Context

This project was completed as a final project for my Statistics class, taken as part of my Master's program at UC Santa Barbara. I worked independently to find data, pose a statistical question, and carry out analysis using appropriate modeling techniques.

### Question

Since the 2010 introduction of federal water quality requirements, what seasonal and non-seasonal trends are present for nitrogen and phosphorus concentrations in Chesapeake Bay tidal regions?

### Analysis Summary

Constructed two Seasonal-Trend using LOESS (STL) decomposition models to conduct 2010-2019 time series analysis of nutrient concentrations in the Chesapeake Bay. Used 43,809 nitrogen samples and 43,590 phosphorus samples from 143 monitoring stations positioned throughout the Bay's tidal regions. Selecting seasonality for the model based on autocorrelation, visualized monthly mean concentration, seasonally adjusted monthly mean, STL seasonality component, and STL trend component for each of the two pollutants. Ran regressions of model parameters to compare the proportion of variation that was attributable to seasonality for nitrogen and phosphorus, as well as to compare 95% confidence intervals for change in each pollutant's trend component over the 10-year period.

### Datasets
- 2010-2019 Chesapeake Bay Program (CBP) Traditional Partner Tidal XLSXs

### Data References
- Chesapeake Bay Program DataHub. n.d. “Traditional Partner Tidal (Tier 3) Data.” https://datahub.chesapeakebay.net/FileDownloads.

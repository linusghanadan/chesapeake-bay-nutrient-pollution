# Time Series Analysis of Nutrient Concentration in Chesapeake Bay
## Purpose
This analysis seeks to better understand the seasonality of nitrogen and phosphorus concentration in Chesapeake Bay tidal regions, in addition to any non-seasonal trends since 2010. For this reason, I build a seasonal trends decomposition using LOESS (STL) model, which models concentration as a function of three components: seasonal trend, non-seasonal trend, and remainder. After analyzing my STL model with visualizations and parameter regressions, I make conclusions regarding the driving forces of variation in nutrient pollution over the previous decade.

## Repository contents
    chesapeake_bay_nutrient_pollution
    └───images
        │   STL visualization for nitrogen: nitrogen.png
        │   STL visualization for phosphorus: phosphorus.png
    │   README.md
    │   .Rmd
    │   .Rproj

## Datasets
- 2010-2019 Chesapeake Bay Program (CBP) Traditional Partner Tidal XLSXs

## Data references
- Chesapeake Bay Program DataHub. n.d. “Traditional Partner Tidal (Tier 3) Data.” https://datahub.chesapeakebay.net/FileDownloads.

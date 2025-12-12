# California Crop Water Use Analysis

### Gamma Regression Modeling Across Hydrologic Regions (2016 - 2020)

## About This Repository

This repository contains the analysis for a statistical modeling project that examines how crop type, hydrologic region, and year influence *applied water per acre* in California. The project includes:

-   California Department of Water Resources - Agricultural Water Use Data from 2016 to 2020

-   Data wrangling and reshaping of crop(s) irrigation outputs

-   A directed acyclic graph (DAG) describing hypothesized causal relationships

-   Gamma generalized linear modeling (GLM) to quantify the effects of climate region and crop selection on agriculture water use

-   Simulate data to demonstrate model assumptions

The goal is to understand which factors drive differences in irrigation across California and apply gamma model to applied water requirements with a positive continuous response.

## Repository Structure

``` bash
crop-water-gamma
├── crop-water-gamma.qmd
├── crop-water-gamma.Rproj
├── data
│   └── agricultural_water_use_data_2016_2020.xlsx
└── README.md
```

## Data Access

This project uses publicly available water use data from the [California Department of Water Resources](https://data.ca.gov/dataset/statewide-agricultural-water-use-data-2016-2020) (DWR).

#### Statewide Agricultural Water Use Dataset (2016 - 2020)

The Statewide Agricultural Water Use Dataset (WY 2016–2020) provides statewide estimates of applied water (acre-feet per acre), irrigated crop area, evapotranspiration metrics (ETc and ETaw), hydrologic region classifications, and crop-level applied water values reported annually across California. Our project requires the `Statewide_AW_Unit` sheet, which shows the seasonal applied water per acre for 20 crop categories across 10 hydrologic regions.

## Authorship

This repository was created for the following course: EDS 222 - Statistics for Environmental Data Science University of California, Santa Barbara

**Project Author**: Jay Kim

**Instructor**: Max Czapanskiy

**Teaching Assistant**: Nathan Grimes

## Reference

[1] California Department of Food and Agriculture. (2024). *California agricultural production statistics* [web page]. Available: [https://www.cdfa.ca.gov/statistics.](https://www.cdfa.ca.gov/statistics.) [Accessed: Dec. 1, 2025]

[2] California Department of Water Resources. (2023). *Statewide Agricultural Water Use Estimates, Water Years 2016–2020* [data file]. Available: <https://data.cnra.ca.gov/dataset/agricultural-water-use-estimates>. [Accessed: Oct. 25, 2025]

[3] Mode Analytics. (2021). *Violin Plots 101: Visualizing Distribution and Probability Density* [web page]. Available: <https://mode.com/blog/violin-plot-examples>. [Accessed: Dec. 11, 2025]

[4] Wikimedia Commons. (2024). *Sisteme-de-irigatie.jpg* [image file]. Available: <https://commons.wikimedia.org/w/index.php?title=File:Sisteme-de-irigatie.jpg&oldid=838313884.> [Accessed: Dec. 4, 2025]

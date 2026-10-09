# The Modern Rise of STIs in the U.S.

**INFO 201 Group Project | University of Washington | 2025**  
**Authors:** Yan Peng, Mavis Yu, Ting-Yu Hsu, and Houzhengwu Shi

## Overview

This project explores long-term trends and geographic disparities in sexually transmitted infections (STIs) across the United States, with a particular focus on syphilis.

Using publicly available CDC surveillance data, we analyzed national STI trends from 2000 to 2023 and examined regional differences in syphilis rates.

## Methods

- **Data cleaning and preparation:** Processed missing values and standardized CDC surveillance datasets using R and `tidyverse`.
- **Exploratory analysis:** Compared STI rates across years, states, and counties.
- **Data visualization:** Used `ggplot2` to visualize temporal trends and geographic disparities.

## Key Findings

- Syphilis rates increased substantially after 2015.
- STI trends varied across diseases and geographic regions.
- South Dakota exhibited particularly high syphilis rates, highlighting regional disparities and the importance of accounting for population size when interpreting rates.

## Project Files

- `project.Rmd` — R Markdown source containing data cleaning, analysis, and visualization.
- `STIs in the U.S..pptx.pdf` — Project presentation with results and figures.
- `AtlasPlusTableData.csv` — CDC AtlasPlus surveillance data.
- `PS-Syphilis-Rates-Women-15-44-Years-by-County-US-2023.csv` — County-level syphilis data.

## Reproducibility

Open `project.Rmd` in RStudio and select **Knit** after installing the required R packages. Keep both CSV files in the same directory as the R Markdown file.

# Effect of Erythromycin on Bacterial Growth Across Temperature

## Overview
This project analyzes whether erythromycin significantly affects bacterial 
growth (log optical density) across a range of incubation temperatures 
(25–55°C), and whether this effect depends on temperature.

## Files
- `Bacterial Growth.qmd` — full reproducible analysis (R code + interpretation)
- `Bacterial Growth.html` — rendered report ([view live report](LINK-YAHAN-AYEGA))
- `sample 2.csv` — raw dataset

## Key Findings
- A significant interaction between treatment and temperature was found 
  (p = 0.041), indicating erythromycin's effect on bacterial growth 
  varies by temperature.
- Model diagnostics suggested treating temperature as categorical 
  (ANOVA) rather than continuous (regression) for this dataset.

## Tools Used
R, tidyverse (dplyr, ggplot2), Quarto
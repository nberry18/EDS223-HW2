# EDS223-HW2: Exploring Patterns of Redlining and Environmental Injustice in Los Angeles, CA

<img width="4272" height="2848" alt="LA" src="https://github.com/user-attachments/assets/d842ef6e-849e-42fc-98f5-7fbaf43da1a2" />


## Purpose
This repository contains an analysis of redlining in Los Angeles, CA. Redlined neighborhoods are neighborhoods that were historically marked as risky for mortgage lending because of racist and classist policies that discriminated against residents based on their racial, ethnic, and/ or economic background. These discriminatory practices contributed to environmental injustice, as redlined areas often experienced greater environmental burdens. This repository explores the relationship between historical HOLC grades (A-D) and present-day socioeconomic and environmental conditions, including low-income households, low life expectancy, and pedestrian and bicycle accident reporting, to evaluate whether disparities persist across neighborhoods.

## Overview
Highlights:
- hw2.qmd file: The first section contains code to create a map of historical redlining neighborhoods in Los Angeles, California, colored by HOLC grade. The second section contains code for a table describing the percentage of census block groups that fall within each HOLC grade. The next section explores the relationship between EJScreen indicators, specifically Low-Income Households and Low Life Expectancy, and historical redlining patterns in LA. The final section contains code for a figure summarizing the percentage of pedestrian and bicycle crash observations located within neighborhoods associated with each HOLC grade.
- Data folder: houses EJ Screen data, Crashes.csv, EJ Screen data index, the technical document of the EJ Screen data, and mapping-inequality-los-angeles.json.

```{r}
EDS223-HW1
└───data
     └───ejscreen_2023
         Crashes.csv
         EJSCREEN_2023_BG_Columns.xlsx
         ejscreen-tech-doc-version-2-2.pdf
         mapping-inequality-los-angeles.json
├── hw2_files
|        figure-html
|        libs
│   hw2.html
│   hw2.qmd
│   README.md
```

## Data Access
The EJ Screen data originally is from the United States Environmental Protection Agency’s EJScreen: Environmental Justice Screening and Mapping Tool. However, this EJ Screen tool and data have been removed from the EPA website and an unofficial version is now stored on this webpage: https://pedp-ejscreen.azurewebsites.net/. The EJ Screen dataset used in this analysis was obtained from a downloadable data folder provided through the Environmental Data Science 223 course at the University of California of Santa Barbara website by Annie Adams: https://eds-223-geospatial.github.io/assignments/HW2.html. 

The HOLC Grade data originally came from a team of researchers at the University of Richmond that digitized maps and information from the HOLC as part of the Mapping Inequality project: https://dsl.richmond.edu/panorama/redlining/#loc=5/39.1/-94.58. For this project specifically we will be working with maps of HOLC grade designations for Los Angeles, CA. This dataset used in this analysis was obtained from a downloadable data folder provided through the Environmental Data Science 223 course at the University of California of Santa Barbara website by Annie Adams: https://eds-223-geospatial.github.io/assignments/HW2.html. 

The Crashes data comes from the Statewide Integrated Traffice Records System (SWITRS) database collects and processes data gathered from a collision scenes. The data is hosted on the Transportation Information Mapping System (TIMS): https://tims.berkeley.edu/, developed by UC Berkley SafeTREC. 

## Author
Nina Berry: https://github.com/nberry18 

## References
- Downloadable EJ Screen dataset: https://drive.google.com/file/d/1nG6Nj1bXfzQFOVMO8Km3eNy4SWu1YcIQ/view?usp=sharing
- EJ Screening and Mapping Tool (stored version): https://pedp-ejscreen.azurewebsites.net/
- HOLC Redlining: [https://dsl.richmond.edu/panorama/redlining/#loc=5/39.1/-94.58&text=downloads](https://dsl.richmond.edu/panorama/redlining/#loc=5/39.1/-94.58&text=downloads)
- Crashes datset: https://tims.berkeley.edu/

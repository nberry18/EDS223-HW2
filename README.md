# EDS223-HW2: Exploring Redlining and Pattern of Environmental Injustice in Los Angeles, CA

<img width="4272" height="2848" alt="LA" src="https://github.com/user-attachments/assets/d842ef6e-849e-42fc-98f5-7fbaf43da1a2" />


## Purpose
This repository contains two maps of Yakima County in Washington State that help identify potential environmental justice concerns. Environmental justice seeks to ensure that all communities are protected from disproportionate environmental burdens that historically have been overlooked contributing to unequal exposure to pollution and environmental hazards. This repository examines whether higher concentrations of PM2.5 are associated with areas in Yakima County that have larger populations of low-income residents and communities of color.

## Overview
Highlights:
- hw2.qmd file: Code for the two maps of Yakima County. The first map displays the EJScreen Demographic Index, highlighting low-income communities and communities of color. The second map shows PM2.5 concentrations, which measure fine particulate matter 2.5 micrometers or smaller in diameter, across the county. 
- Data folder: houses EJ Screen data, EJ Screen data index, and the technical document of the EJ Screen data.

```{r}
EDS223-HW1
└───data
     └───ejscreen_2023
         Crashes.csv
         EJSCREEN_2023_BG_Columns.xlsx
         ejscreen-tech-doc-version-2-2.pdf
         mapping-inequality-los-angeles.json
├── ej_files
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

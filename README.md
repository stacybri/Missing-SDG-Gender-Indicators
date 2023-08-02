--- 
 contributors: 
    - Kathleen Beegle 
    - Umar Serajuddin 
    - Brian Stacy 
    - Divyanshi Wadhwa 
--- 

# Missing SDG Gender Indicators
 Reproducibility Package for "Missing SDG Gender Indicators" paper

## Overview  

The code in this replication packages constructs the analysis files and tables and figures for Beegle, Serajuddin, Stacy, and Wadhwa (2023) using R.  One main file runs all of the code to generate the data and figures.  The file is located in 02_programs/Missing-SDG-Gender-Indicators.Rmd.  The replicator should expect the code to run for around 20-30 minutes. 

### License

The data are licensed under a Creative Commons/CC-BY-4.0 license. 

### Summary of Availability

- [X] All data **are** publicly available.
- [ ] Some data **cannot be made** publicly available.
- [ ] **No data can be made** publicly available.

### Data Sources

| Data.Name  | Data.Files | Location | Provided | Citation |
| -- | -- | -- | -- | -- | 
| “World Development Indicators | WDIEXCEL.xlsx | 01_raw_data/ | TRUE | World Bank (2023). World Development Indicators.   |
| “UN SDG Database” | IT_CEN_MGTN.csv; IT_MOB_OWN.csv; SD_MDP_MUHC.csv;... | 01_raw_data/sdg_data/ | TRUE | UN Global SDG Database |

### Software

R version 4.2.1 (2022-06-23 ucrt) -- "Funny Looking Kid" was used.

This repository contains several files from the R package "renv". The renv package helps manage specific package versions used to produce the results in this repository. Because package version conflicts can make code that runs on one system not run on another system, it is important to have a list of the specific package versions used and a workflow for accessing these specific packages. The renv package provides this. In order to use renv, see the renv documentation here (https://rstudio.github.io/renv/articles/renv.html). In general, the renv::restore() command should install all packages found in the renv.lock file in this repository, so that version conflicts do not cause errors.
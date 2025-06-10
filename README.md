# ENVS 193DS, Final

Spring 2025

## General information

The dataset for problem 2 is from: Kui, L. 2024. Daily sea surface temperature in Santa Barbara channel between 1982 and 2023 ver 3. Environmental Data Initiative. <https://doi.org/10.6073/pasta/e930954949b2635928b8be6824630f84>.


The dataset for problem 3 is from: Stojanovic, Dejan et al. (2021). Do nest boxes breed the target species or its competitors? A case study of a critically endangered bird [Dataset]. Dryad. <https://doi.org/10.5061/dryad.83bk3j9sb>.

The published paper for problem 3 is: Stojanovic, D., Owens, G., Young, C.M., Alves, F. and Heinsohn, R. (2021), Do nest boxes breed the target species or its competitors? A case study of a critically endangered bird. Restor Ecol, 29: e13319. <https://doi.org/10.1111/rec.13319>.

This repository is for research writing, data visualization, data analysis, and affective and exploratory visualizations.

### Packages

```         
library(tidyverse) # general use
library(lubridate) # working with dates and times
library(ggplot2) # creating plots and data visualizations
library(flextable) # creating tables
library(gt) # creating tables
library(here) # file organization
library(janitor) # cleaning data frames
library (dplyr) # wrangling and manipulating data
library(scales) # modifying axis labels
library(ggeffects) # getting model predictions
library(MuMIn) # model selection
```

## Data and file information

File structure:

```         
.
├── ENVS-193DS_spring-2025_final.Rproj
├── README.md
├── code                                     # code folder
│   ├── ENVS-193DS_spring-2025_final_files
│   ├── ENVS-193DS_spring-2025_final.html     
│   └── ENVS-193DS_spring-2025_final.qmd
└── data                                     # data folder
    ├── SST_update2023.csv
    └── occdist.csv
    
```

All code is in the `code` folder. The code runs models, generates model predictions, and visualizes data.

## Rendered output

The rendered output is [here](https://samantha-ross2303.github.io/ENVS-193DS_spring-2025_final/code/ENVS-193DS_spring-2025_final.html).

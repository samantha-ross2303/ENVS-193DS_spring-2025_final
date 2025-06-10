# ENVS 193DS, Final

Spring 2025

## General information

This dataset is from: Stojanovic, Dejan et al. (2021). Do nest boxes breed the target species or its competitors? A case study of a critically endangered bird [Dataset]. Dryad. <https://doi.org/10.5061/dryad.83bk3j9sb>

The published paper is: 

This repository is for demonstrating fitting models with categorical and continuous predictors and model selection.

### Packages

```         
library(tidyverse) # general use
library(lubridate) # 
library(ggplot2) # 
library(flextable) # 
library(gt) # 
library(here) # file organization
library(janitor) # cleaning data frames
library (dplyr) # 
library(scales) # modifying axis labels
library(ggeffects) # getting model predictions
library(MuMIn) # model selection
```

## Data and file information

File structure:

```         
.
├── ENVS-193DS_workshop-08.Rproj
├── README.md
├── code                                     # code folder
│   ├── workshop-08_code_KEY.Rmd             # keys
│   ├── workshop-08_code_KEY.html            # rendered output is from .qmd key
│   ├── workshop-08_code_KEY.qmd
│   ├── workshop-08_code_KEY_files
│   ├── workshop-08_code_TEMPLATE.Rmd        # templates
│   └── workshop-08_code_TEMPLATE.qmd
└── data                                     # data folder
    └── Valliere_etal_EcoApps_Data.xlsx
```

All code is in the `code` folder. The code runs models, generates model predictions, and visualizes data.

## Rendered output

The rendered output is [here](https://samantha-ross2303.github.io/ENVS-193DS_spring-2025_final/code/ENVS-193DS_spring-2025_final.html).

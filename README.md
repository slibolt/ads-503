# ADS 503, University of San Diego
Course: Applied Predictive Modeling (ADS-503-01)
Professor: Ebrahim Tarshizi

## Diabetes Prediction Project (ADS 503 Group 3)

This project applies data science techniques to predict diabetes using behavioral and clinical variables from the 2023 CDC BRFSS (Behavioral Risk Factor Surveillance System) dataset. The pipeline includes comprehensive data cleaning, feature selection, multiple machine learning models, and a deployed RShiny app using the top-performing model.

### 👥 Team Members
- Jimmy Hwang  
- Sasha Libolt

### 🗃️ Dataset

- **Source**: [CDC BRFSS 2023](https://www.cdc.gov/brfss/annual_data/2023/files/LLCP2023XPT.zip)
- **Size**: >400,000 observations, 350 features
- **Target Variable**: `DIABETE4` — binary indicator of diabetes (Yes = 1, No = 3)
- **Note**: Raw file must be downloaded separately and path updated in code.

### ⚙️ Environment Setup

Install required R libraries:
```r
install.packages(c("tidyverse", "caret", "haven", "dlookr", "naniar", 
                   "explore", "corrr", "gt", "pROC", "shiny", "bslib", "vcd"))
```

## ▶️ Run Project
To run the entire project from start to finish, simply open and execute the ADS503_Group3_FinalProject.qmd Quarto file. This file contains all the data cleaning, modeling, and visualization steps in one place.

✅ Note: Make sure you update the file path to the BRFSS .XPT file and install all required libraries before running.

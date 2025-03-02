# Econometrics Regression Study

This repository contains the analysis for an econometrics problem set focused on two datasets: **College Distance** and **Loan Applications**. The project involves regression analysis, hypothesis testing, and data exploration using R.

## Datasets

1. **College Distance**: Analyzes the relationship between years of education completed and factors like distance to college, income, and parental education.
2. **Loan Applications**: Examines the factors influencing loan amounts requested by applicants, including income, demographics, and property details.

## Key Analyses

- **Regression Models**: Linear and robust regression models to analyze relationships between variables.
- **Hypothesis Testing**: F-tests and t-tests to evaluate the significance of predictors.
- **Data Visualization**: Histograms, scatterplots, and residual analysis to explore data patterns.
- **Log Transformations**: Applied to normalize skewed data and improve model performance.

## Files

- `analysis.R`: R script containing the code for data loading, cleaning, analysis, and visualization.
- `CollegeDistance.xls`: Dataset for the College Distance analysis.
- `loan_applications.csv`: Dataset for the Loan Applications analysis.
- `README.md`: This file.

## Tools Used

- **R**: Primary programming language for data analysis.
- **R Packages**: `estimatr`, `ggplot2`, `dplyr`, `readxl`, `car`.

## How to Run

1. Clone this repository.
2. Open `analysis.R` in RStudio or any R environment.
3. Install the required packages using:
   ```R
   install.packages(c("estimatr", "ggplot2", "dplyr", "readxl", "car"))

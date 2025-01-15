# Air Quality Analysis Project

## Overview
This project analyzes air quality data collected from chemical sensors in an Italian city. The dataset contains hourly averaged responses from an array of 5 metal oxide chemical sensors, recorded from March 2004 to February 2005.

## Dataset Description
The dataset includes 9,358 instances with 15 features:
- Date and Time information
- True hourly averaged concentrations of various pollutants (CO, Non Metanic Hydrocarbons, Benzene, NOx, NO2)
- Sensor responses from different types of sensors (tin oxide, titania, tungsten oxide, indium oxide)
- Environmental parameters (Temperature, Relative Humidity, Absolute Humidity)

Missing values are tagged with -200 value in the original dataset.

## Project Tasks

### 1. Data Quality Control
- Recognition and handling of missing values
- Recoding of missing values
- Distribution analysis
- Target variable quality assessment

### 2. Statistical Analysis
- Frequency distribution visualization for categorical variables
- Statistical measures for continuous variables:
  - Mean values
  - Z values
  - Distribution roundness
  - Distribution skewness
- Correlation analysis with target variables
- Z-value categorization and analysis

### 3. Information Value (IV) and Weight of Evidence (WoE) Analysis
- IV and WoE calculations for all variables
- Visualization of WoE for strongest predictors
- Class grouping based on WoE criterion
- Profile analysis and recommendations

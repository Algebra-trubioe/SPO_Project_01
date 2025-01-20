# Air Quality Analysis Project

This project analyzes air quality data using various statistical methods and techniques including data quality control, statistical analysis, and Information Value (IV) / Weight of Evidence (WoE) calculations.

## Project Structure
```
.
├── AirQualityAnalysis.ipynb    # Main analysis notebook
├── data/
│   ├── AirQualityUCI.csv      # Raw air quality dataset
│   └── Air Quality - UCI Machine Learning Repository.pdf  # Dataset documentation
├── README.md                   # This file
└── Requirements.txt           # Python dependencies
```

## Tasks Overview

### 1. Data Quality Control
- Recognition and analysis of missing values
- Recoding of missing values
- Recognition of uniform or illogical distributions
- Target variable analysis and quality assessment
- Findings documentation and explanation

### 2. Statistical Analysis
- Frequency distribution analysis for categorical variables
- Statistical measures for continuous variables:
  - Mean values
  - Z values
  - Distribution roundness
  - Distribution skewness
- Correlation analysis with target variable
- Z-value class correlations analysis
- Comprehensive findings explanation

### 3. IV and WoE Analysis
- IV and WoE calculations for all variables
- Analysis of strongest IV variables with WoE visualization
- Class grouping based on WoE criterion
- Profile analysis and causal relationships
- Problem-solving recommendations based on analysis

## Reproduction Steps

1. **Environment Setup**
```bash
# Clone the repository
git clone https://github.com/Algebra-trubioe/SPO_Project_01.git
cd SPO_Project_01

# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows use: .venv\Scripts\activate

# Install dependencies
pip install -r Requirements.txt
```

2. **Data Preparation**
- Place the `AirQualityUCI.csv` file in the `data/` directory
- Ensure the UCI documentation PDF is present in the `data/` directory

3. **Running the Analysis**
- Launch Jupyter Notebook:
```bash
jupyter notebook
```
- Open `AirQualityAnalysis.ipynb`
- Run all cells sequentially from top to bottom

## Notes

- Ensure all cells in the notebook are executed in order
- The analysis includes data preprocessing, missing value handling, and various statistical computations
- Visualizations are generated throughout the notebook to support the analysis
- Results and interpretations are provided inline with the code
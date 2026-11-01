# Fadil Asif Iqbal
### 4SF25CI051 - 3C

## Dataset Instructions

The dataset is provided as a ZIP file because the original CSV exceeds GitHub's recommended upload size.

Before running the Jupyter Notebook:

1. Download `zomato.csv.zip` from this repository.
2. Extract the ZIP file.
3. Place the extracted `zomato.csv` in the same directory as the Jupyter Notebook.
4. Run all notebook cells.

**Note:** The notebook reads the extracted CSV file, not the ZIP file.

# Zomato Data Analysis

## Overview
A Python-based exploratory data analysis project on the Zomato restaurant dataset. The project focuses on data cleaning, transformation, missing value handling, insight generation, and visualization.

## Dataset
- **Dataset:** Zomato Restaurant Dataset
- **Format:** CSV
- **Original Records:** 51,717
- **Original Columns:** 17
- **Source:** Kaggle

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Processing
- Removed unnecessary columns.
- Identified and removed duplicate records.
- Cleaned and converted rating and cost columns into numeric formats.
- Handled numerical missing values using mean imputation.
- Handled categorical missing values using mode imputation.
- Reset the DataFrame index.

## Analysis Performed
- Average restaurant ratings and dining costs.
- Top 10 restaurant locations.
- Popular cuisine combinations.
- Online vs offline ordering distribution.
- Average ratings based on online ordering.
- Top restaurants based on aggregated votes.

## Visualizations
Created bar charts, pie charts, and histograms using Matplotlib and Seaborn.

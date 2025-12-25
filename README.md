# California Housing Price Prediction

An end-to-end data analysis and machine learning project using the CA-Housing dataset to predict median house values.

## Project Overview
This repository contains a comprehensive analysis of California housing data. The goal is to build a predictive model that estimates house prices based on features like location, population, and median income.

## Tech Stack
Language: Python
Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
Model: Linear Regression

## Key Steps

### Exploratory Data Analysis (EDA)
- Overplotting Mitigation: Handled high-density scatter plots using alpha transparency and hexbinning to visualize geographic price clusters.
- Correlation Analysis: Identified Median Income as the strongest predictor of house value.


### Data Preprocessing
- Handling Missing Values: Implemented imputation strategies for incomplete features
- Categorical Encoding: Applied One-Hot Encoding to the ocean_proximity column to convert text labels into a machine-readable format.
- Feature Scaling: Standardized numerical attributes to ensure the Linear Regression model converges efficiently.


### Machine Learning
- Splitting: Divided data into 80% training and 20% testing sets.
- Model Training: Fit a Linear Regression model to the processed training data.
- Evaluation: Validated performance using Root Mean Squared Error (RMSE) and R2 score


## Results
The model provides a baseline for housing prediction, highlighting the significant impact of proximity to the coast and household income on property valuation in California.

```
## How to Run
  1. Clone the repo: git clone https://github.com/hstamper/CA-Housing-Analysis.git
  2. Run the notebook: jupyter notebook CA_Housing.ipynb
```

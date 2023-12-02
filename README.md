# Polish-Bankruptcy-Dataset

## Overview
This project involves the analysis of the Polish Bankruptcy dataset with the aim of developing a predictive model to identify potential bankruptcy cases based on various financial indicators. The analysis covers data preprocessing, exploratory data analysis (EDA), feature engineering, model selection, and evaluation.

## Contents
notebook.ipynb: Jupyter notebook containing the full analysis, including data loading, preprocessing, EDA, feature engineering, model training, and evaluation.
data/: Directory containing the dataset used in the analysis.
requirements.txt: List of Python dependencies required to run the notebook.
Installation
To set up the environment to run this notebook, install the required Python packages using:

pip install -r requirements.txt

## Data Description
The dataset includes financial ratios derived from annual financial statements of Polish companies. The main objective is to predict the bankruptcy status (class column) of a company based on these financial ratios.

## Methodology
### Data Preprocessing: 
Converting data types, handling missing values, and data cleaning.

### Exploratory Data Analysis: 
Statistical analysis and visualization of the data to uncover trends and patterns.

### Model Selection and Evaluation: 
Training a RandomForestClassifier and tuning it using GridSearchCV. Evaluation metrics include accuracy and F1 score.

## Results
The RandomForest model showed promising results in predicting bankruptcy. Detailed results and insights are provided in the notebook.

## Future Work
Future analysis could include testing more sophisticated models and employing advanced imputation methods to handle missing data more effectively.

## Contact
For any queries regarding this project, please contact Alexia.

# A Novel Application of Machine Learning for Multi-Disease Detection

## Overview

This project has been done to detect multi-disease (heart and kidney disease) with the application of data analytics specifically the implication of machine learning models with their optimized parameter settings.

## Features

1. **Data Preprocessing:**
   - Treating missing values through data cleaning.
   - Treating outliers using PCA and reduced using data normalization.

2. **Exploratory Data Analysis (EDA):**
   - The features of the data have been analyzed based on the disease statistics.

3. **Feature Selection:**
   - The features from datasets (heart and kidney disease) have been selected using a hybrid approach by combining RFE and Chi-Squared methods.

4. **Model Optimization and Model Preparation:**
   - The chosen models have been optimized using the GridSearch method with 5-Fold Cross Validation.
   - Preparing the tuned models.
   - Design the hybrid model for the detection of multiple disease by combining the top-performing models namely Decision Tree and Random Forest.

5. **Disease Detection:**
   - Apply the models through training and testing to predict disease.
   - Compares model performance using classification metrics such as accuracy, precision etc.

6. **Visualization:**
   - Plots the performance results using bar charts.

## Requirements

The project requires Python 3.9 or above and the following Python libraries:

- `warnings`
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`

Install dependencies using the following command:
```
pip install numpy pandas matplotlib seaborn scikit-learn



```python

```

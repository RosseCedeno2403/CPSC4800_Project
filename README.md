# CPSC4800_Project
# Titanic Dataset Analysis

## Overview

This data analysis project explores the Titanic dataset, aiming to gain insights into the factors that influenced passenger survival rates. The project involves data preprocessing, statistical analysis, and data visualization to uncover patterns and correlations within the dataset.

## Data

### Dataset

- The dataset used for this analysis is the "Titanic: Machine Learning from Disaster" dataset from Kaggle.
- Dataset Source: [Titanic Dataset on Kaggle](https://www.kaggle.com/c/titanic/data)
- Format: CSV
- Description: The dataset contains information about passengers on the Titanic, including features like age, sex, class, and survival status.

### Data Preprocessing

- The dataset was cleaned and preprocessed to handle missing values and outliers.
- Data wrangling techniques, such as imputation and feature engineering, were applied.

## Analysis

### Key Findings

- Survival rates were significantly higher for passengers in first class compared to other classes.
- Females had a considerably higher chance of survival than males.
- Passengers with specific titles (e.g., "Mrs," "Miss") had higher survival rates.
- Age and ticket fare also played a role in survival.

### Data Visualization

- Visualizations, including bar charts and histograms, were created to illustrate the key findings.
- These visualizations provide a clear understanding of the factors influencing survival rates.

## Methodology

- The analysis involved descriptive statistics and data visualization using Python and libraries such as pandas, NumPy, and Matplotlib.

## Usage

### Prerequisites

To replicate this analysis, ensure you have the following software and libraries installed:

- Python (3.x)
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn

# House Prices - Train Dataset Analysis

## Overview

This repository presents a detailed analysis of the "train.csv" dataset, which is part of the "House Prices - Advanced Regression Techniques" competition on Kaggle. The analysis focuses on understanding the factors that influence house sale prices. The dataset includes a wide range of features related to residential properties, and this README provides key insights based on statistical analysis.

## Dataset Information

### Dataset Source

- The "train.csv" dataset is provided by Kaggle as part of the "House Prices - Advanced Regression Techniques" competition.
- Dataset Source: [House Prices - Advanced Regression Techniques (Train Dataset)](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

### Purpose

- The primary purpose of this dataset is for predictive modeling, particularly for predicting house sale prices.
- The dataset serves as the training dataset for the Kaggle competition.

### Format

- The dataset is provided in CSV (Comma-Separated Values) format.
- It includes a collection of features (variables) related to residential properties.

## Statistical Analysis and Key Findings

The analysis of the "train.csv" dataset has yielded the following key findings:

### SalePrice vs. YearBuilt

- Year Built Histogram (Left Skewed):
  - The left-skewed histogram for "YearBuilt" suggests that the majority of properties are relatively more recently constructed, with fewer older properties.
- Correlation Coefficient (0.523):
  - A moderately strong positive correlation coefficient (0.523) indicates that, on average, newer properties tend to have higher sale prices.
- Year Built Whisker Plot (Left Skewed with Outliers to the Left):
  - The left-skewed whisker plot and the presence of outliers to the left confirm the distribution's skewness.

### SalePrice vs. Ground Living Area (GrLivArea)

- Ground Living Area Histogram (Slightly Right Skewed):
  - The slightly right-skewed histogram for "GrLivArea" indicates that most properties have smaller ground living areas, with a tail to the right for larger living spaces.
- Correlation Coefficient (0.708):
  - A relatively strong positive correlation coefficient (0.708) suggests that, on average, larger ground living areas are associated with higher sale prices.
- Ground Living Area Whisker Plot (Slightly Right Skewed with Outliers to the Right):
  - The slightly right-skewed whisker plot and the presence of outliers to the right confirm the distribution's skewness.

### SalePrice vs. Total Basement Area (TotalBsmtSF)

- Total Basement Area Histogram (Slightly Right Skewed):
  - The slightly right-skewed histogram for "TotalBsmtSF" indicates that most properties have smaller basement areas, with a tail to the right for larger basements.
- Correlation Coefficient (0.613):
  - A moderately strong positive correlation coefficient (0.613) suggests that, on average, larger basement areas are associated with higher sale prices.
- Total Basement Area Whisker Plot (Slightly Right Skewed with Outliers):
  - The slightly right-skewed whisker plot and the presence of outliers on both sides confirm the distribution's characteristics.

## Data Usage

- The statistical insights and findings presented here are valuable for researchers, data scientists, and machine learning practitioners looking to build predictive models for house prices.
- The analysis results can inform regression analysis, feature selection, and model development.

## Acknowledgments

- The "train.csv" dataset is provided by Kaggle.
- Special thanks to Kaggle and the competition organizers for making this dataset available for educational and analytical purposes.

## License

- The usage of this dataset is subject to Kaggle's terms and conditions. Please review Kaggle's licensing and usage policies for specific details.

## Project Structure

- The project structure typically includes data files, Jupyter notebooks, and additional scripts used for the analysis.



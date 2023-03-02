# Data Mining Project: Understanding Correlations between Stroke Data and Health Indicators

## Overview
This repository contains the code and data for my data mining project, where I explored correlations between stroke data and various health indicators among different groups of individuals. The project involved basic data preprocessing techniques such as one-hot encoding, imputation, and outlier detection and removal using quantile-based capping and flooring to lower the level of skewness, as well as visualization techniques to find correlations between attributes and to find stroke count among the different features.

## Dataset
Link to the original dataset used in the project: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

## Features
The dataset used in this project includes the following features:

- id: unique identifier for each individual
- age: age of the individual
- hypertension: whether the individual has hypertension (1 = yes, 0 = no)
- heart disease: whether the individual has heart disease (1 = yes, 0 = no)
- average glucose level: average glucose level in the individual's blood
- BMI: body mass index
- stroke: whether the individual had a stroke (1 = yes, 0 = no)

## Data Preprocessing Techniques Used
The following data preprocessing techniques were employed:

- One-hot encoding: to convert categorical variables into numerical variables
- Imputation: to fill in missing data
- Outlier detection and removal using quantile-based capping and flooring: to lower the level of skewness in the data

## Visualization Techniques Used
The following visualization techniques were used to explore correlations between attributes and to find stroke count among the different features:

- Scatter plots
- Correlation matrix
- Bar plots
- Heat maps

## Conclusion
Through the application of data preprocessing and visualization techniques, this project provided insights into correlations between stroke data and various health indicators among different groups of individuals. The code and data in this repository can be used as a resource for further research in this area.

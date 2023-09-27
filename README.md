
# Vehicle Category Prediction

## Overview

🚗🔍 This project focuses on predicting the category of vehicles based on various attributes.               The dataset used in this project contains information about different vehicles, including attributes like compactness, circularity, distance circularity, radius ratio, and more. The dataset also includes the vehicle categories.

## Data Exploration

We started by exploring the dataset to understand its characteristics. We checked for missing values and found that there were 41 missing values in the dataset. We handled these missing values by replacing them with the median values of their respective columns.

We also analyzed the data types of the features, which include integer, float, and object (categorical) types.

## Data Visualization

To gain insights into the dataset, we created several visualizations. We plotted histograms to visualize the distribution of numerical features. We also used boxplots to identify potential outliers in the data.

Additionally, we generated a correlation matrix heatmap to visualize the relationships between numerical attributes. This helped us identify which attributes are highly correlated with each other.

A pairplot was created to visualize pairwise relationships between numerical features.

## Data Preprocessing

Normalization was performed on the dataset to ensure that all numerical features have similar scales. This step is crucial for many machine learning algorithms.

# Principal Component Analysis (PCA)

Principal Component Analysis (PCA) was applied to reduce the dimensionality of the dataset while preserving its essential information. We analyzed the explained variance and the principal components to understand the contribution of each feature to the dataset's variability.

The PCA results can be used as input features for machine learning models to predict the vehicle category.
## 🔗 Links
[![portfolio](https://img.shields.io/badge/view_my_notebook-000?style=for-the-badge&logo=github&logoColor=white)](https://nbviewer.org/github/Harinivas44/Vehicle_Category_Prediction/blob/main/Unsupervised_KMeans.ipynb)

# Machine Learning Final Project - README

## Project Overview

In this project, we explore a binary classification problem using various machine learning models. The project involves data exploration, preprocessing, modeling, and evaluation stages. The primary objective is to identify the best-performing model that can classify new data effectively.

ML models: KNN, ANN, Decision Tree, Adaptive Boosting
Evaluation Methods: confusion matrix, ROC Curece, AUC Score.

## Dataset Description

The dataset used in this project contains information about user behaviors in an online shopping website. It consists of several features that serve as input variables for the models. The target variable is binary (purchase made / not made), representing the two classes we want to classify.

## Libraries Used

The project utilizes the following Python libraries:

- pandas: For data manipulation and preprocessing.
- numpy: For numerical operations and array handling.
- scipy.stats: For statistical computations.
- plotly.express: For interactive data visualization.
- seaborn: For advanced data visualization.
- matplotlib.pyplot: For basic data plotting.

## Project Stages

The project is divided into several stages, as follows:

1. Data Import: We import the dataset from a CSV file and load it into a pandas DataFrame.

2. Exploration: We perform an exploratory analysis of the dataset, obtaining general information and visualizing the distribution of both numeric and categorical factors.

3. Preprocessing:

  3.1. Duplicates: We remove duplicate instances.

  3.2. Nulls: We handled nulls by exploring the feature and completing null values with a relevnat value.
  
  3.3. One-Hot Encoding: We handeled categorial features by applying one-hot encoding.
  
  3.4. Outliers: We investigate and handle potential outliers in the dataset.

  3.5. Missing Data: We deal with any remaining missing data, employing appropriate imputation techniques.

  3.6. Data Scaling: We apply data scaling to standardize the numeric features.

  3.7. PCA (Principal Component Analysis): We perform PCA for dimensionality reduction.
  
4. Modeling: We build different machine learning models, including K-Nearest Neighbors (KNN), Multi-Layer Perceptron (MLP), Decision Tree, and Adaptive Boosting.

5. Model Evaluation: We evaluate the performance of each model using metrics such as confusion matrix, cross-validation, and checking for overfitting.

6. Prediction: We use the best-performing model to make predictions on new data.

## Running the Project

Before running the project, ensure you have the required libraries installed. The main script contains the code for all stages of the project. Run the cells sequentially in your Jupyter notebook or preferred Python environment.

## Conclusion

The Machine Learning Final Project involves comprehensive exploration, preprocessing, modeling, and evaluation of various machine learning models. The project aims to identify the most effective model for binary classification tasks. For detailed information and implementation, refer to the code and visualizations in the project files.

---

_This README file serves as documentation for the Machine Learning Final Project. For detailed information and implementation, refer to the code and visualizations in the project files._

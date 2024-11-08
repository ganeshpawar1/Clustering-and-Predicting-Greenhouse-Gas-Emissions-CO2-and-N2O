CO₂ and N₂O Emissions Analysis and Prediction

This project analyzes CO₂ and N₂O emissions data across countries, sourced from the World Bank Open Data. The project uses various machine learning techniques, including Linear Regression, Logistic Regression, SVM, and K-Means Clustering, to explore, predict, and classify emission patterns.


Project Overview

This project aims to:

Cluster Countries based on CO₂ and N₂O emissions using K-Means Clustering, categorizing them into groups with similar emission levels.
Predict Emissions using machine learning models like Linear Regression, Logistic Regression, and SVM to identify trends and project future emission levels.
The analysis provides insights into factors influencing emissions, offering a foundation for further climate research.

Dataset:

The dataset emissions.csv is derived from the World Bank Open Data, containing features that potentially impact CO₂ and N₂O emissions.

Data Preprocessing

Encoding: Categorical country data was numerically encoded.

Scaling: Features were normalized for better model performance.

Algorithms Used:

K-Means Clustering: Clustered countries based on emissions data to identify common patterns.
Linear Regression: Used for predicting emission levels based on continuous features.
Logistic Regression: Applied to classify emission levels into categories.
Support Vector Machine (SVM): Utilized for a robust classification of emission trends.
Project Structure
The project includes:

Notebook: The Jupyter notebook contains the complete workflow, including data preprocessing, clustering, modeling, and evaluation.
Data File (emissions.csv): The dataset file used in the analysis.

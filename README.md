# week1
Week1
This project aims to analyze country-specific data and develop predictive models to estimate CO2 emissions.The dataset comprises data from 1990 to 2011, covering countries worldwide. It includes a wide variety of features such as population statistics, economic indicators, land use, energy consumption, and more.

Dataset Summary
Years: 1990 to 2011 Countries: Global coverage

Features: Greenhouse gas emissions (CO2, CH4, N2O) Population data (total, urban, growth) Economic indicators (GDP, GNI, FDI) Agricultural and land parameters Energy usage Climate statistics (precipitation, disasters) Health indicators (medical staff counts)

Stage 1: Data Cleaning and Preparation
Import and overview of raw data
Handling missing values
Feature renaming and formatting
Conversion to numerical types
Melting and transforming datasets
Final clean dataset exported as data_cleaned.csv

# week2

This notebook represents the foundational phase of our data science workflow—Exploratory Data Analysis (EDA) and Data Preprocessing. The objective was to transform a raw dataset into a clean, structured format suitable for modeling and statistical analysis. Below are the key technical steps performed:

Data Filtering & Row Elimination: Rows containing metadata markers (e.g., "Text" in SCALE or Decimals) were removed to retain only relevant, quantifiable observations.

Feature Selection: Non-informative columns such as "Country name", "Series code", "SCALE", and "Decimals" were dropped to reduce dimensionality and enhance processing efficiency.

Missing Value Treatment: Placeholder strings like ".." and empty cells were converted to NaN, enabling easier detection and later imputation or exclusion, as required.

Data Type Standardization: All columns were coerced into appropriate numerical data types, ensuring compatibility with statistical methods and machine learning models.

Initial Statistical Profiling (optional if added later): Summary statistics and data distribution checks can now be applied on this cleaned dataset for further insights.

This preprocessing pipeline ensures the dataset meets the requirements for robust modeling, reduces noise, and minimizes data leakage risks. With this solid data foundation, the next phase will involve feature engineering, correlation analysis, and model training for predictive analytics.

# week3 CO₂ Emissions Prediction: Model Building Phase

This repository contains the Model Building Phase of a machine learning project to predict CO₂ emissions using World Bank datasets. This phase follows data preprocessing and focuses on selecting, training, evaluating, and fine-tuning models.

Objective- To build and evaluate machine learning models that can accurately predict CO₂ emissions per capita using features extracted from historical socioeconomic and energy-related data.


Features :-
1. Feature selection based on correlation and domain relevance.
2. Hyperparameter tuning using GridSearchCV.
3. Model evaluation with metrics like R² Score, MAE, MSE, and RMSE.
4. Visual comparison of model performances.

Evaluation Metrics
1. R² Score
2. Mean Absolute Error (MAE)
3. Mean Squared Error (MSE)
4. Root Mean Squared Error (RMSE)

Results
1. Best model identified: XGBoost Regressor
2. Highest R² Score among tested models.
3. Generalization validated through test set performance.


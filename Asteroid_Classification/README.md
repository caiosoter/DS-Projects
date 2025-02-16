
![](https://images.rawpixel.com/image_800/cHJpdmF0ZS9zdGF0aWMvaW1hZ2VzL3dlYnNpdGUvMjAyMy0wNC93azEwMjc4MDUxMS1pbWFnZS5qcGc.jpg)

# Asteroid Hazard Classification

## Problem Summary

The increasing threat of potentially hazardous asteroids (PHAs) poses a significant challenge to Earth's safety. Understanding the characteristics, behaviors, and risks associated with these celestial bodies is crucial to develop effective mitigation strategies. This data analysis project addresses this critical need by investigating a comprehensive asteroid dataset to build predictive models capable of accurately identifying PHAs. If you would like to seek to understand more about the analysis and the results I encourage you to go through the [Notebook](https://github.com/caiosoter/DS-Projects/blob/main/Asteroid_Classification/Asteroid_Classification.ipynb).

## Project Objective

This project aims to conduct an in-depth analysis of an asteroid dataset, exploring their physical, orbital, and compositional characteristics. The primary objective is to build effective machine learning models that can classify asteroids as hazardous or non-hazardous based on their observable parameters.

## Skills and Technologies Involved

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Missingno, Imblearn, XGBoost, Joblib
* **Data Analysis Techniques:** Data cleaning and preprocessing, exploratory data analysis (EDA), feature engineering, feature selection, predictive modeling, model evaluation, hyperparameter optimization.

## Steps Involved

1. **Data Collection and Preparation:** The data was obtained from Kaggle and loaded into a Pandas DataFrame. Irrelevant columns were removed, missing values were handled, and data types were converted.
2. **Exploratory Data Analysis (EDA):** EDA was performed to identify relevant patterns, trends, and insights in the data. Histograms, box plots, heatmaps, and other visualization techniques were used to understand the distribution, correlation, and outliers of the variables.
3. **Feature Engineering and Feature Selection:** New features were created from the existing data, such as converting categorical variables using one-hot encoding. Feature selection techniques, such as random forest importance, XGBoost importance, and recursive feature elimination (RFE), were employed to identify the most relevant predictors for the model.
4. **Predictive Modeling:** Several machine learning models were trained and evaluated, including Random Forest, Extra Trees, XGBoost, and Multilayer Perceptron. The models were trained using different preprocessing techniques, such as StandardScaler, Min Max Scaler, and Robust Scaler, and their performances were compared using stratified cross-validation.
5. **Model Evaluation:** Evaluation metrics, such as F1-score, recall, precision, and AUC-ROC, were calculated to assess the performance of the models. The confusion matrix was used to visualize the classification results.

## Most Interesting Analyses

* **Variable Correlation:** A strong correlation was observed between the "moid" and "moid_ld" columns, both measuring distances. The "moid_ld" column was discarded due to its larger range.
* **Handling Missing Values:** Missing values in the "sigma" and "pha" columns were identified as related, and observations with missing values in "pha" (target variable) were removed.
* **Feature Importance:** Feature importance analysis revealed that "H" (absolute magnitude) and "moid" (Earth minimum orbit intersection distance) are the most important predictors for the model.
* **Model Performance:** The XGBoost model with Robust Scaler showed the best performance, achieving an F1-score of 0.985622 in cross-validation.

## Next Steps

* **Model Refinement:** The XGBoost model can be further refined by exploring different architectures, loss functions, and regularization techniques.
* **Additional Data Collection:** Collecting additional data, such as spectral characteristics and asteroid images, can enrich the dataset and improve model performance.
* **Production Implementation:** The model can be deployed in a real-time alert system to aid in the identification and monitoring of PHAs.

## References

* **NASA JPL Small-Body Database:** [https://ssd.jpl.nasa.gov/tools/sbdb_lookup.html](https://ssd.jpl.nasa.gov/tools/sbdb_lookup.html)
* [**Asteroid-dataset**](https://www.kaggle.com/datasets/sakhawat18/asteroid-dataset)
* **Scikit-learn Documentation:** [https://scikit-learn.org/](https://scikit-learn.org/)
* **XGBoost Documentation:** [https://www.nvidia.com/en-us/glossary/xgboost/](https://www.nvidia.com/en-us/glossary/xgboost/)
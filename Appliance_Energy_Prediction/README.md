![](https://c0.wallpaperflare.com/preview/61/600/874/energy-inspiration-ideas-planet-waters.jpg)

# Appliance Energy Consumption Prediction

## Problem Summary

The business problem that motivated this project was the need to predict the energy consumption of appliances in low-energy buildings. This prediction is crucial to optimize energy use, reduce costs, and contribute to environmental sustainability. If you would like to seek to uderstand more about the analysis and the results I encourage you to go through the [Notebook](https://github.com/caiosoter/DS-Projects/blob/main/Appliance_Energy_Prediction/Appliance_energy_prediction.ipynb).

## Project Objective

The main objective of this project was to develop a machine learning model capable of predicting the energy consumption of appliances in a low-energy building. To achieve this goal, we explored and pre-processed the data, performed normality tests, and evaluated the performance of different predictive modeling algorithms.

## Skills and Technologies Involved

* Programming language: Python
* Libraries: Pandas, NumPy, SciPy, Matplotlib, Plotly, Seaborn, Scikit-learn, XGBoost
* Data analysis techniques: Data cleaning, exploratory analysis, feature engineering, feature selection, and predictive modeling.

## Steps Involved

1. Data collection and preparation: The data was loaded from a CSV file and transformed into a suitable format for analysis.
2. Exploratory data analysis: Descriptive statistics and visualizations were used to understand the distributions, relationships, and outliers in the data.
3. Feature engineering: A new variable was created to represent whether a day is a weekend or not, and random variables and columns with high correlation were removed.
4. Predictive modeling: The data was divided into training and testing sets. Linear Regression, Ridge, Lasso, SVR, Random Forest and XGBoost models were trained and evaluated using different data scalers.
5. Model evaluation: The RMSE and R² metrics were used to evaluate the performance of the models and select the best model.

## Most Interesting Analysis

* Normality tests indicated that no variable follows a normal distribution.
* The variables T6 and T_out, which represent the outside temperature, showed high correlation between themselves.
* All temperatures show a significant correlation with each other, with the variable T9 standing out with correlations above 0.9.
* The two random variables are equal and show no correlation with the target variable, being excluded from the model.
* The "lights" variable was excluded because it has more than 77% of the records with value 0.
* The Random Forest model showed the best performance in all data scaling.

## Next Steps

* Increase data collection to improve the predictive model.
* Deploy the predictive model in production to help optimize energy consumption.
* Perform hypothesis testing to assess the statistical significance of other variables.

# References:
- https://www.kaggle.com/datasets/loveall/appliances-energy-prediction
- https://c0.wallpaperflare.com/preview/61/600/874/energy-inspiration-ideas-planet-waters.jpg (Image Link)
- https://towardsdatascience.com/a-practical-introduction-to-the-shapiro-wilk-test-for-normality-5675e52cee8f
- https://towardsdatascience.com/6-ways-to-test-for-a-normal-distribution-which-one-to-use-9dcf47d8fa93
- https://towardsdatascience.com/bayesian-optimization-concept-explained-in-layman-terms-1d2bcdeaf12f
- https://xgboost.readthedocs.io/en/stable/parameter.html
- https://towardsdatascience.com/an-interactive-guide-to-hypothesis-testing-in-python-979f4d62d85
- https://rhydhamgupta.medium.com/p-value-explained-clearly-regression-pdf-discrete-45c30b5dc813

## Additional Information

This project demonstrates the potential of data analysis and machine learning to optimize energy consumption in buildings. The results obtained can be used to create more efficient and sustainable energy use strategies.
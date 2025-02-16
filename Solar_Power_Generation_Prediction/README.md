![](https://www.cronicanorte.es/wp-content/uploads/2017/01/energia-solar-espa%C3%B1a-1024-768x432.jpg)

# Solar Power Generation Prediction

## Problem Summary

The amount of energy consumed has increased dramatically in recent years. As a result, investment in renewable energy has become increasingly important due to concerns about the environment and global warming. This project aims to analyze and predict the generation of solar power plants using a dataset downloaded from Kaggle. If you would like to seek to uderstand more about the analysis and the results I encourage you to go through the [Notebook](https://github.com/caiosoter/DS-Projects/blob/main/Solar_Power_Generation_Prediction/Solar_Power_Prediction.ipynb).

## Project Objectives

The main objective of this project is to develop a model that can accurately predict the generation of solar power plants. This information can be used to optimize energy production and distribution, as well as to make informed decisions about investments in renewable energy.

## Skills and Technologies Involved

* Programming Language: Python
* Data Analysis Techniques: Data cleaning, exploratory data analysis, feature engineering, predictive modeling
* Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Steps Involved

1. Data Collection and Preparation:
    * The dataset was downloaded from Kaggle.
    * The data was cleaned and preprocessed, including handling missing values and converting data types.
2. Exploratory Data Analysis:
    * Descriptive statistics were used to summarize the data.
    * Data distribution was analyzed using histograms and box plots.
    * Correlation between variables was explored using scatter plots and heatmaps.
3. Feature Engineering:
    * New features were created based on the existing data.
    * Feature selection techniques were used to identify the most relevant variables for the model.
4. Predictive Modeling:
    * Several machine learning models were trained and evaluated, including:
        * Linear Regression
        * Random Forest
        * XGBoost
    * The best model was selected based on its performance on the test set.
5. Model Evaluation:
    * The performance of the model was evaluated using metrics such as RMSE and R-squared.
    * The model was fine-tuned to optimize its performance.

## Most Interesting Analysis

* Radiation and Sunshine are the most important predictors of solar power generation.
* There is a strong positive correlation between Radiation and Sunshine.
* The ExtraTreeRegressor model achieved the best performance on the test set, with an RMSE of 819.731 and an R-squared of 0.5349.

## Next Steps

* Collect more data to improve the model's accuracy.
* Explore other machine learning models.
* Deploy the model to production.

# References:
* [Dataset](https://www.kaggle.com/datasets/pythonafroz/solar-powe-generation-data)
* https://www.cronicanorte.es/wp-content/uploads/2017/01/energia-solar-espa%C3%B1a-1024-768x432.jpg (Image Link)
* https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6350423/
* https://machinelearningmastery.com/a-gentle-introduction-to-normality-tests-in-python/
* https://www.researchgate.net/post/How-do-we-know-which-test-to-apply-for-testing-normality
* https://towardsdatascience.com/scale-standardize-or-normalize-with-scikit-learn-6ccc7d176a02
* https://machinelearningmastery.com/standardscaler-and-minmaxscaler-transforms-in-python/?unapproved=692893&moderation-hash=1103f3962e6d3e887e442d79fc5f5185#comment-692893
* https://medium.com/analytics-vidhya/writing-math-equations-in-jupyter-notebook-a-naive-introduction-a5ce87b9a214
* https://k3ybladewielder.medium.com/sele%C3%A7%C3%A3o-de-features-com-recursive-feature-elimination-rfe-5effad69590b

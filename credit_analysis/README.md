![](https://medias.revistaoeste.com/wp-content/uploads/2023/08/FreePix.jpg.webp)

# Default Analysis

## Problem Summary

This project addresses the issue of delinquency in financial institutions, focusing on the creation of a predictive model to assess the credit risk of recurring customers in new credit applications. The analysis is based on customer and transaction data, aiming to optimize decision-making in credit granting. If you would like to seek to uderstand more about the analysis and the results I encourage you to go through the ![Notebook](https://github.com/caiosoter/DS-Projects/blob/main/credit_analysis/analise_inadimplencia.ipynb).

## Project Objective

The main objective of this project is to develop a credit scoring model capable of predicting the probability of customer delinquency in new credit applications. This model will allow financial institutions to assess credit risk more accurately, assisting in the decision to approve or deny credit.

## Skills and Technologies Involved

* **Skills**:
    * Machine Learning
    * Statistics
    * Data Analysis
    * Data Visualization
    * Programming Language: *Python 3.11.10*
* **Techniques**:
    * Data cleaning and preprocessing
    * Exploratory data analysis
    * Feature engineering
    * Feature selection
    * Hyperparameter optimization
    * Model evaluation

## Steps Involved

1. **Data collection and preparation:** The data was loaded from three CSV files, containing customer registration information, credit information, and payment history. Columns were converted to the correct data types and missing values were handled.

2. **Exploratory data analysis:** Descriptive statistics were calculated and analyzed. Distributions of numerical and categorical variables were checked, and outliers were detected. Correlations between variables were calculated and visualized.

3. **Feature engineering:** New variables were created from existing data, such as payment time, total amount paid, and number of transactions per month.

4. **Feature selection:** The most relevant variables for the predictive model were selected using feature importance and recursive feature elimination methods.

5. **Predictive modeling:** The XGBoost model was chosen as the best algorithm for the problem, based on the recall metric. The model's hyperparameters were optimized using Grid Search and cross-validation.

6. **Model evaluation:** The model was evaluated on the test set using the recall metric. The ROC curve was calculated to assess the model's performance at different classification thresholds.

## Most Interesting Analyses

* **Correlations:** Correlation analysis revealed significant relationships between variables, such as the correlation between payment time and delinquency.

* **Relationship between Variables:** Analysis of the relationship between variables showed, for example, that most clients are medium-sized and operate in the service segment.

* **Delinquency over time:** Analysis of delinquency over time revealed an increase in the number of delinquent customers over the months, with a drop in 2020-04.

## Next Steps

* **Improve the predictive model:** The predictive model can be improved with more advanced machine learning techniques, such as deep learning.

* **Test the model with data from different periods and scenarios:** The model can be tested with data from different periods and scenarios to assess its robustness and generalization.

* **Implement the model in a production environment for real-time use:** The model can be implemented in a production environment for real-time use, allowing financial institutions to assess the credit risk of customers in new credit applications in an automated way.

## References

* Articles and books on credit analysis and credit scoring.
* Documentation of the Python libraries used (pandas, numpy, matplotlib, seaborn, statsmodels, scikit-learn, xgboost, joblib, os).

## Additional Information

This project was developed as part of a data analysis challenge on delinquency in banking institutions. The data used in the project was provided by the challenge and includes customer registration information, credit information, and payment history. The predictive model developed in the project can be used by financial institutions to assess the credit risk of customers in new credit applications, assisting in the decision to approve or deny credit.
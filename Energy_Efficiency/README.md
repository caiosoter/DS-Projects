![](https://live.staticflickr.com/5009/5277522498_7646c3b586_z.jpg)

# Energy Efficiency Prediction Project

## Problem Summary
The project addresses the challenge of energy efficiency in buildings, focusing on the relationship between physical parameters of buildings and the energy required to heat and cool them. With the increasing demand for sustainable energy solutions, understanding and predicting energy consumption is crucial for optimizing building designs and reducing energy costs. If you would like to seek to understand more about the analysis and the results I encourage you to go through the [Notebook](https://github.com/caiosoter/DS-Projects/blob/main/Energy_Efficiency/efficiency_prediction.ipynb).

## Project Objective
The primary objective of this project is to build machine learning models that can predict the heating and cooling loads of buildings based on their physical characteristics. By doing so, the project aims to contribute to energy efficiency efforts, helping to design buildings that require less energy for heating and cooling, thereby reducing overall energy consumption.

## Skills and Technologies Involved
* **Programming Language:** Python
* **Data Analysis Techniques:** Data cleaning, exploratory data analysis, feature engineering, predictive modeling
* **Libraries and Tools:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, Statsmodels

## Project Steps
1. **Data Collection and Preparation:**
   - The dataset was obtained from the UCI Machine Learning Repository, containing 768 building shapes with their respective physical parameters and energy loads.
   - Data cleaning and type conversion were performed to ensure the dataset was ready for analysis.

2. **Exploratory Data Analysis (EDA):**
   - Descriptive statistics and distribution analysis were conducted to understand the dataset.
   - Correlation analysis (Spearman) was used to identify relationships between variables.
   - Visualizations such as histograms, boxplots, and scatterplots were created to explore the data.

3. **Feature Selection:**
   - Feature selection techniques, including Recursive Feature Elimination (RFE), were applied to identify the most relevant features for predicting heating and cooling loads.
   - Numerical transformations (MinMax Scaler and Standard Scaler) were applied to normalize the data.

4. **Predictive Modeling:**
   - Multiple machine learning models were trained and evaluated using cross-validation.
   - The best-performing model (XGBoost) was selected and fine-tuned using GridSearchCV.

5. **Model Evaluation:**
   - The models were evaluated based on Root Mean Squared Error (RMSE) and R-squared (R²) metrics.
   - The final models were tested on a separate test set to ensure their generalizability.

## Key Insights and Findings
* **Relative Compactness** was identified as the most important feature for predicting both heating and cooling loads.
* **Overall Height** and **Surface Area** were found to have a significant impact on energy efficiency.
* The **XGBoost** model outperformed other models, achieving high R² values (0.998 for heating load and 0.983 for cooling load) on the test set.
* Buildings with lower surface area and wall area tend to be more energy-efficient.

## Next Steps
* **Model Improvement:** Explore more advanced models or ensemble techniques to further improve prediction accuracy.
* **Data Collection:** Gather more data to enhance the model's ability to generalize across different building types and climates.
* **Deployment:** Implement the model in a real-world scenario, such as a building design tool, to assist architects and engineers in creating energy-efficient buildings.

# References
* [Dataset](https://www.kaggle.com/datasets/ujjwalchowdhury/energy-efficiency-data-set?rvi=1)
* [Useful informations](https://pt.slideshare.net/NitinAgarwal53/exploratory-data-analysis-for-energy-efficiency)
* [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/242/energy+efficiency)
* [Introductory Paper](https://www.sciencedirect.com/science/article/abs/pii/S037877881200151X?via%3Dihub)

## Additional Information
* **Dataset:** The dataset used in this project was constructed by the Center of Machine Learning and Intelligent Systems in Irvine, California. It includes 12 different building shapes simulated in Ecotect, with a total of 768 building shapes.
* **Model:** The final model used for prediction is an XGBoost regressor, fine-tuned using GridSearchCV for optimal performance.
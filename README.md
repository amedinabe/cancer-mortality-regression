# cancer-mortality-regression

Cancer mortality prediction using regression models
The current project aims to analyse different patterns from census data and US counties. The goal is to predict cancer mortality using regression models.

## DATA DESCRIPTION
The dataset contains 33 different features that include demography and medical information. According to the country’s census data, the records describe the different counties in the USA and their characteristics. The variable to be predicted is cancer mortality, measured as the mean per capita (100,000) cancer mortality.

## EXPERIMENT OBJECTIVES
The overall objective of this study is to fit a univariate and multivariate linear regression model using the cancer mortality and demography dataset to predict a given target variable (Mean per capita (100,000) cancer mortalities).
The project is divided into several experiments that allow further exploration to achieve a good enough model accuracy.
During the development of the data exploration and model fit, the expectations are to gain knowledge of the dataset, understand the behaviour of each variable and get insights for the further stages of the project.
The experiments aim to produce a pipeline for data cleaning and exploratory data analysis (EDA) to select potential features that can explain the mean cancer mortality target.

## BEST MODEL SELECTED
According to the score presented, the multivariate linear regression model using state categorical feature was selected as the best model. This model includes all the available variables except those eliminated in the data preparation phase, such as ID and income by decile.

## RESULTS
According to the results obtained and the business objective of the project, the final model results could be used to continue new research that may include additional variables and enrich the current dataset.
The results from the Ridge model and the model without regularisation are similar. It might indicate that more data is needed to achieve better performance, and the difference between the scores is not due to overfitting but to missing key features.
The result also suggests that more complex machine learning models should be implemented to predict mean cancer mortality accurately.

## REFERENCES
Brownlee, J. (2016, May 19). Feature Selection For Machine Learning in Python. MachineLearningMastery.Com. https://machinelearningmastery.com/feature-selection-machine-learning-python/

Brownlee, J. (2019, November 26). How to Choose a Feature Selection Method For Machine Learning. MachineLearningMastery.Com. https://machinelearningmastery.com/feature-selection-with-real-and-categorical-data/

Brownlee, J. (2020, March 30). How to Calculate Feature Importance With Python—MachineLearningMastery.com. https://machinelearningmastery.com/calculate-feature-importance-with-python/

DataCamp. (2020, January 1). Principal Component Analysis (PCA) in Python Tutorial. https://www.datacamp.com/tutorial/principal-component-analysis-in-python

GeeksforGeeks. (2023, March 13). Principal Component Analysis with Python. GeeksforGeeks. https://www.geeksforgeeks.org/principal-component-analysis-with-python/

Gupta, A. (2020, October 10). Feature Selection Techniques in Machine Learning (Updated 2023). https://www.analyticsvidhya.com/blog/2020/10/feature-selection-techniques-in-machine-learning/

Hotz, N. (2018, September 10). What is CRISP DM? Data Science Process Alliance. https://www.datascience-pm.com/crisp-dm-2/

Pandian, S. (2021, April 8). Rapid-Fire EDA process using Python for ML Implementation. Analytics Vidhya. https://www.analyticsvidhya.com/blog/2021/04/rapid-fire-eda-process-using-python-for-ml-implementation/

sklearn. (2023). Sklearn.linear_model.LinearRegression. Scikit-Learn. https://scikit-learn/stable/modules/generated/sklearn.linear_model.LinearRegression.html

So, A. (2023a). Module 2 Lab Solutions: 36106 Machine Learning Algorithms and Applications—Autumn 2023. https://canvas.uts.edu.au/courses/26202/pages/module-2-lab-solutions?module_item_id=1297694

So, A. (2023b). Module 3 Lab Solutions: 36106 Machine Learning Algorithms and Applications—Autumn 2023. https://canvas.uts.edu.au/courses/26202/pages/module-3-lab-solutions?module_item_id=1297696
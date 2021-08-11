# Insurance_Claim_Prediction
- It is a supervised machine learning project based on Kaggle porto-seguro-safe-driver-prediction dataset which is made of 595212 records and 59 features. Dataset provider keeps the dataset confidential. Because of that there is no clear definition for features. In this dataset, each row represents a car insurance policy holder.

- It is a classification machine learning project where the goal is predicting if a driver will file a claim or not.
- This application includes data cleaning, data preparation, explanatory data analysis, and modeling. I have written different functions for repetitive tasks such as plotting. Then, for these tasks, I just call the related functions.
- For machine learning purposes, XGBoost Classifier model is used. As data provider asked, "Gini Index" is used as the business metric. For hyperparameter tuning, low-level API of XGBoost is used.
- Compare to the base model, our optimized model could improve the business metric for more than 36%.

# Files in this Repository:
1) Utils_Car_Insurance: This file includes common functions for actions like data manipulation or data visualization. These functions will be called through other files.
2) Preparation_Car_Insurance: This file includes all the preparation steps for this dataset.
3) EDA_Car_Insurance: This file includes applied steps for the Data Explanatory Analysis.
4) Modeling_Car_Insurance: This file includes machine learning content of the project.

# How to run the project?
To run this project after downloading the dataset, the provided files should be run with the above order.

# Dataset:
The dataset for this project can be download from this link: https://www.kaggle.com/c/porto-seguro-safe-driver-prediction/data


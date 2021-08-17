# Prediction of Insurance Claim:
<ul align="justify">
<li>It is a supervised machine learning project based on Kaggle porto-seguro-safe-driver-prediction dataset which is made of 595212 records and 59 features. Dataset provider keeps the dataset confidential. Because of that there is no clear definition for features. In this dataset, each row represents a car insurance policy holder.</li>
<li>It is a classification machine learning project where the goal is predicting if a driver will file a claim or not.</li>
<li>This application includes data cleaning, data preparation, explanatory data analysis, and modeling.</li>
<li>For machine learning purposes, XGBoost Classifier model is used. As data provider asked, "Gini Index" is used as the business metric. For hyperparameter tuning, low-level API of XGBoost is used.</li>
<li>Compare to the base model, our optimized model could improve the business metric for more than 36%.</li>
</ul>
  
# Files in this Repository:
<ol align="justify">
<li>Utils_Car_Insurance: This file includes common functions for tasks like data manipulation or data visualization. These functions will be called through other files.</li>
<li>Preparation_Car_Insurance: This file includes all the preparation steps for this dataset.</li>
<li>EDA_Car_Insurance: This file includes applied steps for the Data Explanatory Analysis.</li>
<li>Modeling_Car_Insurance: This file includes machine learning content of the project.</li>
</ol>

# How to run the project?
To run this project after downloading the dataset, the provided files should be run with the above order.

# Dataset:
The dataset for this project can be download from this link: https://www.kaggle.com/c/porto-seguro-safe-driver-prediction/data

# More Details:
More details is provided in my personal website at https://www.tednaseri.com/car_insurance

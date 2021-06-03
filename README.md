# TPS5-Kaggle
These are my Jupyter Notebook for the Kaggle Competition: Tabular Playground Series Mai 2021

<b>About the competition:</b>

The dataset is used for this competition is synthetic, but based on a real dataset and generated using a CTGAN. The original dataset deals with predicting the category on an eCommerce product given various attributes about the listing. Although the features are anonymized, they have properties relating to real-world features.

Type: Multiclass Classification

Evaluation Metric: Multiclass Log Loss

<b>My repository contains the following notebooks:</b>
- tps5-eda-raising-more-questions-than-answers.ipyng  --- published on Kaggle, Bronze Medal
    - EDA (Exploratory Data Analysis)
    - “manual” baseline in order to check which score the model must beat
-	tps5-dtandrf-costsenstivelearning.ipynb
    - Decision Tree
    - Random Forest with Cost Sensitive Learning 
    - Hyperparameter tuning wiht GridSearch
-	tps5-xgboost-commented.ipynb --- published on Kaggle, Silver Medal
    - XGBoost
    - Oversampling with SMOTE
    - different experiments with data preprocessing
    - Hyperparameter tuning with GridSearch
-	tps5-ensemblig.ipynb
    - simple ensemble with the predictions from Random Forest and XGBoost
  

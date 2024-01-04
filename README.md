# Credit_Score_Classification

A credit classification model is a tool that is typically used in the decision-making process of determining ones credit score.  
The classification model is the result of a statistical model which, based on information about the borrower (e.g. Monthly Income, Number of Bank accounts/Credit cards, Outstanding debt etc.),   
allows one to distinguish between "good", "standard" and "bad" credit.   
A robust and accurate model can help to predict an individual credibility and eligibility for loans and other financial serives.



# Description

The objective of this project is to construct a multi-class classification model that can effectively forecast credit score categories with precision.

- The project begins by undertaking an Exploratory Data Analysis, which aims to examine and analyze the data in order to gain insights and understand the patterns and characteristics of the variables.

- Proceeding further involves data cleansing, where the objective is to eliminate redundant information, special characters, and NULL values. Additionally, it is essential to substitute any erroneous entries and fill in missing values by analyzing other relevant attributes or generating new data.

- The subsequent stage involves preprocessing the data, which entails transforming it to minimize high variance and skewness. Additionally, the categorical variables are encoded using either one-hot encoding or ordinal encoding technique. 

- The target feature in the dataset exhibits a significant imbalance, which will be addressed in the subsequent phase. During this phase, we will prepare the dataset for modeling by dividing it into training and test sets.

- After completing the data preprocessing phase, the data is now prepared for modeling. Initially, several models are constructed using default parameters in the first stage, and their performance is recorded throughout the model building process.

- During the second stage of the model building process, hyperparameter tuning is conducted to enhance the performance of the model. Randomized search is employed in order to explore different hyperparameter combinations and potentially improve the model's performance. After the tuning process, multiple models demonstrated an improvement ranging from 4% to 6%. Ultimately, the two models that exhibited the best performance were selected and saved. 

# File Structure

```
.
├── credit_score_classification.code-workspace
├── credit_score_classification.ipynb
├── environment.yml
├── final_model_xgb.sav
├── final_model_xtc.sav
├── model_report_scaled.txt
├── model_report_unscaled.txt
├── README.md
├── test.csv
└── train.csv
```
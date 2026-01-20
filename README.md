# -Elevatelab_Task_4


#  Feature Encoding and Scaling

# Project Overview
This project focuses on **feature engineering** techniques applied to the **Adult Income Dataset** to prepare data for machine learning models. The task includes identifying categorical and numerical features, applying appropriate encoding methods, and scaling numerical features to improve model performance.


#  Dataset
- Name: Adult Income Dataset
- Source: UCI Machine Learning Repository
- Target Variable: `income` (<=50K, >50K)


#  Technologies Used
- Python
- Google Colab (Cloud Environment)**
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn


#  Steps Performed

#  1. Data Loading
- Loaded the dataset into Google Colab
- Checked dataset shape and structure
  

# 2. Feature Identification
- Identified **categorical** and **numerical** features
- Handled missing values by removing invalid entries
  

# 3. Feature Encoding
- **Label Encoding** applied to the target variable (`income`)
- **One-Hot Encoding** applied to nominal categorical features


# 4. Feature Scaling
- Applied **StandardScaler** to numerical features
- Transformed features to zero mean and unit variance


# 5. Data Export
- Saved the final processed dataset as `adult_processed.csv`


# Why Encoding and Scaling?
- Encoding converts categorical data into numerical form required by ML algorithms
- Scaling ensures equal contribution of features
- Improves performance of algorithms such as:
  - Logistic Regression
  - Support Vector Machines (SVM)
  - KNN
  - Neural Networks

 # output
 

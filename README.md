Building Insurance Claim Predictions - AINow Bootcamp Capstone project

​Executive Summary
​The aim of this project is to predict the likelihood of insurance claims for various buildings based on their physical characteristics and location. 

​The result: Optimized Random Forest, Logistic Regression and Decision Tree models capable of predicting claims with an ROC-AUC score of 0.718, 0.717 and 0.697 respectively outperforming baseline models.

​Key Insights and Findings
​Top Risk Factor: From the results gotten after the analysis, Building Dimension is the most significant predictor. Larger buildings show a much higher frequency of claims.

​Model Performance:  Random Forest: 0.718 AUC (Best model)
​Logistic Regression: 0.717 AUC
​Decision Tree: 0.697 AUC

​Tech Stack
​Language: Python 3.x
​Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
​Techniques: Hyperparameter Tuning (GridSearchCV), Cross-Validation, Data Imputation, Feature Encoding.

​Methodology
​Exploratory Data Analysis (EDA): Identified class imbalance and handled missing data in dimensions and occupancy dates.

​Preprocessing: Cleaned the NumberOfWindows column and three other columns with missing values, encoded categorical variables, and applied median and mode imputation to maintain the integrity of the data.

​Model Tuning: Tested 3 algorithms using GridSearchCV.

​Evaluation: Used ROC Curves and Feature Importance plots to validate the reliability of the models and explain the predictions.

​Project Structure
​HLA_FinalCaP.html: The final interactive report with graphs.
​HLA_FinalCaP.ipynb: The complete source code and processing steps.
​Train_data.csv: The dataset used for training and testing.
Variable Description.csv: Spreadsheet with details about each column.

# AINow-Bootcamp-Capstone-Project

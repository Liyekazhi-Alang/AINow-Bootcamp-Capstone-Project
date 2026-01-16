**Building Insurance Claim Predictions - AINow Bootcamp Capstone project**

**​Executive Summary**

​The aim of this project is to predict the likelihood of insurance claims for various buildings based on their physical characteristics and location. 

**​The result:** Optimized _Random Forest, Logistic Regression and Decision Tree_ models capable of predicting claims with an ROC-AUC score of **0.718, 0.717 and 0.697** respectively outperforming baseline models.

**​Key Insights and Findings**

*​ _Top Risk Factor_: From the results gotten after the analysis, Building Dimension is the most significant predictor. Larger buildings show a much higher frequency of claims.

*​ _Model Performance_:  Random Forest: 0.718 AUC (Best model)
​Logistic Regression: 0.717 AUC
​Decision Tree: 0.697 AUC

**​Tech Stack**

* ​Language: Python 3.x
* ​Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* ​Techniques: Hyperparameter Tuning (GridSearchCV), Cross-Validation, Data Imputation, Feature Encoding.

**​Methodology**

* _Exploratory Data Analysis (EDA)_: Identified class imbalance and handled missing data in dimensions and occupancy dates.

* _​Preprocessing_: Cleaned the NumberOfWindows column and three other columns with missing values, encoded categorical variables, and applied median and mode imputation to maintain the integrity of the data.

* _​Model Tuning_: Tested 3 algorithms using GridSearchCV.

* _​Evaluation_: Used ROC Curves and Feature Importance plots to validate the reliability of the models and explain the predictions.

**​Project Structure**

* _​HLA_FinalCaP.html_: The final interactive report with graphs.
* _​HLA_FinalCaP.ipynb_: The complete source code and processing steps.
* _​Train_data.csv_: The dataset used for training and testing.
Variable Description.csv: Spreadsheet with details about each column.

# AINow-Bootcamp-Capstone-Project

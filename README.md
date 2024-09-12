## Machine Learning Project: Salary Prediction for Techworks Consultant 
#### Overview
This project aims to predict the salaries of newly hired employees using a dataset with features like college, city, previous CTC, job role, and more. Various machine learning models were explored to optimize predictions and determine which factors had the most impact on salary determination.

#### Libraries Used
Numpy: For numerical operations.

Pandas: For data manipulation and analysis.

Seaborn: For data visualization.

Statsmodels: For statistical modeling.

Scikit-learn: For machine learning model creation and evaluation.

#### Dataset Description
ML Case Study.csv: Main dataset containing employee details.

Colleges.csv: Contains information about different college tiers.

Cities.csv: Categorizes cities into metro and non-metro areas.

#### Key Features
College: Categorized into Tier 1, Tier 2, and Tier 3.

City: Categorized into metro and non-metro cities.

Role: One-hot encoded to handle categorical data.

CTC (Target Variable): The salary of newly hired employees, which we aim to predict.

#### Data Preprocessing
Categorization: College and city data were categorized and replaced with numerical values (1, 2, 3 for colleges; 1 for metro, 0 for non-metro cities).

Dummy Variables: Created for the 'Role' column.

Missing Values: None found.

Outliers: Checked via visualizations using seaborn.

#### Models Implemented

Multiple Linear Regression

Random Forest Regressor

Decision Tree Regressor

Gradient Boosting Machine (GBM) Regressor

XGBoost Regressor

Ridge Regression

Lasso Regression

Model Evaluation

Each model was evaluated using Mean Squared Error (MSE) and R-Squared (R2) scores.

#### Model	R2 Score

Linear Regression	0.5343

Random Forest Regressor	0.6582

Decision Tree Regressor	0.5928

Gradient Boosting Machine	0.6327

XGBoost	0.6449

Ridge Regression	0.5356

Lasso Regression	0.5356

#### Best Model: Random Forest Regressor

The Random Forest Regressor outperformed other models with the highest R2 score of 0.6582.

#### Improvements for Future Work

Gather More Data: To improve generalization.

Hyperparameter Tuning: To further optimize model performance.

Feature Engineering: Additional feature creation and analysis to boost predictive accuracy.

Ensemble Methods: Combining multiple models to enhance performance.

#### How to Run

1. Ensure you have Python 3.x installed.
 
2. Install the required libraries using: "pip install numpy pandas seaborn statsmodels scikit-learn"
  
3. Load the datasets by placing them in the appropriate file paths.
 
4. Execute the notebook to preprocess the data, train the models, and evaluate performance.


## Contact

##### For questions or contributions, feel free to reach out.


# Amna-Kauser-TASK---2-Data-Science-and-Analytics-
Data Science and Analytics Internship Tasks

## Task 2: Credit Risk Predict

### Objective
Predict which customers are likely to default on their 
loan based on financial and personal data.

### Approach
- Loaded the Loan Default dataset
- Visualized key features:
  - Loan Amount Distribution
  - Default vs Non-Default count
  - Education vs Default
  - Income vs Default
- Encoded categorical features (Education, EmploymentType, 
  MaritalStatus, HasMortgage, HasDependents, LoanPurpose, HasCoSigner)
- Trained a Decision Tree classifier (max_depth=3)
- Evaluated using Confusion Matrix and Accuracy Score

### Results and Insights
- Model Accuracy: 88.48%
- Dataset is imbalanced — 225,000 non-defaulters vs 30,000 defaulters
- Model predicted "No Default" for every customer — 
  completely missed all actual defaulters
- Income is a useful predictor — lower income customers 
  are more likely to default
- Education level has almost no effect on default
- Loan amounts are uniformly distributed from $0 to $250,000

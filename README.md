# Data Science Internship – Task 1

## Task 1: Exploring and Visualizing the Iris Dataset

**Objective:**  
Understand the structure of the Iris dataset and visualize features to gain insights.

**Dataset:**  
Iris Dataset (available in seaborn or CSV format)  
Contains 150 samples with 4 features (sepal length, sepal width, petal length, petal width) and species labels.

**Approach:**  
1. Loaded the dataset using `pandas`.  
2. Explored dataset structure with `.shape`, `.columns`, and `.head()`.  
3. Visualized the data using:  
   - Scatter plots (pairplot)  
   - Histograms  
   - Box plots  
4. Checked for missing values and summarized statistics.

**Results / Insights:**  
- Scatter plots show separation between species for petal features.  
- Histograms indicate feature distributions.  
- Box plots help identify potential outliers.  
- Dataset has no missing values.

**Tools Used:**  
- Python  
- Pandas  
- Matplotlib  
- Seaborn

**GitHub Link:**  
https://github.com/alimurtaza9dev-ctrl/DataScienceInternship2026_Task1/blob/main/Task1_Iris.ipynb


## Task 2: Credit Risk Prediction

### Objective
Predict whether a loan applicant is likely to default on a loan using machine learning.

### Dataset
Loan Prediction Dataset (loan_data.csv) – includes information like Gender, Married, Dependents, Education, ApplicantIncome, LoanAmount, Credit_History, etc.

### Approach
- Loaded dataset using pandas
- Handled missing values (LoanAmount, Dependents, Self_Employed)
- Converted categorical columns to numeric using Label Encoding
- Dropped Loan_ID column (not needed for prediction)
- Split dataset into training and testing sets
- Trained Logistic Regression model
- Made predictions on test data

### Model Evaluation
- **Accuracy**: Checked using `accuracy_score`
- **Confusion Matrix**: Showed correct/incorrect predictions

### Insights
- Credit History, Education, ApplicantIncome, and LoanAmount are important factors
- The model can help banks decide whether to approve loans

 **GitHub Link:**
  http://github.com/alimurtaza9dev-ctrl/data-science-internship/blob/main/Task2_CreditRisk.ipynb


## Task 3: Customer Churn Prediction (Bank Customers)

### Objective
Predict which bank customers are likely to leave the bank (customer churn) using machine learning techniques.

### Dataset
Churn Modelling Dataset (churn.csv)

The dataset contains customer information such as:
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Credit Card ownership
- Active member status
- Estimated Salary
- Exited (target variable indicating churn)

### Approach
- Loaded dataset using pandas
- Removed unnecessary columns (RowNumber, CustomerId, Surname)
- Checked for missing values
- Converted categorical features (Gender, Geography) into numeric form using Label Encoding
- Split dataset into training and testing sets
- Trained Decision Tree classification model
- Predicted customer churn on test dataset
- Analyzed feature importance to identify key factors affecting churn

### Model Evaluation
- Accuracy score used to measure model performance
- Confusion matrix used to evaluate correct and incorrect predictions
- Feature importance used to understand which variables most influence churn

### Insights
- Age, Balance, Geography, and Credit Score significantly influence customer churn
- Customers with higher balances and certain demographics show higher probability of leaving
- Model helps banks identify customers at risk of leaving and take preventive actions

**GitHub Link:**

https://github.com/alimurtaza9dev-ctrl/DataScienceInternship2026_Task1/blob/main/Task3_Churn.ipynb

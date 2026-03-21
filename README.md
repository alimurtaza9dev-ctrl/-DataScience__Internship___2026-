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

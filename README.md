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


## Task 4: Insurance Cost Prediction

Objective:
Predict medical insurance charges using Linear Regression.

Steps:
- Encoded categorical features
- Split dataset into training and testing sets
- Applied Linear Regression model
- Evaluated performance using MAE, MSE, R2 score

Result:
Model predicts insurance charges based on age, BMI, smoking habits, and region.

**GitHub Link:**

 https://github.com/alimurtaza9dev-ctrl/-DataScience__Internship___2026-/blob/main/Task4_Insurance.ipynb


## Task 5: Personal Loan Acceptance Prediction

**Objective:**  
Predict which customers are likely to accept a personal loan offer using customer data.

**Dataset:**  
Bank Marketing / Loan Prediction dataset (CSV format)

**Steps Performed:**  
1. Explored dataset and checked missing values.  
2. Handled missing data by filling with mean/mode for numerical/categorical features.  
3. Encoded categorical features (Gender, Married, Education, Self_Employed, Property_Area) using Label Encoding.  
4. Split dataset into training and testing sets (80%-20%).  
5. Trained a classification model using **Random Forest Classifier**.  
6. Made predictions on the test set.  
7. Evaluated model performance using **accuracy score**.

**Results:**  
- The model predicts which customers are more likely to accept a personal loan offer.  
- Achieved accuracy: ~75–85% (may vary depending on dataset and preprocessing).  

**Key Insights:**  
- Customer income, credit history, and education play a significant role in loan acceptance.  
- Random Forest helps capture non-linear relationships better than simple Logistic Regression.  

**Tools & Libraries Used:**  
- Python  
- pandas, numpy  
- scikit-learn  
- Jupyter Notebook

**GitHub Link:**
https://github.com/alimurtaza9dev-ctrl/-DataScience__Internship___2026-/blob/main/Task5_Loan.ipynb
## Advanced Task 6: Term Deposit Subscription Prediction

**Objective:** Predict whether a customer will subscribe to a term deposit after a marketing campaign.

**Approach:**
- Explored dataset and encoded categorical features
- Trained Logistic Regression and Random Forest models
- Evaluated models using Confusion Matrix, F1 Score, and ROC Curve
- Explained top 5 predictions using SHAP for model interpretability

**Results:**
- Random Forest performed slightly better than Logistic Regression
- Key influential features: `duration`, `poutcome`, `balance`, `campaign`, `age`

**Tools Used:** Python, pandas, numpy, scikit-learn, matplotlib, seaborn, shap



**GitHub Link:**

https://github.com/alimurtaza9dev-ctrl/-DataScience__Internship___2026-/blob/main/Task6_TermDeposit.ipynb


## Advanced Task 7: Customer Segmentation using Unsupervised Learning

### Objective
Segment customers into different groups based on their purchasing behavior and income level. The goal is to help businesses understand customer patterns and design targeted marketing strategies.

### Dataset
Mall Customers Dataset

The dataset contains customer demographic and spending information:
- Age
- Annual Income (k$)
- Spending Score (1-100)
- Gender
- CustomerID

### Approach

1. Data Exploration
- Loaded dataset using pandas
- Checked structure, column types, and summary statistics

2. Feature Selection
Selected important numerical features:
- Age
- Annual Income
- Spending Score

3. Data Preprocessing
- Applied StandardScaler to normalize data
- Prepared dataset for clustering

4. Model Building – K-Means Clustering
- Used Elbow Method to determine optimal number of clusters
- Applied K-Means algorithm to group customers into segments

5. Dimensionality Reduction
- Used PCA (Principal Component Analysis) to visualize clusters in 2D space

6. Visualization
- Scatter plots created to display customer segments
- Identified clear cluster separation

### Results & Insights

The model grouped customers into 5 distinct segments:

Cluster examples:
- High income, high spending customers → premium target group
- Low income, low spending customers → discount-focused group
- Medium income, high spending customers → marketing opportunity
- High income, low spending customers → potential growth segment

### Business Value

Customer segmentation helps businesses:
- improve targeted marketing
- personalize promotions
- increase customer satisfaction
- improve sales performance

### Tools & Libraries Used
- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

### Conclusion

K-Means clustering successfully identified meaningful customer groups. Businesses can use these insights to develop more effective marketing strategies and improve decision-making.

**GitHub Link:**

https://github.com/alimurtaza9dev-ctrl/-DataScience__Internship___2026-/blob/main/Task7_CustomerSegmentation.ipynb

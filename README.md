Employee Attrition Prediction Using Logistic Regression

 Project Overview

Employee attrition is a major challenge faced by organizations as it leads to increased recruitment costs, training expenses, and productivity loss. This project uses Machine Learning to predict whether an employee is likely to leave the company based on employee information, work experience, job satisfaction, and other related factors.

The model is built using Logistic Regression and helps organizations identify employees who are at risk of leaving and improve retention strategies.

Dataset Link:
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

Problem Statement

Predict whether an employee will leave the company or continue working using historical employee data.

Target Variable:

*Attrition

Classes:

* Yes (Employee will leave)
* No (Employee will stay)

---

Dataset

Dataset: IBM HR Analytics Employee Attrition Dataset

Features include:

* Age
* Gender
* Department
* Job Role
* Education
* Marital Status
* Monthly Income
* Job Satisfaction
* Environment Satisfaction
* Work Life Balance
* Overtime
* Years at Company
* Years in Current Role
* Training Times Last Year
* Distance From Home
* Business Travel

Target:

* Attrition

---

Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Logistic Regression
* Joblib
* Jupyter Notebook

---

Project Workflow

1. Data Collection

Loaded the IBM HR Analytics Employee Attrition dataset.

2. Data Preprocessing

* Handled missing values
* Removed unnecessary columns
* Converted categorical variables into numerical format
* Prepared features and target variable

3. Feature Engineering

* Label Encoding
* Data Transformation

4. Model Building

* Train-Test Split
* Logistic Regression Model Training

5. Model Evaluation

* Accuracy Score
* Confusion Matrix
* Classification Report

6. Model Deployment Preparation

* Saved trained model using Joblib
* Loaded saved model for future predictions

---

Model Performance

Evaluation Metrics:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

Project Structure

employee-attrition-prediction/

├── Employee_Attrition.ipynb

├── WA_Fn-UseC_-HR-Employee-Attrition.csv

├── README.md



---

Installation

```bash
pip install pandas numpy scikit-learn joblib
```

## Run Project

```bash
jupyter notebook
```

Open:

```text
Employee_Attrition.ipynb
```

Run all cells sequentially.

---

Business Impact

The model helps organizations:

* Identify employees likely to leave
* Improve employee retention
* Reduce hiring and training costs
* Increase workforce stability
* Support data-driven HR decisions

---

Author

Suman k project:Employee Attrition Prediction Using Logistic Regression

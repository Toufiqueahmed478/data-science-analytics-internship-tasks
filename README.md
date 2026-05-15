# Data Science & Analytics Internship Tasks

This repository contains completed tasks for the **Data Science & Analytics Internship** at DevelopersHub Corporation.

The assignment required completing at least **3 out of 5 tasks**. In this repository, the following three tasks have been completed:

1. Task 1: Exploring and Visualizing a Simple Dataset
2. Task 2: Credit Risk Prediction
3. Task 3: Customer Churn Prediction

Each task is completed in a separate Jupyter Notebook using Python and common data science libraries.

---

## Tools and Libraries Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Task 1: Exploring and Visualizing a Simple Dataset

### Objective

The objective of this task was to understand how to load, summarize, and visualize a simple dataset.

### Dataset

The **Iris dataset** was used for this task. It contains measurements of iris flowers, including sepal length, sepal width, petal length, petal width, and species.

### Work Completed

- Loaded the Iris dataset using Python.
- Displayed the dataset structure using `.shape`, `.columns`, and `.head()`.
- Checked basic statistical summary of the dataset.
- Checked for missing values.
- Created visualizations using matplotlib and seaborn.

### Visualizations

- Scatter plot to analyze relationships between variables.
- Histogram to examine data distribution.
- Box plot to check data spread and possible outliers.

### Key Insight

The Iris dataset is clean and easy to understand. The visualizations showed clear differences between flower species, especially using petal-related features.

---

## Task 2: Credit Risk Prediction

### Objective

The objective of this task was to predict whether a loan applicant is likely to get loan approval or not using classification techniques.

### Dataset

The **Loan Prediction dataset** was used for this task. It contains information about loan applicants, such as income, education, loan amount, credit history, and loan status.

### Work Completed

- Loaded and explored the loan dataset.
- Handled missing values appropriately.
- Visualized important features such as loan amount, education, and applicant income.
- Encoded categorical variables for machine learning.
- Trained a classification model.
- Evaluated the model using accuracy and confusion matrix.

### Model Used

- Decision Tree Classifier

### Evaluation Metrics

- Accuracy score
- Confusion matrix
- Classification report

### Key Insight

Credit history and applicant-related financial information play an important role in predicting loan approval. The model was able to learn useful patterns from the dataset.

---

## Task 3: Customer Churn Prediction

### Objective

The objective of this task was to identify bank customers who are likely to leave the bank.

### Dataset

The **Bank Customer Churn dataset** was used for this task. It contains customer information such as credit score, geography, gender, age, balance, number of products, and churn status.

### Work Completed

- Loaded and explored the churn dataset.
- Removed unnecessary columns.
- Checked and handled missing values.
- Encoded categorical features such as Geography and Gender.
- Trained a classification model.
- Evaluated the model performance.
- Analyzed feature importance to understand factors that influence churn.

### Model Used

- Decision Tree Classifier

### Evaluation Metrics

- Accuracy score
- Confusion matrix
- Classification report
- Feature importance analysis

### Key Insight

Customer attributes such as age, balance, number of products, and activity status can influence whether a customer leaves the bank or stays.

---

## Repository Structure

```text
Data-Science-Analytics-Internship-Tasks/
│
├── task1_iris_dataset_analysis.ipynb
├── task2_credit_risk_prediction.ipynb
├── task3_customer_churn_prediction.ipynb
├── README.md
├── README_Task1.md
├── README_Task2.md
└── README_Task3.md
```

---

## How to Run the Notebooks

1. Open Google Colab.
2. Upload the required `.ipynb` notebook file.
3. Run the notebook cells one by one from top to bottom.
4. Check the outputs, graphs, model results, and conclusions.

---

## Conclusion

These tasks helped practice important data science skills such as data loading, cleaning, exploratory data analysis, visualization, encoding categorical data, classification model training, model evaluation, and feature importance analysis.

The completed tasks provide beginner-friendly hands-on experience with Python-based data science workflows.

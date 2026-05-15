# Task 2: Credit Risk Prediction

## Objective
The objective of this task is to predict whether a loan applicant is likely to get loan approval using applicant information.

## Dataset
The Loan Prediction dataset was used for this task. It contains applicant details such as gender, marital status, education, applicant income, co-applicant income, loan amount, loan term, credit history, property area, and loan status.

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Approach
First, the dataset was loaded using pandas. Then, the structure of the dataset was checked using shape, columns, info, and summary statistics.

Missing values were handled by using median values for numerical columns and mode values for categorical columns. The Loan_ID column was removed because it is only an identifier and does not help in prediction.

After data cleaning, exploratory data analysis was performed using graphs. Important features such as loan amount, education, applicant income, and credit history were visualized.

Categorical variables were encoded into numerical values using Label Encoding. After that, the dataset was split into training and testing sets.

A Decision Tree Classifier was trained to predict the loan status. The model was evaluated using accuracy, confusion matrix, and classification report.

## Visualizations Created
- Loan status count plot
- Loan amount distribution plot
- Education vs loan status count plot
- Applicant income vs loan status box plot
- Credit history vs loan status count plot
- Feature importance plot

## Model Used
Decision Tree Classifier

## Evaluation Metrics
- Accuracy
- Confusion Matrix
- Classification Report

## Key Insights
Credit history is usually one of the most important factors in loan approval prediction. Applicants with a good credit history have a higher chance of loan approval. Loan amount, income, and education also provide useful information for prediction.

## Conclusion
This task helped in understanding data cleaning, exploratory data analysis, classification model training, and model evaluation. It also showed how machine learning can be used in financial decision-making problems such as loan approval prediction.

# Task 3: Customer Churn Prediction

## Objective
The objective of this task is to identify bank customers who are likely to leave the bank.

## Dataset
The Churn Modelling dataset was used for this task. It contains information about bank customers, including credit score, geography, gender, age, tenure, balance, number of products, credit card status, active membership, estimated salary, and churn status.

The target column is `Exited`.

- `0` means the customer stayed.
- `1` means the customer left the bank.

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Approach
First, the dataset was loaded and inspected using pandas. Unnecessary identifier columns such as `RowNumber`, `CustomerId`, and `Surname` were removed because they do not help in prediction.

Then, exploratory data analysis was performed using graphs. Churn patterns were analyzed based on geography, gender, age, and balance.

Categorical features such as `Geography` and `Gender` were encoded into numeric form using Label Encoding. After that, the dataset was split into training and testing data.

A Decision Tree Classifier was trained to predict customer churn.

## Visualizations Created
- Customer churn count plot
- Churn by geography
- Churn by gender
- Age distribution by churn status
- Balance box plot by churn status
- Feature importance graph

## Model Used
Decision Tree Classifier

## Evaluation Metrics
The model was evaluated using:

- Accuracy
- Confusion Matrix
- Classification Report

## Key Insights
The model helps predict whether a customer may leave the bank. Feature importance analysis shows which factors influence customer churn more strongly. Features such as age, number of products, balance, and active membership may play an important role in churn prediction.

## Conclusion
This task helped in understanding data cleaning, categorical encoding, classification model training, model evaluation, and feature importance analysis. It also showed how data science can help banks identify customers who may leave and take action to retain them.

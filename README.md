# Fraud-detection-in-financial-transactions


## Problem statement:
Financial institutions face significant losses due to fraudulent transactions, which negatively impact profitability and customer trust. Existing fraud detection systems often struggle to identify new and sophisticated fraud patterns, resulting in delayed detection and increased financial damage. These financial institutions are seeking a means to develop and implement an advanced fraud detection system, utilizing machine learning techniques to accurately identify and prevent fraudulent transactions in real-time, thereby minimizing financial losses and enhancing customer trust. The system should leverage a variety of data sources, including transaction history, customer behavior, and external data, to improve detection accuracy and reduce false positives.

## Project goal:
Build a machine learning model to identify fraudulent transactions from a dataset, and visualize the results in a Power BI dashboard.

### Tools 
- Excel:  For quickly opening  the CSV file and getting a sense of the data
  
- Jupyter Notebook: For interactive coding and documentation.
  
- Power BI: For creating the interactive dashboard.


## Dataset

The synthetic fraud data used in this project can be downloaded from the link below:  
📄 **[Download synthetic_fraud_data.csv](https://github.com/CelesNeba/Fraud-detection-in-financial-transactions/blob/main/synthetic_fraud_data.csv)**

> Click the **Raw** button on GitHub to download the CSV file directly.

### Data cleaning
- Handle missing values

![](https://github.com/CelesNeba/Fraud-detection-in-financial-transactions/blob/main/Fraud_data_missing_value_screenshot.PNG)


- Correct data types

![](https://github.com/CelesNeba/Fraud-detection-in-financial-transactions/blob/main/correct%20data%20types%20screenshot.PNG)


- Data standardization

![](https://github.com/CelesNeba/Fraud-detection-in-financial-transactions/blob/main/Data%20standardization%20screenshot.PNG)


- Handle outliers

- Remove duplicate rows

- Data standardization



### Data exploration and preprocessing

1. Descriptive statistics:

- Goal: Get a summary of the numerical features in the dataset.

2. Class distribution analysis:

- Goal: Understand the imbalance between the two classes (fraudulent and non-fraudulent transactions).

3. Correlation analysis

- Goal: Identify relationships between features.

4. Data splitting

- Goal: Divide the data into training and testing sets.

5. Handle class imbalance (SMOTE)

- Goal: Address the class imbalance in the training data.




### Model training and evaluation

1. Model selection

- Goal: Choose an appropriate machine learning model for fraud detection.

2. Model training

- Goal: Train the selected model on the resampled training data (the data after applying SMOTE).

3. Model prediction

- Goal: Use the trained model to make predictions on the test data.

4. Model evaluation

- Goal: Assess the performance of the model on the test data.


### Outcome from the model.

The fraud detection model, while showing 98% accuracy, fails to identify any fraudulent transactions, indicated by 0% precision and recall for the fraudulent class and a near-random AUC-ROC score; therefore, the model is currently ineffective and requires further investigation into data preprocessing, feature selection, model selection, and hyperparameter tuning to improve its fraud detection capability.



## Power BI dashboard visualization.







   


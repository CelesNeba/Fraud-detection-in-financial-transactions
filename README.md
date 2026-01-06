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

https://github.com/CelesNeba/Fraud-detection-in-financial-transactions/blob/main/Handle%20outliers%20screenshot.PNG

- Remove duplicate rows

![](https://github.com/CelesNeba/Fraud-detection-in-financial-transactions/blob/main/Removing%20duplicate%20rows%20screenshot.PNG)




### Data exploration and preprocessing

1. Descriptive statistics:

- Goal: Get a summary of the numerical features in the dataset.

![](https://github.com/CelesNeba/Fraud-detection-in-financial-transactions/blob/main/Descriptive%20Statistics%20screenshot.PNG)


2. Class distribution analysis:

- Goal: Understand the imbalance between the two classes (fraudulent and non-fraudulent transactions).

![](https://github.com/CelesNeba/Fraud-detection-in-financial-transactions/blob/main/class%20distribution%20analysis%20screenshot.PNG)


3. Correlation analysis

- Goal: Identify relationships between features.

![](https://github.com/CelesNeba/Fraud-detection-in-financial-transactions/blob/main/Correlation%20analysis.PNG)


4. Data splitting

- Goal: Divide the data into training and testing sets.

![](https://github.com/CelesNeba/Fraud-detection-in-financial-transactions/blob/main/Data%20Splitting%20screenshot.PNG)


5. Handle class imbalance (SMOTE)

- Goal: Address the class imbalance in the training data.


![](https://github.com/CelesNeba/Fraud-detection-in-financial-transactions/blob/main/Handle%20class%20imbalance%20screenshot.PNG)





### Model training and evaluation

1. Model selection

- Goal: Choose an appropriate machine learning model for fraud detection.

2. Model training

- Goal: Train the selected model on the resampled training data (the data after applying SMOTE).

![](https://github.com/CelesNeba/Fraud-detection-in-financial-transactions/blob/main/Model%20trainning%20screenshot.PNG)


3. Model prediction

- Goal: Use the trained model to make predictions on the test data.

![](https://github.com/CelesNeba/Fraud-detection-in-financial-transactions/blob/main/Model%20prediction%20screenshot.PNG)


4. Model evaluation

- Goal: Assess the performance of the model on the test data.

![](https://github.com/CelesNeba/Fraud-detection-in-financial-transactions/blob/main/Model%20Evaluation%20screenshot1.PNG)



![](https://github.com/CelesNeba/Fraud-detection-in-financial-transactions/blob/main/Model%20eveluation%20screenshot2.PNG)




### Outcome from the model.

The fraud detection model, while showing 98% accuracy, fails to identify any fraudulent transactions, indicated by 0% precision and recall for the fraudulent class and a near-random AUC-ROC score; therefore, the model is currently ineffective and requires further investigation into data preprocessing, feature selection, model selection, and hyperparameter tuning to improve its fraud detection capability.



## Power BI dashboard visualization.


## 📊 Fraud Detection Dashboard

This screenshot shows the **Fraud Detection Dashboard** for analyzing financial transactions, designed to provide a comprehensive overview of both the dataset and the model performance in detecting fraud.

[![Fraud Detection Dashboard](https://github.com/CelesNeba/Fraud-detection-in-financial-transactions/blob/main/fraud%20detection%20dashboard1.PNG)](https://github.com/CelesNeba/Fraud-detection-in-financial-transactions/blob/main/fraud%20detection%20dashboard1.PNG)

### 🔍 Dashboard Components

1. **Total Transactions Card** – Displays the total number of transactions in the dataset.  
2. **Total Fraudulent Transactions Card** – Shows the total number of transactions labeled as fraudulent (Class = 1).  
3. **Fraud Rate Card** – Calculates and displays the percentage of transactions that are fraudulent.  
4. **Total Fraudulent Transactions per Class Bar Chart** – Compares the number of transactions for each class (0 = non-fraud, 1 = fraud), highlighting the class imbalance.  
5. **Model Performance Matrix (Confusion Matrix)** – Visualizes how well the fraud detection model performs by showing True Positives, True Negatives, False Positives, and False Negatives.  
6. **Distribution of Fraud Amount Bar Chart** – Displays the distribution of transaction amounts for fraudulent transactions using bins, helping identify typical fraud amounts and outliers.

### 🎯 Purpose

This dashboard allows analysts and stakeholders to:  

- Quickly understand the size and balance of the dataset  
- Identify patterns in fraudulent transaction amounts  
- Evaluate the performance of the fraud detection model  
- Spot areas where the model may fail, such as undetected fraud  

> The combination of summary cards, bar charts, and the confusion matrix provides both **high-level insights** and **detailed analysis**, making it easier to interpret and improve the fraud detection process.



# Fraud-detection-in-financial-transactions
A machine learning project that detects fraudulent financial transactions using Python and visualizes insights with Power BI.

### Problem statement

Financial institutions process millions of transactions daily, making manual fraud detection impractical.
This project builds a machine learning model to identify fraudulent transactions while handling severe class imbalance and minimizing missed fraud cases.


### Dataset

- Synthetic financial transaction data (2,000 rows)

- Includes:

* Transaction details (amount, time, type, merchant category)

* Customer attributes (age)

* Fraud labels

* Highly imbalanced dataset (fraud is a minority class)

### Tools & technologies

* Python (Pandas, NumPy)

* Scikit-learn

* Imbalanced-learn (SMOTE)

* Jupyter Notebook

* Power BI

### ⚙️ Machine learning workflow

1. Data cleaning and type conversions

2. Feature engineering (time-based features, encoding)

3. Class distribution analysis

4. Train-test split (before SMOTE)

5. Class imbalance handling using SMOTE

6. Random Forest model training

7. Probability-based fraud prediction (custom threshold)

8. Model evaluation (precision, recall, confusion matrix)

9. Export results for Power BI visualization

## 📈 Power BI dashboard visualizations 

* Total transactions
* Actual fraud count
* Sum of predicted fraud
* Fraud rate (%)
* Actual vs predicted fraud transactions
* Fraud vs non-fraud transactions
* Fraud by transaction type
* Fraud by merchant category
* Fraud by age group
* Fraud probability distribution


## ▶️ How to run the project

1️⃣ Install dependencies

pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn jupyter

2️⃣ Open the notebook
notebooks/fraud_detection_notebook.ipynb

3️⃣ Run all cells sequentially


📁 Project Structure
fraud-detection-project/
├─ notebooks/      # Jupyter notebooks
├─ data/           # CSV datasets
├─ dashboard/      # Power BI files
└─ .gitignore


🧠 Key  outcomes

* Handling imbalanced datasets correctly

* Applying probability thresholds for fraud detection

* Translating ML results into business dashboards

* End-to-end analytics project workflow

### 📌 Future improvements

* Hyperparameter tuning

* Cost-sensitive learning

* Real-time fraud scoring simulation








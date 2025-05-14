# Customer Churn Prediction

This project predicts whether a customer will churn (leave the service) based on customer data such as account details, services, and usage.

## 📌 Objective
The goal of this project is to use machine learning to classify customers as "churned" or "not churned" based on their attributes.

### 🔍 Dataset
- **Source**: [Telco Customer Churn Dataset - Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Description**: The dataset contains customer information such as tenure, contract type, payment method, and services they have subscribed to.

### 🛠️ Tools & Techniques
- **Libraries Used**:
  - `pandas`, `numpy` for data manipulation
  - `seaborn`, `matplotlib` for data visualization
  - `scikit-learn` for model building and evaluation
- **Models**:
  - Logistic Regression
  - Random Forest Classifier
- **Evaluation Metrics**:
  - ROC-AUC
  - Classification Report (Precision, Recall, F1-score)

### 📊 Results
- Logistic Regression and Random Forest models will be evaluated on the test set with metrics like **accuracy**, **precision**, **recall**, and **ROC-AUC**.

### 💻 Requirements

Install the necessary dependencies with:

```bash
pip install -r requirements.txt

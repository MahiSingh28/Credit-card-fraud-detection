# 🛡️ Credit Card Fraud Detection

This repository contains a machine learning project focused on detecting fraudulent credit card transactions using various classification techniques. The dataset is highly imbalanced, and special attention is given to handling class imbalance, model evaluation, and performance optimization.

## 📁 Project Structure

* `credit_card_fraud_detection.ipynb`: Jupyter notebook with the full workflow including data loading, preprocessing, modeling, and evaluation.
* `README.md`: Project overview, setup instructions, and documentation (this file).

## 📊 Dataset

The dataset used contains anonymized features of credit card transactions and a binary label indicating fraud (`1`) or not (`0`). It includes:

* 284,807 transactions
* 492 fraud cases (approximately 0.172%)

> **Note**: This dataset is originally from a [Kaggle competition](https://www.kaggle.com/mlg-ulb/creditcardfraud).

## ⚙️ Features of the Project

* **Data Preprocessing**:

  * Handling missing values
  * Normalization of features
  * Splitting data into train/test sets

* **Dealing with Class Imbalance**:

  * Oversampling (e.g., SMOTE)
  * Undersampling

* **Model Training**:

  * Logistic Regression
  * Random Forest
  * Other potential classifiers

* **Model Evaluation**:

  * Confusion Matrix
  * Precision, Recall, F1-Score
  * ROC-AUC Score

## 📌 Requirements

* Python 3.7+
* Jupyter Notebook
* pandas
* numpy
* scikit-learn
* imbalanced-learn (for SMOTE)
* matplotlib / seaborn (for visualization)


## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
   ```

2. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Open the notebook `credit_card_fraud_detection.ipynb` and run all the cells.

## ✅ Results

The models are evaluated using classification metrics, with special focus on **recall** and **precision**, as these are crucial in fraud detection scenarios where false negatives can be costly.

## 📌 Future Improvements

* Try deep learning models like Autoencoders for anomaly detection
* Integrate real-time prediction pipelines
* Deploy the model as a web service (e.g., using Flask or FastAPI)

## 🧑‍💻 Author

Mahi Singh
3rd Year Engineering Student - Data Science

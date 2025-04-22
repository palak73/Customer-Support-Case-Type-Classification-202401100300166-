# Customer-Support-Case-Type-Classification-202401100300166-

# 📞 Customer Support Case Type Classification

This project aims to classify customer support cases into **billing**, **technical**, or **general** queries using machine learning. It processes support case data and builds a supervised classification model that can help automate and streamline customer service workflows.

---

## 🚀 Project Overview

- **Objective**: Automatically classify customer support cases into predefined categories.
- **Tech Stack**: Python, Scikit-learn, Pandas, Seaborn, Matplotlib
- **Model**: Logistic Regression (can be extended to SVM, Random Forest, etc.)
- **Dataset**: Structured dataset with labeled cases
- **Evaluation**: Accuracy, Precision, Recall, Confusion Matrix


## 📂 Dataset

The dataset should contain following columns:

| Column Name       | Description                               |
|-------------------|-------------------------------------------|
| `Message`         | The support message or query from the customer (text).             |
| `Response`        |The response from the support team |
| `case_type`       | Label for the case (`billing`, `technical`, or `general`) |

If you're working with numeric features instead of raw text, update the feature engineering steps accordingly.

---

## ⚙️ How It Works

1. **Data Cleaning**  
   Removes missing values and maps case types to numerical labels.

2. **Text Vectorization**  
   Uses `TfidfVectorizer` to convert text into numerical features.

3. **Model Training**  
   Logistic Regression model trained on vectorized support messages.

4. **Evaluation**  
   Prints classification report and confusion matrix heatmap.

---



# Customer Churn Prediction in Banking

## 📌 Project Overview

Customer churn is a major challenge in the banking industry. Losing customers directly impacts revenue and long-term business growth. This project focuses on predicting whether a bank customer is likely to **churn (leave the bank)** using Machine Learning and Artificial Neural Networks (ANN).

By analyzing customer information such as credit score, age, balance, geography, number of products, and activity status, the model identifies patterns that help predict customer behavior. This allows banks to take proactive measures to improve **customer retention strategies**.

---

## 🎯 Project Objectives

* Analyze customer data to understand factors influencing churn
* Perform Exploratory Data Analysis (EDA) to identify trends and patterns
* Preprocess and prepare the data for machine learning models
* Build an Artificial Neural Network model for churn prediction
* Evaluate model performance and prediction accuracy

---

## 📊 Dataset Information

The dataset contains customer information from a bank.

**Key Features:**

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of Products
* Has Credit Card
* Is Active Member
* Estimated Salary

**Target Variable:**

* `Exited`

  * 0 → Customer stays
  * 1 → Customer churns

---

## ⚙️ Technologies Used

* **Python**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **TensorFlow / Keras**
* **Jupyter Notebook**

---

## 🔍 Project Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Encoding and Scaling
5. Train-Test Split
6. Artificial Neural Network Model Building
7. Model Training
8. Prediction and Evaluation

---

## 📈 Exploratory Data Analysis

EDA was performed to understand relationships between features and customer churn.

Key insights include:

* Customers from certain geographic regions show higher churn rates
* Older customers tend to churn more frequently
* Inactive members are more likely to leave the bank
* Customers with fewer products show higher churn probability

---

## 🤖 Model Building

An **Artificial Neural Network (ANN)** was built using TensorFlow/Keras to classify customers into churn or non-churn categories.

Model structure:

* Input Layer
* Hidden Layers with activation functions
* Output Layer with Sigmoid activation for binary classification

Loss Function: `Binary Crossentropy`
Optimizer: `Adam`

---

## 📊 Model Evaluation

The model performance was evaluated using:

* Accuracy Score
* Loss Curve
* Training vs Validation Accuracy

These metrics help determine how well the model predicts customer churn.

---

## 🚀 Future Improvements

* Implement additional machine learning models such as:

  * Logistic Regression
  * Random Forest
  * XGBoost
* Handle class imbalance using techniques like **SMOTE**
* Improve neural network architecture for better accuracy
* Deploy the model as a **web application using Flask or Streamlit**

---

## 📁 Project Structure

```
Customer-Churn-Prediction
│
├── data
│   └── Churn_Modelling.csv
│
├── notebooks
│   └── churn_prediction.ipynb
│
├── images
│   └── visualizations
│
└── README.md
```

---

## 🎯 Conclusion

This project demonstrates how machine learning and deep learning techniques can be used to predict customer churn. By identifying customers who are likely to leave, businesses can implement targeted strategies to improve customer satisfaction and retention.

---

## 👨‍💻 Author

**Ch Naveen**


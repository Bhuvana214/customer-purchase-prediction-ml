# customer-purchase-prediction-ml
Machine Learning project that predicts customer purchase behavior using Logistic Regression, KNN, SVM, Decision Tree, and Random Forest.
# 🚀 Customer Purchase Prediction using Machine Learning

<p align="center">
Predicting customer purchase intent using behavioral analytics and machine learning.
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green)

</p>

---

## 📌 Project Overview

Businesses often struggle to identify which users are most likely to convert into paying customers.

This project builds an end-to-end Machine Learning pipeline that predicts whether a user will purchase based on platform engagement data such as watch time, activity, and exam participation.

By identifying high-intent users early, businesses can improve:

* 🎯 Marketing ROI
* 💰 Sales conversion rates
* 📈 Retention strategies
* 📢 Personalized campaigns

---

## 🎯 Problem Statement

Can we predict customer purchase behavior using historical engagement data?

This project solves a **binary classification** problem where:

* **0** = No Purchase
* **1** = Purchase

---

## 📂 Dataset Features

Key features used:

* student_country
* days_on_platform
* minutes_watched
* courses_started
* practice_exams_started
* practice_exams_passed
* minutes_spent_on_exams

---

## ⚙️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Statsmodels
* Jupyter Notebook

---

## 🧠 Machine Learning Models Compared

✔ Logistic Regression
✔ K-Nearest Neighbors (KNN)
✔ Support Vector Machine (SVM)
✔ Decision Tree Classifier
✔ Random Forest Classifier

---

## 🏆 Best Model

### Random Forest Classifier

Selected based on strong overall performance and robust handling of structured tabular data.

Benefits:

* Handles non-linear patterns
* Reduces overfitting vs single trees
* Strong predictive performance
* Works well on mixed behavioral signals

---

## 📊 ML Workflow

```text
Data Collection
   ↓
Data Cleaning
   ↓
Outlier Removal
   ↓
Missing Value Treatment
   ↓
Feature Encoding
   ↓
Train/Test Split
   ↓
Model Training
   ↓
Hyperparameter Tuning
   ↓
Performance Comparison
   ↓
Best Model Selection
```

---

## 📈 Evaluation Metrics

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Classification Report

---

## 💼 Real Business Applications

This solution can be used for:

* Lead Scoring
* Subscription Purchase Prediction
* Customer Segmentation
* Personalized Recommendations
* Sales Funnel Optimization

---

## 🚀 How to Run Locally

```bash
git clone https://github.com/your-username/customer-purchase-prediction-ml.git
cd customer-purchase-prediction-ml
pip install -r requirements.txt
jupyter notebook
```

---

## 📁 Project Structure

```bash
customer-purchase-prediction-ml/
│── Machine Learning Project - Solution - Part 6.ipynb
│── README.md
│── requirements.txt
│── dataset.csv
```

---

## 🔮 Future Improvements

* Apply SMOTE for class imbalance
* Add XGBoost / LightGBM
* Deploy using Flask / Streamlit
* Real-time prediction API
* Interactive dashboard

---

## 👩‍💻 About Me

**Bhuvana**

 AI & ML Learner | Continuous Learner

---

## ⭐ Support

If you found this project useful:

🌟 Star this repository
🍴 Fork it
📢 Share it



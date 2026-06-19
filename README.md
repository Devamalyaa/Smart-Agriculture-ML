# 🌾 Smart Agriculture Yield Prediction using Machine Learning

## 📌 Overview

This project predicts agricultural crop yield using Machine Learning techniques and compares the performance of multiple regression models. In addition, K-Means clustering is applied to identify patterns and group similar agricultural conditions.

The goal is to support data-driven farming decisions by analyzing environmental and agricultural factors that influence crop productivity.

---

## 🚀 Features

* Data preprocessing and cleaning
* Exploratory data analysis (EDA)
* Multiple machine learning model implementation
* Model performance comparison
* Evaluation using R² Score, MSE, and MAE
* K-Means clustering for pattern identification
* Data visualization

---

## 🛠️ Machine Learning Models Used

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* K-Nearest Neighbors (KNN) Regressor

---

## 📊 Evaluation Metrics

The models were evaluated using:

* R² Score
* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)

### Performance Summary

| Model             | R² Score |
| ----------------- | -------- |
| Linear Regression | 0.9130   |
| Random Forest     | 0.9065   |
| Decision Tree     | 0.9035   |
| KNN Regressor     | 0.8874   |

---

## 🔍 Clustering

K-Means clustering was used to group similar agricultural conditions and identify productivity patterns within the dataset.

---

## 🧰 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## 📂 Project Structure

```text
Smart-Agriculture-ML/
│
├── images/
│   ├── model_comparison.png
│   ├── actual_vs_predicted.png
│   ├── kmeans_clustering.png
│   └── feature_importance.png
│
├── Copy_of_Smart_Agriculture_Yield_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## 🎯 Future Improvements

* Deploy as a web application
* Add more agricultural datasets
* Experiment with advanced ensemble models
* Integrate weather APIs for real-time prediction

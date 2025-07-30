# Federated vs Centralized Learning for Medical Insurance Cost Prediction

## 📌 Overview

This project compares **Federated Learning** and **Centralized Machine Learning** approaches for predicting medical insurance charges using the `Medical_insurance.csv` dataset. The core objective is to highlight the trade-offs between data privacy and model performance.

## ⚙️ Features

* Data preprocessing: Encoding categorical variables, normalization
* Centralized training using `SGDRegressor`
* Simulated federated learning across 4 clients for 10 communication rounds
* Evaluation using **Mean Squared Error (MSE)**
* Performance comparison between both models

## 🧠 Algorithms Used

* **Centralized Model**: Linear Regression (SGDRegressor)
* **Federated Model**: Model updates from clients averaged after local training

## 📊 Evaluation Metric

* **Mean Squared Error (MSE)** is used to compare accuracy across both training setups.

## 🗃️ Dataset

* `Medical_insurance.csv` with features like age, sex, BMI, children, smoker, region, and charges.

## 📁 Structure

```
finalProject.ipynb
Medical_insurance.csv
README.md
```

## 🚀 How to Run

1. Install dependencies:

   ```bash
   pip install pandas scikit-learn matplotlib
   ```
2. Open `finalProject.ipynb` in Jupyter Notebook.
3. Run all cells to simulate both centralized and federated learning.

## 📌 Conclusion

The project showcases how federated learning can preserve privacy while achieving competitive performance compared to centralized models, especially in sensitive domains like healthcare.

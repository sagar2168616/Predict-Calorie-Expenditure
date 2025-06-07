
# 🏋️ Predict Calorie Expenditure - Kaggle Playground Series S5E5

Welcome to my solution for the **"Predict Calorie Expenditure"** competition on Kaggle's Playground Series - Season 5, Episode 5.

This repository contains my code, experiments, and documentation for tackling this regression challenge using a synthetically-generated tabular dataset.

---

## 📌 Problem Statement

The goal of this competition is to **predict the number of calories burned during a workout** using the features provided in the dataset.

This challenge is designed to help participants practice and improve their machine learning skills using tabular data.

---

## 🧪 Evaluation Metric

The competition is evaluated using **Root Mean Squared Logarithmic Error (RMSLE)**:

\[
RMSLE = \sqrt{ \frac{1}{n} \sum_{i=1}^n \left( \log(p_i + 1) - \log(a_i + 1) \right)^2 }
\]

Where:
- \( n \) = number of test samples  
- \( p_i \) = predicted calorie value  
- \( a_i \) = actual calorie value  
- \( \log \) = natural logarithm

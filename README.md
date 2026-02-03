# Assignment_2_Predictive_analysis
Sampling by Dr. Anjula

# Sampling Assignment – Handling Imbalanced Dataset

## Objective

The objective of this assignment is to understand the importance of **sampling techniques** in handling **imbalanced datasets** and to analyze how different sampling strategies affect the **accuracy of multiple machine learning models**.

---

## Problem Statement

In real-world classification problems, datasets are often highly imbalanced, which can negatively impact model performance.
In this assignment, a **credit card dataset** with severe class imbalance is used. The dataset is balanced using various sampling techniques, and the performance of different machine learning models is evaluated to study the impact of sampling.

---

## Dataset

* **Dataset Name:** Creditcard_data.csv
* **Source:** Provided via GitHub
* **Problem Type:** Binary Classification
* **Target Variable:** `Class`

  * `0` → Non-fraud
  * `1` → Fraud

The dataset is highly imbalanced, making it suitable for studying sampling techniques.

---

## Sampling Techniques Used

Five different sampling techniques were applied to balance the dataset:

| Sampling Technique   | Description                                       |
| -------------------- | ------------------------------------------------- |
| Random Undersampling | Reduces majority class samples                    |
| Random Oversampling  | Increases minority class samples                  |
| SMOTE                | Synthetic Minority Oversampling Technique         |
| NearMiss             | Undersampling based on nearest neighbors          |
| SMOTEENN             | Combination of SMOTE and Edited Nearest Neighbors |

Each technique generates a different balanced sample.

---

## Machine Learning Models Used

Five machine learning models were trained on each sampled dataset:

| Model ID | Model Name               |
| -------- | ------------------------ |
| M1       | Logistic Regression      |
| M2       | Decision Tree Classifier |
| M3       | Random Forest Classifier |
| M4       | K-Nearest Neighbors      |
| M5       | Support Vector Machine   |

---

## Evaluation Metric

* **Accuracy (%)** was used as the evaluation metric to compare model performance across different sampling techniques.

---

## Results

A **5 × 5 accuracy matrix** was generated where:

* Rows represent machine learning models
* Columns represent sampling techniques

This table helps in identifying how each sampling method impacts different models.

---

## Visualization

A bar graph was plotted to visually compare the accuracy of different models under different sampling strategies.
This visualization provides an intuitive understanding of performance variation.

---

## Analysis & Discussion

* Oversampling techniques such as **SMOTE** and **SMOTEENN** generally improved performance for most models.
* Undersampling techniques sometimes resulted in information loss.
* No single sampling technique performed best for all models.
* The effectiveness of a sampling method depends on the model used.

---

## Conclusion

This assignment demonstrates that **sampling plays a crucial role** in handling imbalanced datasets.
Choosing the right sampling strategy can significantly improve model performance.
The results show that a combination of appropriate sampling techniques and suitable models is essential for effective classification.

---

## Tools & Technologies Used

* **Google Colab**
* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Scikit-learn**
* **Imbalanced-learn (imblearn)**

---

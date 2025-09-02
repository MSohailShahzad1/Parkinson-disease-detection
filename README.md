# 🧠 Parkinson's Disease Detection

This project focuses on predicting **Parkinson's Disease** using **Machine Learning models** trained on biomedical voice and speech data. The goal is to assist in **early detection**, which is crucial for improving patient quality of life and healthcare outcomes.

---

## 📌 Features

* Preprocessing of dataset (handling missing values, normalization, feature selection).
* Implementation of multiple ML algorithms:

  * k-Nearest Neighbors (k-NN)
  * Logistic Regression
  * Naive Bayes
  * Decision Tree
  * Support Vector Machine (SVM)
  * Ensemble Learning (Hard, Soft, Stacking, Boosting)
* Evaluation with **Accuracy, Precision, Recall, and F1-score**.
* Comparison of results with existing studies.

---

## 📊 Dataset

* **Name:** Parkinson’s Disease Dataset
* **Size:** 195 rows × 24 columns
* **Features:**

  * Vocal frequency measures (MDVP\:Fo, MDVP\:Fhi, MDVP\:Flo, etc.)
  * Jitter & Shimmer variations
  * Noise-to-tonal ratios (NHR, HNR)
  * Nonlinear measures (RPDE, D2, DFA, PPE)
* **Target Variable:**

  * `status = 1` → Parkinson’s Disease
  * `status = 0` → Healthy

---

## ⚙️ Methodology

1. **Data Preprocessing**

   * Handling missing values
   * Feature scaling & normalization
   * Balancing dataset

2. **Model Training & Testing**

   * Applied multiple ML algorithms
   * Hyperparameter tuning where needed

3. **Evaluation Metrics**

   * Accuracy
   * Precision
   * Recall
   * F1-score

---

## 📈 Results

| Model                  | Accuracy | Precision | Recall | F1-score |
| ---------------------- | -------- | --------- | ------ | -------- |
| **k-NN**               | 0.983    | 0.967     | 1.0    | 0.983    |
| Logistic Regression    | 0.831    | 0.852     | 0.793  | 0.821    |
| Naive Bayes            | 0.831    | 0.852     | 0.793  | 0.821    |
| Decision Tree          | 0.831    | 0.852     | 0.793  | 0.821    |
| Ensemble (Hard Voting) | 0.932    | 1.0       | 0.862  | 0.926    |
| Ensemble (Soft Voting) | 0.983    | 1.0       | 0.966  | 0.982    |
| Boosting               | 0.966    | 0.966     | 0.966  | 0.966    |
| Ensemble (Stacking)    | 0.983    | 1.0       | 0.966  | 0.982    |
| **SVM**                | 0.983    | 0.967     | 1.0    | 0.983    |

✔️ **Top Performers:** k-NN, SVM, Ensemble (Soft & Stacking)

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:**

  * scikit-learn
  * numpy
  * pandas
  * matplotlib / seaborn (for visualization)
* **Environment:** Google Colab

---

## 🚀 Future Work

* Use more **advanced ensemble techniques**.
* Incorporate **additional clinical data** beyond voice features.
* Validate models on **larger & more diverse datasets**.
* Explore **deep learning approaches**.

---

## 👨‍💻 Authors

* **Muhammad Sohail Shahzad**

---

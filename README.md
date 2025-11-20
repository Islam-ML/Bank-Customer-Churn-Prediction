# 🏦 Bank Customer Churn Prediction

## 📖 Project Overview | نبذة عن المشروع

**[English]**
Customer churn is a critical metric for banking institutions. This project aims to build a robust Machine Learning model to predict whether a customer will leave the bank based on their demographic and financial data. By identifying at-risk customers early, the bank can implement retention strategies to reduce losses.

**[العربية]**
تعتبر مغادرة العملاء (Churn) من أهم التحديات التي تواجه المؤسسات البنكية. يهدف هذا المشروع إلى بناء نموذج تعلم آلي قوي للتنبؤ بما إذا كان العميل سيترك البنك بناءً على بياناته الديموغرافية والمالية. يساعد هذا النموذج البنك على تحديد العملاء المعرضين للمغادرة واتخاذ إجراءات استباقية للحفاظ عليهم.

---

## 🛠️ Tech Stack | الأدوات والتقنيات

The project utilizes a comprehensive stack of Data Science tools:

*   **Data Manipulation:** `Pandas`, `NumPy`
*   **Visualization:** `Matplotlib`, `Seaborn`
*   **Machine Learning:** `Scikit-Learn`, `XGBoost`, `SVM`, `Random Forest`
*   **Deep Learning:** `TensorFlow / Keras (ANN)`
*   **Imbalance Handling:** `SMOTE` (Synthetic Minority Over-sampling Technique)

---

## 📊 Methodology | منهجية العمل

1.  **Exploratory Data Analysis (EDA):** Analyzing feature distributions and correlations (Heatmaps) to understand churn drivers.
2.  **Data Preprocessing:**
    *   Handling missing values (if any).
    *   **One-Hot Encoding** for categorical features (Geography, Gender).
    *   **Feature Scaling** using `StandardScaler`.
3.  **Model Development:** Training and evaluating 5 different models.
4.  **Handling Class Imbalance:** Applying **SMOTE** to improve recall for the minority class (Churners).
5.  **Evaluation:** Comparing models based on Accuracy, Precision, Recall, and F1-Score.

---

## 🏆 Model Performance & Results | النتائج والأداء

After extensive experimentation, we compared the models' performance on the test set. The **XGBoost Classifier** proved to be the most balanced model.

| Model | Accuracy | Precision (Class 1) | Recall (Class 1) | Verdict |
| :--- | :---: | :---: | :---: | :--- |
| **XGBoost (Winner)** 🥇 | **86.95%** | **High** | **Balanced** | **Best Overall Performance** |
| Random Forest | 86.65% | High | Moderate | Strong Contender |
| ANN (Deep Learning) | 86.30% | Moderate | Moderate | Good Baseline |
| SVM | 85.60% | High | Low | Good Precision, Low Recall |
| Logistic Regression | 81.10% | Low | Low | Underperformed |

> **Note:** While applying **SMOTE** significantly increased the *Recall* (ability to find churners), it slightly reduced the overall *Accuracy*. The standard XGBoost model offered the best trade-off for this specific business case.

---

## 📈 Visualizations | رسوم بيانية

*(You can add screenshots of your plots here, e.g., Correlation Heatmap or XGBoost Learning Curve)*

*   **Correlation Heatmap:** To show relationships between features.
*   **XGBoost Learning Curve:** Demonstrating the reduction of Log Loss over training rounds.

# lead-score-prediction
Machine learning model to predict lead conversion probability
# 🎯 Lead Score Prediction (End-to-End ML Project)

## 📌 Business Problem

Companies receive a large number of leads, but only a small percentage convert into customers. The objective of this project is to build a machine learning model that predicts the probability of lead conversion, helping businesses prioritize high-quality leads.

---

## 📊 Dataset Overview

* Contains information about leads such as source, engagement level, and interaction history
* Target variable: **Converted (Yes/No)**

---

## 🔍 Key Steps

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Model Building using Logistic Regression
* Model Evaluation

---

## 🤖 Model Used

* Logistic Regression

---

## 📈 Model Performance

| Metric     | Value             |
| ---------  | ----------------  |
| Accuracy   | 0.7908540685944856|
| Recall     | 0.793392275476966 |
| Specificity| 0.7884948096885813|

---

## 📊 Key Insights

* Leads with higher engagement have a significantly higher probability of conversion
* Certain lead sources generate more qualified leads
* Model helps prioritize leads based on conversion likelihood

---

## 📷 Visualizations

<img width="598" height="533" alt="image" src="https://github.com/user-attachments/assets/e7be369f-0984-4e49-b15c-00b8d77ba5f1" />
<img width="598" height="533" alt="image" src="https://github.com/user-attachments/assets/91a201db-6288-4825-bf40-89bf728016ed" />
<img width="688" height="533" alt="image" src="https://github.com/user-attachments/assets/648fb3da-66fe-43dc-b40d-196bdc3a7b5f" />
-<img width="1555" height="1110" alt="image" src="https://github.com/user-attachments/assets/a5fc9559-119c-4784-825f-9ee605ccd28f" />
-<img width="338" height="333" alt="image" src="https://github.com/user-attachments/assets/643ecce2-87be-4911-8473-c8781460273c" />
<img width="372" height="262" alt="image" src="https://github.com/user-attachments/assets/7a54db61-cb4f-47e3-8a7e-ac8bd5e3463b" />

## 💡 Business Impact

* Helps sales teams focus on high-potential leads
* Improves conversion rates
* Optimizes marketing and sales strategies

---

## 🚀 How to Run

```bash id="runls"
pip install -r requirements.txt
jupyter notebook notebooks/lead_score_model.ipynb
```

---

## 👤 Author

Ashwini Khandelwal

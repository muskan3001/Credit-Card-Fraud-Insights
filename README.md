# 💳 Credit Card Fraud Insights  
### _Detecting Fraud. Protecting Consumers. Driving Data-Driven Trust._

---

## 🧠 Executive Summary

This project analyzes the **2023 Credit Card Fraud Detection Dataset** consisting of over **550,000 anonymized transactions** by European cardholders. The core objective is to detect potentially fraudulent activities using **statistical modeling** and **exploratory data analysis (EDA)** — helping financial institutions minimize fraud-related losses while enhancing consumer trust.

---

## 📌 Project Objective

- 🧠 Identify key features that separate fraudulent from legitimate transactions  
- 📊 Visualize high-risk patterns in anonymized variables (`V1`–`V28`)  
- 🧪 Evaluate logistic regression coefficients & significance via Z-scores  
- ⚙️ Explore time and amount patterns linked to fraud cases  
- 🔍 Enable future model development for real-time fraud detection

---

## 📊 Dataset Overview

- **Records:** 550,000+  
- **Target:** `Class` (1 = Fraud, 0 = Legitimate)  
- **Features:** 30 columns  
- **Time Frame:** 2023 (Snapshot)  
- **Source:** Kaggle – [*Credit Card Fraud Detection Dataset 2023*](https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023)

### 🔑 Key Columns

| Column        | Description                                    |
|---------------|------------------------------------------------|
| `id`          | Unique transaction ID                         |
| `V1`–`V28`    | PCA-transformed anonymized features            |
| `Amount`      | Transaction amount in Euros                    |
| `Class`       | Binary label (1 = Fraud, 0 = Non-Fraudulent)   |

---

## 🔍 Analysis Highlights

- ✅ Identified **statistically significant features** using Z-score analysis  
- 📉 Fraudulent transactions often involve **lower or mid-range amounts**  
- 🔁 Time-based analysis suggests fraud is **not randomly distributed**  
- ⚖️ **V5** is an outlier — statistically insignificant in most tests  
- 🧠 Logistic regression is effective for baseline fraud prediction models

---

## 📊 Business Value & Insights

- 🛡️ Enables proactive fraud flagging by isolating transaction patterns  
- 💰 Reduces financial loss from undetected fraudulent activity  
- 🧭 Builds a foundation for machine learning-based fraud detection  
- 🤖 Even anonymized datasets can power **accurate, interpretable models**

---

## 🛠 Tools & Technologies Used

- Python  
- Pandas & NumPy — Data preprocessing  
- Seaborn & Matplotlib — Visualization  
- Scikit-learn — Logistic Regression & Evaluation  
- Jupyter Notebook

---

<sub>📧 Email: muskan.gulati3029@gmail.com  
🔗 <a href="https://www.linkedin.com/in/muskan-gulati30/">LinkedIn</a></sub>

---

## 🧾 Project Structure

```bash
credit-card-fraud-insights/
├── CreditCardDetection_Project-2.ipynb     # Main analysis notebook
├── README.md                               # This file
└── images/                                 # (Optional) for charts

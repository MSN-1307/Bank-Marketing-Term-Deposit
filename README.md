# 🏦 Bank Marketing — Term Deposit Subscription Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> Predicting whether a bank client will subscribe to a term deposit using machine learning — based on real-world telemarketing campaign data.

---

## 📌 Problem Statement

A Portuguese bank ran a series of telemarketing campaigns to get clients to subscribe to a **term deposit**. The goal of this project is to:

- Analyze client and campaign data
- Identify key factors influencing subscription decisions
- Build a classification model to **predict subscription (yes/no)**

---

## 📂 Project Structure

```
bank-marketing-project/
│
├── bankmarketing.csv                        # Raw dataset (41,188 records)
├── Bank_Marketing_Inspection_test.ipynb     # Data inspection & EDA
├── BANK_TERM_DEPOSIT.ipynb                  # Full ML pipeline notebook
├── Bank_Term_Deposit_Summary.ipynb          # Project summary notebook
└── README.md                               # Project documentation
```

---

## 📊 Dataset Overview

| Feature | Description |
|--------|-------------|
| `age` | Age of the client |
| `job` | Type of job |
| `marital` | Marital status |
| `education` | Education level |
| `default` | Has credit in default? |
| `housing` | Has housing loan? |
| `loan` | Has personal loan? |
| `contact` | Contact communication type |
| `month` | Last contact month |
| `duration` | Last contact duration (seconds) |
| `campaign` | Number of contacts during campaign |
| `poutcome` | Outcome of previous campaign |
| `emp.var.rate` | Employment variation rate |
| `cons.price.idx` | Consumer price index |
| `euribor3m` | Euribor 3-month rate |
| **`y`** | **Target: subscribed? (yes/no)** |

- **Total Records:** 41,188
- **Features:** 20 input + 1 target
- **Target:** Binary classification (`yes` / `no`)

---

## 🔄 Project Workflow

```
Raw Data → EDA → Preprocessing → Model Training → Evaluation → Insights
```

1. **Data Inspection** — shape, info, missing values, distributions
2. **Preprocessing** — handle unknowns, encode categories, scale features
3. **Model Training** — Logistic Regression, Decision Tree, Random Forest
4. **Evaluation** — Accuracy, Precision, Recall, F1-Score
5. **Insights** — key findings and business recommendations

---

## 🤖 Models Used

| Model | Type |
|-------|------|
| Logistic Regression | Linear Classifier |
| Decision Tree | Tree-based Classifier |
| Random Forest | Ensemble Classifier |

---

## 📈 Key Findings

- **`duration`** — longer calls = higher subscription rate
- **`poutcome`** — successful past campaign = likely to subscribe again
- **`month`** — May and August were most effective months
- **`contact`** — cellular contact worked better than telephone
- **Random Forest** gave the best overall performance

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.8+ | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical computation |
| Matplotlib / Seaborn | Data visualization |
| Scikit-learn | Machine learning |
| Jupyter Notebook | Development environment |

---

## 👤 Author

**Your Name**
- 🔗 LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)
- 💻 GitHub: https://github.com/MSN-1307/Bank-Marketing-Term-Deposit
- 📧 Email: msainikhit@gmail.com

---

*Dataset: [UCI ML Repository — Bank Marketing](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)*

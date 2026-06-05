# 🏦 Bank Marketing Prediction using Decision Tree

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-orange.svg)](https://scikit-learn.org/)
[![Accuracy](https://img.shields.io/badge/Accuracy-91.24%25-brightgreen.svg)](https://github.com/)

## 📌 Project Overview

This project predicts whether a bank customer will subscribe to a term deposit using a **Decision Tree Classifier**. By analyzing customer data like age, job, call duration, and economic indicators, the model helps banks target potential customers efficiently.

**Problem Statement**: Banks waste resources calling uninterested customers.  
**Solution**: ML model predicts `Yes` or `No` with **91.24% accuracy** before making calls.

---

## 📊 Dataset

| Attribute | Details |
| --- | --- |
| **Name** | Bank Marketing Dataset |
| **Source** | UCI Machine Learning Repository |
| **File** | `bank-additional-full.csv` |
| **Total Records** | 41,188 customers |
| **Features** | 20 input columns |
| **Target** | `y` - `yes` or `no` |

### Key Features Used:
- `age` - Customer age
- `job` - Job type 
- `duration` - Last contact duration in seconds - **Most important**
- `campaign` - Number of contacts in this campaign
- `pdays` - Days since last contact
- `nr.employed` - Number of employees - **Root node feature**

---

## 🎯 How It Works

1. **Input**: Customer details like age=42, duration=380, pdays=18
2. **Process**: Decision Tree checks rules like `duration > 165.5` and `nr.employed <= 5087`
3. **Output**: `Yes` - Customer likely to subscribe / `No` - Unlikely to subscribe

---

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**: `pandas`, `scikit-learn`, `matplotlib`
- **Algorithm**: `DecisionTreeClassifier`

Install dependencies:
```bash
pip install pandas scikit-learn matplotlib
```

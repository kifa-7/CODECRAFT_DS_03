# CODECRAFT_DS_03
# 🌳 Task 03 – Decision Tree Classifier (Pure Python)

This repository contains a simple **Decision Tree Classifier** implemented using **pure Python**, without any external libraries or CSV handling. It is part of the internship tasks for **CodeCraft**.

---

## 🧠 Objective

> Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data.

Dataset used: [Bank Marketing Dataset – UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)

---

## 📁 Files Included

| File Name   | Description                                   |
|-------------|-----------------------------------------------|
| `task3.py`  | Core Python script with the rule-based classifier logic |
| `README.md` | This documentation file                       |

---

## 📊 Features Used for Classification

- `age`
- `job`
- `marital`
- `previous` (outcome of previous marketing campaign)

---

## 🔍 Classifier Logic

The classifier uses simple rule-based conditions derived from dataset patterns:

```python
if customer['previous'] == 'success':
    return 'Subscribed'
elif customer['job'] == 'student':
    return 'Subscribed'
elif customer['age'] > 40 and customer['job'] == 'technician':
    return 'Subscribed'
else:
    return 'Not Subscribed'
# 🙋‍♀️ Author
Kifa Fathima
Data Science Intern
CodeCraft Internship Program


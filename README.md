# Beta Bank Churn Prediction 🏦📉

Machine Learning project to **predict customer churn** (whether a client will leave the bank soon).  
The goal is to help the business focus retention efforts on high-risk customers.

---

## Objective 🎯
Build a classification model with the **highest F1 score possible** and also report **AUC-ROC**.

Target:
- `Exited` (1 = customer left, 0 = stayed)

---

## Data 📦
File:
- `Churn.csv`

Features include customer profile and banking behavior (e.g., credit score, geography, age, balance, number of products, etc.).

---

## Key Challenge ⚖️
The dataset is **imbalanced** (most customers stay).  
To handle this, I applied **upsampling** on the training set to improve recall and overall F1.

---

## Approach 🧠
1. Load and inspect the dataset
2. Handle missing values (including a “was missing” indicator)
3. Encode categorical features
4. Scale numeric features where needed
5. Train/validation split
6. Train baseline models and tune hyperparameters
7. Evaluate with **F1** and **AUC-ROC**

---

## Models Tested 🔍
- DecisionTreeClassifier (baseline + tuned)
- RandomForestClassifier (baseline + tuned)
- LogisticRegression (reference)

✅ Final choice: **RandomForestClassifier** (best overall balance)

---

## Results 📈
- **F1 ≈ 0.62**
- **AUC-ROC ≈ 0.87**

This model provides a strong tradeoff between catching churners and avoiding too many false positives.

---

## Suggested Repo Structure 🗂️

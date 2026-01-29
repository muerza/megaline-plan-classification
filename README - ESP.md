# Megaline Plan Classification 📱🤖

Machine Learning project to **recommend the right mobile plan** for Megaline customers: **Smart** or **Ultra**.  
The model learns from customer behavior data to support plan upgrades and reduce legacy-plan usage.

---

## Goal 🎯
Build a classification model to predict:
- `is_ultra` (1 = Ultra, 0 = Smart)

Minimum target:
- ✅ **Accuracy ≥ 0.75**

Dataset:
- `users_behavior.csv`

---

## Approach 🧠
- Load and explore data
- Split into train/validation sets
- Train baseline models
- Tune hyperparameters
- Evaluate using **accuracy** (and review confusion matrix)

---

## Models Tested 🔍
- Decision Tree
- Random Forest ✅ (final)
- Logistic Regression

---

## Result ✅
Final model: **RandomForestClassifier**

- **Validation Accuracy: 0.8085** 🎯

This exceeds the required threshold and provides a solid balance of performance and stability.

---

## Suggested Repo Structure 🗂️

```text
.
├── data/
│   └── users_behavior.csv
├── notebooks/
│   └── megaline-plan-classification.ipynb
├── src/                  # (optional) reusable functions
│   ├── train.py
│   └── utils.py
├── README.md
└── requirements.txt

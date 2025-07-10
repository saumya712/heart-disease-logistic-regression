# 🫀 Heart Disease Prediction using Logistic Regression

Hey there!  
This is a simple logistic regression project I did on the classic Cleveland heart disease dataset. The goal here was just to try out some solid classification techniques and understand metrics like **ROC-AUC**, **confusion matrix**, and **classification report** properly — not trying to go fancy with models or anything.

## 🧠 What's inside?

- Used the UCI Heart Disease Dataset (Cleveland subset)
- Did basic data cleaning and standard scaling (nothing too crazy)
- Already encoded columns, so no need to do one-hot or label encoding
- Built a pipeline with `StandardScaler` and `LogisticRegression`
- Evaluated using:
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion matrix
  - ROC-AUC (got a clean 0.94 💪)

## 🛠️ Tools & Libraries

- Python
- scikit-learn
- pandas
- matplotlib / seaborn (for visualizations)

## 📈 Results

- Accuracy: `86.6%`
- ROC AUC Score: `0.94`
- Pretty balanced precision/recall between both classes

Honestly, this was a solid dataset to practice logistic regression — clean structure, binary target, and very interpretable results.

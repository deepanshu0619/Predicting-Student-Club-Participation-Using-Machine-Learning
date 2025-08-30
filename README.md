# 🎓 Student Club Participation Prediction

This project aims to predict whether a student will participate in a club based on their interest level and available free hours per week using machine learning techniques.

---

## 📌 Problem Statement

Predict student club participation using features such as interest level and free hours available, helping institutions better understand engagement factors.

---

## 📁 Dataset

- **Filename:** `club_participation.csv`
- **Features:**
  - `interest_level`: Numeric score indicating interest in clubs.
  - `free_hours_per_week`: Weekly free time in hours.
- **Target:**
  - `club_participation`: Whether the student joins a club (`yes` or `no`).

---

## 🛠️ Methodology

1. **Data Preprocessing**
   - Convert categorical target into binary (yes → 1, no → 0)
   - Handle class balance using `class_weight='balanced'` in the model

2. **Model Used**
   - Random Forest Classifier

3. **Evaluation Metrics**
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - Confusion Matrix (heatmap)

---

## 📊 Output

Example evaluation metrics:
# Predicting-Student-Club-Participation-Using-Machine-Learning
# Predicting-Student-Club-Participation-Using-Machine-Learning

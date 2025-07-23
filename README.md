# Predicting-Patient-No-Shows-in-Healthcare-Appointments
'''
# 🏥 Predicting Patient No-Shows in Healthcare Appointments

This machine learning project uses real-world appointment data to predict whether a patient will miss their scheduled healthcare appointment. By identifying high-risk no-shows in advance, clinics can improve scheduling efficiency, reduce financial losses, and enhance patient care.

---

## 📌 Business Problem

Healthcare providers suffer significant losses from missed appointments. These no-shows waste staff time, reduce clinic efficiency, and lead to longer wait times for other patients. This project aims to:

- Predict whether a patient will miss an appointment
- Identify patterns and factors contributing to no-shows
- Improve scheduling and reduce revenue loss by using predictive modeling

---

## 🧠 Approach

- **Model:** Logistic Regression
- **Feature Engineering:** Extracted wait time, transformed dates, encoded categorical variables,SMOTE, threshold adjustment
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1 Score, ROC-AUC
- **Cross-Validation:** Leave-One-Out and 5-fold CV to assess stability

---

## 📁 Dataset

- Source: [Kaggle - Medical Appointment No Shows](https://www.kaggle.com/datasets/joniarroba/noshowappointments)
- Records: 100,000+ historical appointments
- Key Features: Age, Gender, Appointment Dates, SMS Received, Neighborhood, No-show status

---

## 💻 Technologies

- Python 3.10+
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`; 'imblearn'

---


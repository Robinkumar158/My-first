This is my First ML Projects in which i build a Model prediction to predict a particular student can be placed or not.
# 🎯 Placement Prediction Project

This machine learning project predicts whether a student will be placed based on two important features: **Resume Score** and **CGPA**. It is a simple classification task that demonstrates how academic performance and resume strength can influence placement outcomes.

## 📌 Objective

To build a predictive model that classifies students into **Placed** or **Not Placed** categories using:

- `resume_score`: A score (out of 100) representing the quality of the student's resume (skills, keywords, format, etc.)
- `cgpa`: The student's cumulative grade point average
- `placed`: Output column — `1` for placed, `0` for not placed

## 🧠 Techniques Used

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Classification Models (e.g., Logistic Regression, Decision Tree, Random Forest)
- Evaluation Metrics: Accuracy, Confusion Matrix, Precision, Recall
- Visualizations to interpret results and model performance

## 📊 Sample Dataset

| resume_score | cgpa | placed |
|--------------|------|--------|
| 88           | 8.6  | 1      |
| 65           | 6.9  | 0      |
| 74           | 7.4  | 1      |

## 📈 Insights

- Students with higher CGPA and better resume scores have a higher probability of placement.
- Resume quality plays a significant role even if the CGPA is moderate.

## ✅ Outcome

A trained model that can predict placement status with good accuracy using just two features, useful for early evaluation of students and career guidance.

---

Feel free to clone, improve, or extend this project. Contributions are welcome!


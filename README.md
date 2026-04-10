
#  Student Performance Prediction System

##  Project Overview

This project focuses on predicting **students' final exam scores** using academic and behavioral data. The goal is to identify key factors affecting student performance and build a machine learning model for prediction.

---

## Objective

* Predict students’ **Final Exam Score**
* Identify important factors like study hours, motivation, attendance
* Help institutions take **early actions to improve performance**

---

## Dataset Information

### Target Variable

* `Final_Exam_Score`

### Input Features

* Hours_Studied
* Attendance
* Parental_Involvement
* Access_to_Resources
* Extracurricular_Activities
* Sleep_Hours
* Previous_Scores
* Motivation_Level
* Internet_Access
* Tutoring_Sessions

---

##  Data Preprocessing

### Data Cleaning

* Handled missing values
* Removed duplicates
* Checked for invalid/unknown values

### Outlier Detection

* Used **IQR Method**
* Treated outliers in:

  * Hours_Studied
  * Attendance
  * Sleep_Hours
  * Previous_Scores

---

##  Exploratory Data Analysis

###  Key Insights

* More study hours → Higher scores
* Previous scores strongly impact final results
* Higher motivation → Better performance
* Internet & resources improve outcomes
* Sleep has minimal impact

---

##  Feature Engineering

* Converted categorical data into numerical using **mapping**
* Removed unnecessary columns
* Final dataset split into:

  * `X` (features)
  * `y` (target)

---

##  Model Development

### Model Used

* **Linear Regression**

###  Train-Test Split

* 80% Training
* 20% Testing

---

## Model Evaluation

| Metric   | Value |
| -------- | ----- |
| MSE      | 17.89 |
| MAE      | 3.36  |
| R² Score | 0.75  |

### Conclusion

* Model performs well with **75% accuracy (R²)**
* Suitable for predicting student performance

---

## Insights

* Motivation level is a key factor
* Previous scores strongly influence results
* Study hours significantly affect performance
---

## Recommendations

1. Improve student motivation through engagement
2. Provide better access to learning resources
3. Support low-performing students with mentoring
4. Maintain a balance between study and rest

---

## Future Improvements

* Use advanced models like **XGBoost, LightGBM**
* Add more features (assignments, feedback, participation)
* Deploy using **Flask / FastAPI**

---
##  Conclusion

* Understanding student performance patterns
* Predicting exam scores
* Supporting early intervention for students


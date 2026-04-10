# 📊 Employee Performance Analysis – INX Future Inc.

## 📌 Project Overview

This project analyzes employee performance data from **INX Future Inc.**, where the company faced a decline in performance leading to an 8% drop in client satisfaction.

Using data science and machine learning techniques, this project identifies key factors affecting employee performance and builds a predictive model to help improve organizational efficiency.

---

## 🎯 Business Problem

INX Future Inc. is experiencing declining employee performance. The goal is to:

* Identify the **root causes of performance decline**
* Determine the **key factors influencing performance**
* Build a **predictive model** to classify employee performance
* Provide **actionable recommendations** to management

---

## 📂 Dataset Information

* Dataset: INX Future Inc. Employee Dataset
* Features include:

  * Age
  * Department
  * Job Role
  * Salary Hike %
  * Work-Life Balance
  * Environment Satisfaction
* Target Variable: **Performance Rating**

---

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 🔍 Project Workflow

### 1. Exploratory Data Analysis (EDA)

* Majority employees have **performance rating = 3 (average performers)**
* Dataset is **imbalanced** (few high & low performers)
* Employee age shows **normal distribution**
* Work-life balance is mostly **moderate (level 3)**

---

### 2. Data Preprocessing

* No missing values (clean dataset ✅)
* Removed irrelevant columns (e.g., Employee ID)
* Applied:

  * Label Encoding
  * One-Hot Encoding
* Feature scaling using **Standardization**

---

### 3. Model Building

Models used:

* Logistic Regression
* Decision Tree
* ✅ **Random Forest (Best Model)**

👉 Random Forest selected because:

* Handles non-linear data
* Better accuracy and stability

---

### 4. Model Evaluation

* Compared models using:

  * Accuracy
  * F1-score
  * Cross-validation

👉 **Random Forest performed best**

---

### 5. Prediction

* Model successfully predicts employee performance
* Input data is standardized before prediction
* Model validated on test dataset

---

### 6. Visualization & Insights

#### 📊 Department-wise Performance

* **R&D & Development** → High consistent performance
* **Sales** → High variation (needs improvement)

#### 📊 Top 3 Important Features

1. **Salary Hike % (~22%)** → Strongest driver
2. **Environment Satisfaction (~21%)**
3. **Work-related factors**

---

## 📈 Key Insights

* Financial rewards significantly impact performance
* Work environment satisfaction is a critical factor
* Performance inconsistency exists in Sales department
* Balanced work-life improves productivity

---

## 🧠 Business Recommendations

* Align salary hikes with performance metrics
* Improve workplace environment
* Standardize training in Sales department
* Focus on employee satisfaction programs

---

## 📁 Project Structure

```bash
Employee-Performance-Analysis/
│
├── data/
├── notebooks/
│   ├── data_exploratory_analysis.ipynb
│   ├── Data_Processing.ipynb
│   ├── train_model.ipynb
│   ├── predict_model.ipynb
│   ├── visualize.ipynb
│   ├── Analysis_Report.ipynb
│   └── Final_Summary.ipynb
│
├── README.md
```


---

## 🧾 Conclusion

This project successfully identifies the core drivers of employee performance and provides a robust machine learning solution to predict performance levels. It enables data-driven HR decisions to improve employee productivity and organizational outcomes.

---

## 👤 Author

**Chetan Shinagari**
Aspiring Data Analyst / Data Scientist

---

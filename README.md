# 📊 Student Performance Prediction System

A Machine Learning project that predicts whether a student will **Pass or Fail** based on academic and lifestyle factors such as study performance, preparation, and exam scores.

---

## 📌 Project Overview

This project analyzes student exam data and builds a predictive model using **Logistic Regression** to classify student performance.

It includes:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Engineering
* Machine Learning Modeling
* Model Evaluation

---

## 🎯 Objectives

* Analyze student academic performance
* Identify key factors affecting results
* Visualize score relationships
* Build a prediction model
* Evaluate classification accuracy

---

## 🗂 Dataset Features

The dataset contains the following columns:

* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch
* Test Preparation Course
* Math Score
* Reading Score
* Writing Score

A new column **Result** was created:

* **Pass → Score ≥ 50**
* **Fail → Score < 50**

---

## 🛠 Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / VS Code

---

## 📊 Exploratory Data Analysis

The following visualizations were created:

* Pass vs Fail Distribution
* Reading vs Writing Scatter Plot
* Correlation Heatmap

### Key Insights

* Reading & Writing scores strongly correlate
* Test preparation improves performance
* Higher overall scores increase pass probability

---

## 🤖 Machine Learning Model

**Algorithm Used:** Logistic Regression

### Steps:

1. Data preprocessing
2. Label encoding
3. Feature selection
4. Train-test split (80/20)
5. Model training
6. Predictions

---

## 📈 Model Evaluation

Evaluation metrics used:

* Accuracy Score
* Confusion Matrix
* Classification Report

**Achieved Accuracy:** XX%
*(Update with your actual result)*

---

## 📁 Project Structure

```
student-performance-prediction/

│── study_performance.csv
│── student_prediction.ipynb
│── README.md
│── images/
│     ├── heatmap.png
│     ├── scatter.png
│     └── confusion_matrix.png
```

---

## 🚀 How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/student-performance-prediction.git
```

2. Install dependencies

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the notebook

```
jupyter notebook
```

---

## 🔮 Future Improvements

* Grade prediction (A/B/C)
* Advanced ML models
* Streamlit Web App
* Model deployment

---

## 👩‍💻 Author

**Sidra Younas**
Data Science Learner | Frontend Developer

---

⭐ If you like this project, don’t forget to star the repository!

# 🏥 Healthcare Readmission Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green)
![Healthcare](https://img.shields.io/badge/Domain-Healthcare-red)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

# 📌 Project Overview

Hospital readmissions are one of the biggest challenges in the healthcare industry because they increase treatment costs and reduce hospital efficiency.

This project focuses on predicting whether a patient is likely to be readmitted to the hospital using Machine Learning techniques. The project includes:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Visualization
- Machine Learning Modeling
- Model Evaluation

The goal is to help healthcare providers identify high-risk patients early and improve patient care.

---

# 🎯 Business Problem

Hospital readmissions can lead to:

- Increased healthcare costs
- Poor patient recovery management
- Higher hospital workload
- Reduced healthcare efficiency

Using Machine Learning, hospitals can:

✅ Identify high-risk patients early  
✅ Improve treatment planning  
✅ Reduce unnecessary readmissions  
✅ Improve healthcare decision-making  

---

# 📂 Dataset Information

The dataset contains healthcare-related patient information such as:

- Age
- Gender
- Time in Hospital
- Number of Medications
- Lab Procedures
- Insulin Usage
- Diagnosis Information
- Admission Type
- Readmission Status

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Visualization |
| Seaborn | Statistical Graphs |
| Scikit-learn | Machine Learning |
| Jupyter Notebook | Development Environment |

---

# 🔄 Project Workflow

```text
1. Business Understanding
2. Data Collection
3. Data Cleaning
4. Exploratory Data Analysis
5. Feature Engineering
6. Model Building
7. Model Evaluation
8. Insights and Conclusion
```

---

# 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Handling missing values
- Removing duplicates
- Feature selection
- Encoding categorical variables
- Data cleaning
- Train-test splitting

---

# 📊 Exploratory Data Analysis (EDA)

EDA was performed to identify patterns and relationships within the healthcare dataset.

---

## 📌 Readmission Distribution

This graph shows the imbalance in the target variable.

- Most patients were not readmitted.
- The dataset is highly imbalanced.

### 📷 Visualization

![Readmission Distribution](images/countplot_readmitted.png)

---

## 📌 Age vs Readmission Analysis

This graph shows how patient age impacts hospital readmission rates.

### Key Insights

- Patients aged 60–80 had the highest readmission count.
- Older patients showed greater risk of readmission.
- Younger age groups had significantly lower readmission rates.

### 📷 Visualization

![Age vs Readmission](images/age_vs_readmission.png)

---

## 📌 Insulin Usage vs Readmission

This visualization analyzes the relationship between insulin usage and patient readmission.

### Key Insights

- Patients with stable insulin usage had lower readmission risk.
- Insulin changes ("Up" and "Down") showed higher readmission tendencies.
- Diabetes management strongly impacts patient recovery.

### 📷 Visualization

![Insulin vs Readmission](images/insulin_vs_readmission.png)

---

## 📌 Time in Hospital vs Readmission

This boxplot shows the relationship between hospital stay duration and readmission.

### Key Insights

- Patients with longer hospital stays showed higher readmission probability.
- Longer treatment duration may indicate severe health conditions.

### 📷 Visualization

![Time in Hospital](images/time_in_hospital_vs_readmission.png)

---

## 📌 Number of Medications vs Readmission

This visualization analyzes medication count against patient readmission.

### Key Insights

- Patients taking more medications were more likely to be readmitted.
- Higher medication counts may indicate complex medical conditions.

### 📷 Visualization

![Number of Medications](images/medications_vs_readmission.png)

---

## 📌 Correlation Heatmap

The heatmap shows relationships between numerical features.

### Key Insights

- Time in hospital and number of medications showed moderate correlation.
- Number of inpatient visits had some relationship with readmission patterns.
- No strong multicollinearity was observed.

### 📷 Visualization

![Correlation Heatmap](images/correlation_heatmap.png)

---

# 🤖 Machine Learning Models

The following models can be used for prediction:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)

---

# 📈 Model Evaluation

The model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1 Score
- ROC Curve

---

## 📌 Confusion Matrix

The confusion matrix shows model prediction performance.

### Key Insights

- The model correctly predicted most non-readmitted patients.
- False negatives still exist and require improvement.
- Class imbalance affected prediction quality.

### 📷 Visualization

![Confusion Matrix](images/confusion_matrix.png)

---

## 📌 ROC Curve

ROC Curve measures the model’s ability to distinguish between classes.

### Key Insights

- The model performed better than random guessing.
- There is still room for improving prediction capability.

### 📷 Visualization

![ROC Curve](images/roc_curve.png)

---

# 📌 Key Findings

✅ Older patients are more likely to be readmitted.  

✅ Longer hospital stays increase readmission risk.  

✅ Patients with higher medication counts showed higher readmission rates.  

✅ Insulin management plays an important role in patient recovery.  

✅ Dataset imbalance affects model performance and should be addressed in future improvements.  

---

# 🚀 Future Improvements

Future enhancements for this project:

- Hyperparameter Tuning
- Feature Importance Analysis
- SHAP Explainability
- SMOTE for Class Imbalance
- Deployment using Flask/Streamlit
- Advanced Ensemble Models

---

# 📁 Project Structure

```text
Healthcare-Readmission-Prediction/
│
├── data/
├── notebooks/
├── images/
├── README.md
├── requirements.txt
└── model.pkl
```

---

# ▶️ How to Run the Project

## Clone Repository

```bash
git clone https://github.com/your-username/Healthcare-Readmission-Prediction.git
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Jupyter Notebook

```bash
jupyter notebook
```

---

# 📌 Requirements

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

# 👨‍💻 Author

## Lucky Singh

Aspiring Data Scientist focused on:
- Machine Learning
- Healthcare AI
- Data Analytics
- Real-world AI Projects

---

# ⭐ Support

If you found this project useful:

⭐ Give this repository a star  
🍴 Fork the repository  
📢 Share with others  

---

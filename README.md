# Stroke Prediction ML Case Study

## 📌 Project Overview

This Machine Learning case study focuses on performing data preprocessing and Exploratory Data Analysis (EDA) on the Stroke Prediction Dataset. The project aims to analyze patient health records and identify important factors that contribute to stroke occurrence using Python-based data analysis techniques.

The case study includes handling missing values, encoding categorical variables, feature scaling, statistical analysis, and multiple data visualization techniques to understand patterns and relationships in the dataset.

---

# 🎯 Objectives

- To preprocess the Stroke Prediction dataset
- To handle missing values and clean the data
- To perform Exploratory Data Analysis (EDA)
- To identify patterns related to stroke occurrence
- To visualize important relationships among features
- To gain practical understanding of Machine Learning preprocessing techniques

---

# 📂 Dataset Information

- **Dataset Name:** Stroke Prediction Dataset
- **Source:** Kaggle
- **Problem Type:** Classification
- **Target Variable:** `stroke`

## Dataset Features

- gender
- age
- hypertension
- heart_disease
- ever_married
- work_type
- Residence_type
- avg_glucose_level
- bmi
- smoking_status
- stroke

---

# 🛠 Technologies & Libraries Used

| Tool / Library | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Handling |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Preprocessing & Scaling |
| Jupyter Notebook | Development Environment |

---

# ⚙️ Data Preprocessing Steps

## ✅ Handling Missing Values
- Checked missing values using `isnull().sum()`
- Filled missing values in the `bmi` column using median values

## ✅ Data Cleaning
- Removed unnecessary columns such as `id`
- Verified data types and cleaned inconsistent values

## ✅ Encoding Categorical Variables
- Converted categorical columns into numerical values using `LabelEncoder`

## ✅ Feature Scaling
- Applied `StandardScaler` on:
  - age
  - avg_glucose_level
  - bmi

---

# 📊 Exploratory Data Analysis (EDA)

The following visualizations were created:

- Stroke Distribution Countplot
- Age Distribution Histogram
- Correlation Heatmap
- BMI vs Stroke Boxplot
- Age vs Glucose Level Scatter Plot
- Hypertension vs Stroke Countplot

---

# 🔍 Key Observations

- Older individuals show higher stroke risk
- Hypertension is strongly related to stroke occurrence
- The dataset contains class imbalance
- BMI and glucose levels influence stroke chances
- Some health-related features show correlation with stroke

---

# 📈 Results and Discussion

The preprocessing techniques improved dataset quality by handling missing values, converting categorical variables into numerical form, and scaling important features. Exploratory Data Analysis helped identify relationships between health-related features and stroke occurrence.

Visualizations provided useful insights into stroke risk factors and patient health patterns.

---

# ✅ Conclusion

This project helped in understanding data preprocessing and exploratory data analysis techniques using a healthcare-based dataset. The analysis successfully identified important feature relationships and improved practical knowledge of Machine Learning data preparation and visualization.

---

# 📷 Outputs Included

- Dataset Overview
- Missing Values Analysis
- Encoded Dataset Output
- Feature Scaling Output
- Statistical Summary
- EDA Graphs

---

# 🔗 Kaggle Dataset Link

https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

---

# 👨‍💻 Author

Sridhar Pedhamanishi
B.E Information Technology  
Data Science & AI/ML Enthusiast

---

# ⭐ Future Improvements

- Apply Machine Learning classification models
- Perform feature selection
- Handle class imbalance using SMOTE
- Build predictive dashboard using Streamlit
- Deploy end-to-end stroke prediction application

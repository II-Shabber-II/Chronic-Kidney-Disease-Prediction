# 🩺 Chronic Kidney Disease Prediction

A comprehensive data analysis and machine learning project for early prediction of Chronic Kidney Disease (CKD), powered by Electronic Health Records (EHR). Visualized through an interactive Power BI dashboard.

---

## 📁 Project Structure
```
Chronic-Kidney-Disease-Prediction/
├── data/ # Raw dataset
│ └── kidney_disease.csv
├── notebooks/ 
│ └── model_code.ipynb
├── visuals/
│ └── CKD Prediction Dashboard.pbix
│ └── Power BI Dashboard.png
├── images/
│ └── Feature-Correlation.png
│ └── SHAP.png
│ └── Target-Class-Distribution.png
├── ckd_predictions_for_powerbi.csv # Predictions for Power BI
└── requirements.txt
```

---

## 🔍 Project Overview

**Objective:** Use machine learning to predict CKD based on patient health parameters and visualize insights using Power BI.

**Dataset:** UCI Chronic Kidney Disease dataset.

**Tech Stack:**
- Python (Pandas, Scikit-learn, SHAP, Seaborn)
- Power BI for interactive dashboard
- Jupyter Notebook
- Git & GitHub

---

## 🧪 Machine Learning Steps

- Data Cleaning & Preprocessing
- Feature Engineering
- Model Training (Random Forest)
- Model Evaluation (Accuracy, ROC-AUC)
- Explainability with SHAP

---

## 📊 Power BI Dashboard Features

- **Donut Chart:** CKD vs Non-CKD Distribution
- **Clustered Column Chart:** Gender vs CKD Status
- **Stacked Column Chart:** Age Groups vs CKD Status
- *(Add correlation heatmap and SHAP plots if access allows)*

*See `visuals/CKD Prediction Dashboard.pbix` or view exported snapshot:*

![Dashboard Overview](visuals/Power%20BI%20Dashboard.png)

---

## 📁 Files Description

| File | Description |
|------|-------------|
| `model_code.ipynb` | Full model pipeline & SHAP explanations |
| `ckd_predictions_for_powerbi.csv` | Model predictions used in Power BI |
| `*.pbix` | Interactive dashboard |
| `requirements.txt` | All Python packages used |

---

## 🚀 How to Run

**1. Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Chronic-Kidney-Disease-Prediction.git
   ```
**2. Install dependencies:**

``` bash
pip install -r requirements.txt
```

**3. Run the notebook:**
   
Open model_code.ipynb in Jupyter.

Run all cells to replicate the model.
  
**4. Open CKD Prediction Dashboard.pbix in Power BI Desktop to explore insights.**

## 📌 Future Work
Add SHAP & Correlation visuals in Power BI.

Enhance model with hyperparameter tuning.

Deploy model as a web app for clinical use.

## 📬 Contact
Author: Shabber Zaidi
Email: shabberimam10@gmail.com
LinkedIn: https://www.linkedin.com/in/shabber-zaidi
GitHub: https://github.com/II-Shabber-II

### ⭐ If you like this project, please give it a star!

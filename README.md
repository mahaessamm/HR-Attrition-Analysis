# HR Employee Attrition Analysis

## Overview
End-to-end data analysis project to identify key drivers of employee turnover and predict attrition risk using the IBM HR Analytics dataset.

## Problem Statement
Why do employees leave? Can we predict who is at risk of leaving?

## Dataset
- **Source:** [IBM HR Analytics Employee Attrition Dataset — Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Size:** 1,470 employees × 35 features
- **Target Variable:** Attrition (Yes/No)

## Tools & Technologies
| Tool | Purpose |
|---|---|
| Python (pandas, NumPy) | Data cleaning & manipulation |
| Seaborn, Matplotlib | Exploratory data analysis |
| Scikit-learn | ML model (Random Forest) |
| Power BI | Interactive dashboard |

## Key Findings
- **16.1%** overall attrition rate (237 out of 1,470 employees)
- **Sales** department has the highest attrition rate
- **Monthly Income** is the strongest predictor of attrition
- Employees working **OverTime** are significantly more likely to leave
- **First-year employees** show the highest attrition risk

## Model Performance
- Algorithm: Random Forest Classifier (100 estimators)
- Accuracy: **84.7%**
- Key challenge: Class imbalance (1,233 No vs 237 Yes)

## Project Structure
```
├── HR_Attrition_Analysis.ipynb   # Main analysis notebook
├── HR-Attrition-Analysis.pdf     # Power BI Dashboard export
└── README.md
```

## How to Run
1. Clone the repository
2. Download the dataset from Kaggle and place it in the same folder
3. Install requirements: `pip install pandas numpy matplotlib seaborn scikit-learn`
4. Open and run `HR_Attrition_Analysis.ipynb`

## Dashboard
Interactive Power BI dashboard includes:
- KPI Cards: Total Employees, Attrition Rate %, Avg Monthly Income
- Bar Chart: Attrition Count by Department
- Line Chart: Attrition Trend by Years at Company
- Slicers: Filter by Department & Job Role

## Author
Maha — Junior Data Analyst | Abu Dhabi, UAE  
[LinkedIn](https://www.linkedin.com/in/mahaessaam) 

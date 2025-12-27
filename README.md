# Econometric and Machine Learning Analysis of Diabetes Risk  
**BRFSS (CDC), Georgia, United States**
---
## Project Overview
This project applies econometric modeling and machine learning techniques to analyze diabetes prevalence using large-scale observational health survey data. The analysis focuses on understanding associations between diabetes and key risk factors, diagnosing the limitations of linear models in aggregated data, and identifying high-risk population groups through classification and risk ranking.
---
## Objective
To analyze diabetes prevalence and risk patterns using behavioral and clinical risk factors, and to evaluate the suitability of econometric and machine learning methods for risk stratification in aggregated public health data.
---
## Data
**Source:** Behavioral Risk Factor Surveillance System (BRFSS)  
**Provider:** U.S. Centers for Disease Control and Prevention (CDC)  
**Region:** Georgia, United States  
**Period:** 2011–2024  
### Data Characteristics
- Aggregated prevalence estimates by population subgroup  
- Observational survey data  
- No individual-level identifiers  
---
## Key Variables
### Outcome
- **Diabetes prevalence (%)**
### Behavioral & Clinical Risk Factors
- Body Mass Index (BMI)
- Smoking prevalence
- Physical inactivity
- High blood pressure
- High cholesterol
### Stratification Variables
- Income
- Education
- Race/ethnicity
- Sex
- Age group
- Year
---
## Methodology
### Exploratory Data Analysis (EDA)
- Summary statistics and prevalence trends  
- Group-wise comparisons across socioeconomic and demographic categories  
- Correlation analysis between diabetes prevalence and risk factors  
- Visualization of inequality patterns over time  
---
## Econometric Modeling
- Multivariate linear regression models with diabetes prevalence as the outcome  
- Heteroskedasticity-robust standard errors  
- Interpretation of coefficients in aggregated observational data  
---
## Machine Learning: Risk Stratification
- Reformulation of diabetes analysis as a **binary classification problem**  
- High-risk groups defined as the **top quantile of diabetes prevalence**  
### Models Implemented
- Logistic Regression  
- Random Forest  
- Gradient Boosting  
---
## Model Evaluation
- Precision  
- Recall  
- F1-score  
- Emphasis on performance under class imbalance  
---
## Limitations
- Aggregated subgroup-level data limits causal interpretation.  
- Results reflect associations and risk stratification, not treatment effects.  
- Findings are specific to Georgia and may not generalize to other regions.  
---
## Tools & Libraries
- Python  
- pandas, NumPy  
- statsmodels (econometric modeling and inference)  
- scikit-learn (machine learning and evaluation)  
- matplotlib, seaborn (visualization)  
---
## Research Context
This project was developed as an independent research portfolio emphasizing:
- Applied econometrics  
- Machine learning for health risk stratification  
- Methodological diagnostics and model evaluation  
---

## License
This project is released under the **MIT License**.

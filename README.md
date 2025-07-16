# Credit Risk Prediction with Logistic Regression and SHAP

This project analyzes credit default risk using logistic regression. The dataset is from [Give Me Some Credit](https://www.kaggle.com/c/GiveMeSomeCredit/data), a classic binary classification task.

## 📊 Project overview

- **Problem**: Predict serious delinquency within 2 years
- **Data**: 150,000+ loan records with borrower info
- **Tech stack**: Python, Pandas, Scikit-Learn, SHAP
- **Approach**:
  - Data cleaning and imputation
  - EDA and visualization
  - Baseline logistic regression
  - Class balancing with `class_weight='balanced'`
  - Model interpretation with SHAP

## 🔍 Key insights

- Income and utilization rate are key drivers of risk
- Class imbalance required careful evaluation
- SHAP improves transparency of decision-making

## 📁 Files

- `credit-risk-logit-shap.ipynb`: full notebook with code and analysis

## 🚀 Next steps

- Try XGBoost or random forest
- Hyperparameter tuning
- Deploy model with Streamlit

---

🧑 Author: Nicolás Vecchioli  
📍 Buenos Aires, Argentina  
📫 [LinkedIn](https://www.linkedin.com/in/nicolas-vecchioli-00893b135)


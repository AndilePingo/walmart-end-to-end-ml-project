# 🛒🛒🛒 Walmart Sales Forecasting & Monitoring🛒🛒🛒

This project predicts weekly sales across Walmart stores using advanced machine learning and modern MLOps tools.

### Key Steps
- **Data Preparation:** Cleaned & feature-engineered time-based and categorical features  
- **Modeling:** Compared Linear Regression, Random Forest, and XGBoost  
- **Tracking:** Logged all experiments with **MLflow**  
- **Monitoring:** Used **Evidently AI** to track data drift and model stability  

### Best Model
- **XGBoost**
  - Train R²: 0.946  
  - Test R²: 0.942  
  - Test RMSE: 5,545  

###  Tools Used
Python, Pandas, Scikit-learn, XGBoost, MLflow, Evidently AI, Matplotlib

###  Insights
- Store 20 is consistently the highest performer  
- Strong seasonal spikes during holiday periods (Q4 each year)  
- No major correlation between departments, but time features influence sales trends  

###  Next Steps (optional)
- Automate report generation (weekly or monthly)
- Deploy model to API or Streamlit dashboard

---

### Created by Andile Pingo

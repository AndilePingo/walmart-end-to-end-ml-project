# 🛒🛒🛒 Walmart Sales Forecasting & Monitoring🛒🛒🛒

### Project highlights
This end-to-end machine learning project demonstrates a complete real-world retail sales forecasting pipeline — from raw data to production-level monitoring. Below are the key highlights:

  1. End-to-End Machine Learning Workflow

   Covers the entire ML lifecycle: data preprocessing, feature engineering, model training, evaluation, experiment tracking, and     monitoring.

Designed for scalability and adaptability to other retail datasets.

  2. Data Preparation and Feature Engineering

   Combines multiple Walmart datasets (train.csv, features.csv, stores.csv, and test.csv) into a clean and structured format.

   Implements advanced feature engineering: holiday flags, year-end indicators, store-level averages, and weekly trends to enhance model   performance.
  3. Model Development and Evaluation

   Trains multiple models — Linear Regression, Random Forest, and XGBoost — to compare predictive performance.

   Evaluates models using RMSE, R², and MAPE on both log-transformed and back-transformed sales data.

   Provides data-driven insights into which algorithms best capture store-level sales patterns.

  4. Experiment Tracking with MLflow

   Tracks all model parameters, metrics, and artifacts (e.g., feature importances, performance plots) using MLflow.

   Enables easy comparison of different model versions and experiments for reproducibility.

  5. Model Monitoring with Evidently AI

   Implements data drift detection and model performance monitoring using the latest Evidently AI Report API.

   Automatically generates monitoring dashboards (monitoring_report.html) stored in the artifacts/ folder.

   Ensures model stability and early detection of input data shifts across time.

  6. Organized Artifact Management

   All generated reports, models, and evaluation results are stored under the artifacts/ directory for transparency and version control.

   Each run creates easily accessible logs for post-analysis and auditing.

  7. Practical and Reproducible Setup

Entire pipeline runs inside a Jupyter Notebook (sales_forecasting.ipynb) for clarity and accessibility.

Lightweight environment ensures compatibility with Windows, macOS, and Linux systems.

## Best Model
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


### 📂 Uploaded Project Files
####1️ Data Files

train.csv, test.csv, features.csv, stores.csv
These files contain the raw and supplemental datasets used for training and evaluating the sales forecasting models.

train.csv: Historical sales data used for model training and validation.

test.csv: Data used for generating final predictions and performance evaluation.

features.csv: Additional contextual features such as holidays, markdowns, and temperature information that enhance model accuracy.

stores.csv: Store-level metadata providing information such as type, size, and other identifiers.

##### 2️ Artifacts Folder

artifacts/
Contains generated outputs from the machine learning pipeline, including trained model files, Evidently AI monitoring reports, MLflow logs, and other experiment artifacts.
These files provide transparency and reproducibility for model performance and data monitoring.

#### 3️ Notebook

sales_forecasting.ipynb
The main Jupyter Notebook that documents the entire end-to-end machine learning workflow — from data exploration and preprocessing to model training (Random Forest, XGBoost), evaluation, and model monitoring using Evidently AI.
This notebook serves as the central reference for the project’s technical implementation.

###  Next Steps (optional)
- Automate report generation (weekly or monthly)
- Deploy model to API or Streamlit dashboard

---

### Created by Andile Pingo

 🏭 Industrial Data Pipeline — Predictive Maintenance

A full Machine Learning pipeline for industrial sensor data to predict machine failures.

### ✔ Includes:
- Synthetic Data Generation
- Data Cleaning & Feature Engineering
- RandomForest & XGBoost Models
- Evaluation: Confusion Matrix + ROC Curve
- Model Explainability with SHAP

## 📂 Project Structure
IndustrialDataPipeline2/
│
├── data/
│   ├── raw/              # synthetic original dataset
│   ├── processed/        # cleaned + engineered dataset
│
├── notebook/
│   ├── 01_generate_dataset.ipynb
│   ├── 02_preprocess.ipynb
│   ├── 03_train_model.ipynb
│   ├── 04_model_evaluation.ipynb
│
├── models/               # saved ML models (.pkl)
├── results/              # evaluation plots exported here
└── .gitignore            # ignore unnecessary files

### 📊 Model Performance Summary

| Metric       | RandomForest | XGBoost |
|-------------|-------------|---------|
| Accuracy    | 0.9994      | 0.9988  |
| Recall      | 0.80        | 1.00    |
| F1-score    | 0.89        | 0.83    |
| ROC-AUC     | 1.00        | 1.00    |

📊 Confusion Matrix
RandomForest:
![](results/confusion_matrix_RandomForest.png)

XGBoost:
![](results/confusion_matrix_XGBoost.png)


📈 ROC Curve
### ROC Curve Comparison

![](results/roc_curve_comparison.png)

🔍 SHAP Explainability
### SHAP Summary (RandomForest)
![](results/shap_summary_rf.png)

### SHAP Bar Plot (RandomForest)
![](results/shap_bar_rf.png)

### SHAP Summary (XGBoost)
![](results/shap_summary_xgb.png)

## 🚀 Future Work
- Deploy model as Web Service (API)
- Real production sensor data ingestion
- Live monitoring dashboard

📌 Contributor: Sahar Dolatyar  




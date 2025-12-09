# Industrial Data Pipeline (Predictive Maintenance)

A machine learning pipeline for industrial sensor data including:
✔ Data Generation  
✔ Preprocessing  
✔ RandomForest + XGBoost Models  
✔ Model Evaluation (Confusion Matrix + ROC Curve)  
✔ SHAP Explainability 

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
└── .gitignore

📊 Model Performance
RandomForest vs XGBoost
Model           Accuracy      Recall      F1-score      ROC-AUC
RandomForest    0.9994        0.80        0.8889        1.00
XGBoost         0.9988        1.00        0.8333        1.00

🔹 Confusion Matrix
RandomForest vs XGBoost:
![Confusion Matrix RF](results/confusion_matrix_rf.png)
![Confusion Matrix XGB](results/confusion_matrix_xgb.png)

🔹 ROC Curve


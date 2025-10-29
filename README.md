# **Obesity Diagnosis Model with Streamlit Deployment**

This project aims to classify individuals into seven obesity levels based on lifestyle and health-related attributes using tabular data. The task focuses on building an accurate machine learning model and deploying it as an interactive web application.

**Tools**: Python, Scikit-learn, FastAPI, Streamlit, Joblib, Pandas, NumPy

**Approach**: Compared Random Forest and XGBoost models for multiclass classification. The best-performing model was saved as a .pkl file and deployed using a FastAPI backend connected to a Streamlit frontend with a custom-designed UI.

**Results**: XGBoost achieved the highest accuracy (96.17%) and near-perfect F1-scores across most classes, effectively identifying high-risk obesity types.

**Key Insight**: XGBoost proved slightly superior to Random Forest, showing strong generalization and reliability for healthcare risk prediction. The deployment pipeline demonstrates a complete end-to-end system, from model training to real-time prediction.

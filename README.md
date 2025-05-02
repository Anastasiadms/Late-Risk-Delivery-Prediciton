# Predicting Late Delivery Risk using Advanced Machine Learning 📦

This projects demonstrate a full-cycle machine learning solution - from data processing and feature engineering to model training, optimization, and explainability using the Dataco Smart Supply Chain dataset from Kaggle.I built predictive models to identify whether a delivery is at risk of being late, applying best practices in classification modeling, class balancing using SMOTE, and SHAP-based interpretability.

# Project Aim and Objectives
**Project Aim :** 
The primary goal of this project is to design and evaluate advanced machine learning models to predict the risk of late deliveries accurately using historical logistics data. By classifying deliveries as either on-time or delayed, the project aims to assist in identifying potential disruptions and improving overall supply chain efficiency.

**Objectives :**
1) Build and train advanced advanced machine learning models (Random Forest, Gradient Boosting, and ANN) to predict late delivery risk.
2) Evaluate and compare model performances
3) Identify and interperet the most influential features contributing to late deliveries using explainable tools.
4) Suggest a practical solution that can reduce delivery delays.

# What I did
- Cleaned and transformed the dataset.
- Created relevant features that may help the classification.
- Balanced data using SMOTE to address class imbalance.
- Trained and tuned the models (Random Forest, GBM, ANN with Keras).
-  Used `GridSearchCV` for model optimization.
-  Explained feature contributions using SHAP for business transparency.

# Key Business Insights
1) **Shipping delay** is the most predictive feature; reinforcing the need for real-time tracking.
2) **Expedited shipping** significantly reduces risk, suggesting it as a key intervention strategy.
3) **SHAP explainability** enables trust and transparency for stakeholders, allowing the model to support operational decision-making.

# Model Performances Summary
| Model              | Accuracy | ROC AUC | Strength                            |
|-------------------|----------|---------|-------------------------------------|
| Random Forest      | 97.54%   | **0.989** | Best balance of accuracy & explainability |
| Gradient Boosting  | **97.56%** | 0.982   | Slightly better raw accuracy        |
| ANN (Keras)        | 97.54%   | 0.973   | Perfect recall, ideal for risk cases |

---

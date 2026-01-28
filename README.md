# Credit Risk Modeling using XGBoost & SHAP

## Objective
Build a predictive model to assess customer credit risk and
identify key factors contributing to loan default.

## Tools
Python, Pandas, NumPy, Scikit-learn, XGBoost, SHAP

## Approach
- Cleaned and preprocessed customer financial data
- Engineered time-based and categorical features
- Built and tuned XGBoost classification model
- Evaluated model using ROC and accuracy metrics
- Applied SHAP for model explainability and feature importance

## Key Insights
- Income stability and credit history were major risk indicators
- Certain customer segments showed significantly higher default probability
- SHAP analysis provided transparent interpretation of model decisions

## Screenshots
[Neural Network Final Model](assets/Neural_Network_Final_Model.png)
[Neural Network Grid Search](assets/Neural_Network_Grid_Search.png)
[XGBoost Final Model](assets/XGBoost_Final_Model.png)
[XGBoost SHAP Analysis](assets/XGBoost_SHAP_Analysis.png)
[auc_curve](assets/auc_curve.png)

## How to Run
pip install -r requirements.txt
Run the notebook in the `notebooks/` folder.

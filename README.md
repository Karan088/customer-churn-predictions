# customer-churn-predictions
To develop and deploy a machine learning model that can predict customer churn using business and customer profile data, helping businesses to take informed retention actions.

✅ Features
End-to-end pipeline: preprocessing → feature selection → modeling → deployment ready

XGBoost with class weights and hyperparameter tuning

Manual oversampling for imbalance handling

Feature importance analysis for interpretability

Saved, reusable pipeline for deployment


*  Run the notebooks to explore, train, and evaluate the model

```
customer-churn-predictions/
│
├── data/
│   └── raw_data.csv              
│
├── churn-prediction-class-balancing.ipynb  #Complete end to end notebook  
│   
├── models/
│   └── churn_model_pipeline.pkl         # Saved pipeline (preprocessor + model)
│
├── scripts/
│   └── predict_sample.ipynb               # Example python notebook for making predictions using saved model
│
├── README.md                            # Project overview and instructions
```

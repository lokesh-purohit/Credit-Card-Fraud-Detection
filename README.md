**Credit Card Fraud Detection**

(This project is based on a popular dataset on Kaggle: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

This repository presents a comparative analysis of various Machine Learning models to identify fraudulent transactions. It includes data preprocessing, exploratory data analysis, model development, model evaluation, and a Tableau dashboard for interactive visualizations. A detailed Executive Summary highlights key findings and recommendations.

Project Overview:

The primary goal of this project is to differentiate fraudulent transactions from legitimate ones using a variety of Machine Learning techniques. Core aspects include:
	•	Data Preprocessing & Exploration: Cleaning raw data, handling class imbalance, and performing feature engineering.
	•	Model Development & Evaluation: Training, tuning, and comparing multiple classifiers to detect fraud.
	•	Interactive Visualizations: Creating a Tableau dashboard to provide clear, data-driven insights.

 Models & Methodology:

  The following supervised Machine Learning models were trained and compared:
  •	Logistic Regression
  •	Linear Discriminant Analysis (LDA)
  •	Decision Tree
  •	Random Forest
  •	XGBoost
  •	CatBoost

 Key Insights:

 	•	Recall is crucial in fraud detection to ensure as many fraudulent transactions as possible
    are caught.
	•	Precision-Recall Trade-Off: High recall typically reduces precision, leading to more false
     positives—an acceptable trade-off in many fraud scenarios.
	•	Feature Importance: Certain features (e.g., V14, V12, V1, V8, V4, V11, V21) and the
     transaction amount stood out as significant indicators of fraudulent behavior.

 Performance Metrics:

 All models were evaluated using standard classification metrics:
 	•	Accuracy: Overall proportion of correct predictions.
	•	F1 Score: Harmonic mean of precision and recall, useful for imbalanced datasets.
	•	Precision: Fraction of predicted fraud cases that were actually fraud.
	•	Recall (Sensitivity): Proportion of actual fraud cases correctly identified.
	•	ROC_AUC: Measures the model’s ability to discriminate between fraud and non-fraud.


CatBoost emerged as the best-performing model with:
	•	F1 Score: 83%
	•	Precision: 93%
	•	Recall: 76%
	•	ROC_AUC: 98%

 You can explore these visualizations by opening the .twbx file with Tableau Desktop using this link: https://drive.google.com/drive/folders/1haI_5zpZUv74If1wtuliNstXpl1jrRDL?usp=drive_link
 
 or Tableau Public using this link: https://public.tableau.com/views/CreditCardFraudPredictiveModelsVisualizations/Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

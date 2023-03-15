# Superstore-EDA-with-Profit-loss-Classification
Super Store profit-loss Classification (Part-1:Classification)

It's one of mine ML Multi-class classification project with EDA , here I've implemented the following tools and methods for classification.
- Data Pre-processing : NumPy, pandas, Synthetic Minority Over-sampling Technique (SMOTE, for processing imbalanced data)
- Data Visualization : Seaborn, Matplotlib, Plotly
- Data Transformation and Scaling : Label Encoding, Created pipeline containing Robust scaler and Standard Scaler
- Classifier : Voting classifier with estimators KNN, Logistic Regression, Random Forest, Gradient Boosting , for each estimator I've used Gradient Search for hyperparameter tuning.
- Validation : Implemented Stratified K-fold
- Feature Selection : Compared before and after feature selection performances using Kbest for K ranging from 4 to total features
- Accuracy : 96.57%

Part-2:Prediction of profit-loss values instead of classifying the records as profitable and non-profitable

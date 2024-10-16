# Parkinson-Disease-Detection
Detecting Parkinson's Disease using various machine learning models. The dataset initially shows a class imbalance, with a significantly lower number of healthy samples compared to Parkinson's cases. To counter this, SMOTE (Synthetic Minority Oversampling Technique) is employed to balance the dataset.

## Key Observations:
Features like spread1, PPE, and spread2 show strong positive correlations with the disease status, making them valuable predictors.
Conversely, features like HNR, MDVP:Fo(Hz), and MDVP:Fhi(Hz) have strong negative correlations and are also crucial for predictions.

## Data Processing:
PCA is implemented to select features that capture at least 95% of the total variance, which are then used for training the models.
Standardization of features is performed to ensure equal consideration during model training.

## Model Implementation:
Several models are implemented and evaluated:
1.Logistic Regression
2.Random Forest
3.K-Nearest Neighbors (KNN)
4.Gradient Boosting Machines (GBM)
5.XGBoost
6.LightGBM
7.CatBoost

## Result:
After testing various algorithms, CatBoost and LightGBM are found to outperform others in accurately detecting Parkinson's Disease.

## References
<a id="1">[1]</a>
'Exploiting Nonlinear Recurrence and Fractal Scaling Properties for Voice Disorder Detection',
Little MA, McSharry PE, Roberts SJ, Costello DAE, Moroz IM.
BioMedical Engineering OnLine 2007, 6:23 (26 June 2007)

https://www.kaggle.com/code/saikiranbaghavathula/smote-pca-k-fold-comparison-of-7-ml-algorithms


# Cirrhosis Survival Prediction
## Overview
This project uses Machine Learning (ML) models to predict cirrhosis patient survival, integrating data analysis, preprocessing, and advanced modeling techniques. 

## Techniques used
### Data Analysis and Preprocessing
- Identification and treatment of variables that require preprocessing to ensure data quality and readiness for analysis.
- Separate handling and preprocessing strategies for numerical and categorical data to optimize their utility in predictive modeling.
- Analysis of variables in relation to the target outcome to identify significant predictors.
- Identification and treatment of outliers to improve model accuracy and robustness.
- Techniques applied to manage missing values and encode categorical variables for model readiness.
- Addressing data imbalance to ensure model fairness and accuracy across different patient profiles.

### Variable Preparation
- **Normalization and Visualization:** Applying normalization techniques to variables and visualizing the effects to ensure uniform scale across features.
- **Correlation Matrix:** Development of a correlation matrix to identify and eliminate redundant variables, enhancing model efficiency.
- **Principal Component Analysis (PCA):** Reduction of dimensionality to improve model performance and interpretability.

## Model Definition and Evaluation
- **Selection of Machine Learning Models:** The practice includes the deployment of models such as K-Nearest Neighbors (KNN), Decision Trees, and Support Vector Machines (SVM) and Explainable Boosting Machine (EBM).
- **Metric Definition:** Definition and application of evaluation metrics to assess model performance accurately.

## Results
The SurvivalPredictionCirrhosis project successfully applies an SVM model to predict survival rates in cirrhosis patients, outperforming other models like KNN and Decision Trees in accuracy, F1-Score, and recall. Despite SVM's computational demands and sensitivity to hyperparameter settings, its proficiency in handling complex, high-dimensional data and minimizing overfitting risks stands out. Notably, the model demonstrates excellent generalization capabilities, evidenced by its recovery in test set performance after a drop in validation results.

## Conclusion
The Cirrhosis Survival Prediction Project exemplifies the integration of machine learning into healthcare, aiming to revolutionize patient care through accurate predictions and actionable insights. The detailed practice underscores the potential of data science and machine learning techniques in improving outcomes and supporting healthcare decisions in the domain of cirrhosis treatment.

# diabetic_readmit
This project aimed to create a machine-learning project to predict hospital readmissions of diabetic patients. This would be useful as such a model would preemptively identify the patients at risk of readmission and alert physicians to take action so they need not return. This in turn would minimize hospital costs for the visit. Logistic regression, Random Forest, Support Vector Machine, and XGBoost models were cross-validated; the Random Forest model was selected as the final predictive model with an F1 score of 0.292 compared to a baseline of 0.198, a 47.47% improvement in balancing precision and recall, resulting in higher accuracy in identifying positive instances while minimizing false positives for improved patient outcomes and reduced hospital costs.
Python version 3.11.4 was used in addition to pandas version 2.0.3, NumPy verison 1.24.4, Matplotlib version 3.7.2, sci-kitlearn verison 1.3.0, XGBoost version 1.7.6, and shap version 0.42.1. 

The results of the Random Forest, Support Vector Machine, and XGBoost models can be downloaded from this zip file: https://drive.google.com/file/d/1sVMRH11pgc_yU2QpbVP9SRFwpnj3NNLA/view?usp=sharing. The results of the Logistic Regression model can be found in the results folder.

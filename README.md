# Breast-Cancer-Diagnosis-Advanced-Stats-Computing
This project focuses on the challenge of accurately predicting whether a tumor is malignant (cancerous) or benign (non-cancerous) using cell characteristics. Our key questions were: Which predictive model best classifies tumors as malignant or benign? Which cell features are most important for accurate predictions?

We applied feature selection tecniques such as forward selection, lasso regression, and ridge regression methods to identify the most relevant predictors. In addition, we evaluated classication models like Logistic Regression, Ridge Classifier, and Generalized Additive Model. 

From our results, we selected the Ridge Regression for feature selection and applied the Generalized Additive Model to the features. Once we evaluated the performance of the model using accuracy, ROC-AUC, Recall, and F-1 Score, we determined that our model performs well in classifying cancer cases for different goals. For the goal of detecting as many malignant cases as possible, GAM is better. For a simple, consistent model, then Ridge Regression is the best choice.

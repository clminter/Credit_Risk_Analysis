# Credit_Risk_Analysis
## Overview
Evaluation of data with unbalanced classes using oversampling, undersampling and a combinational approach in order to compare machine learning models that reduce bias and predict credit risk.

## Results
 - Naive Random Oversampling
   ![image](https://user-images.githubusercontent.com/81878169/132171103-cce5c8b9-14b7-4512-ad31-e964e0b4c017.png)

- SMOTE Oversampling
  ![image](https://user-images.githubusercontent.com/81878169/132171183-ae96b5f4-0e26-44f9-bad0-679d0d940abe.png)

- Undersampling
  ![image](https://user-images.githubusercontent.com/81878169/132171284-3254dcd3-0ad1-41a5-ac4f-c83f2ea217d7.png)

- Combination (Over and Under) Sampling
  ![image](https://user-images.githubusercontent.com/81878169/132171403-3cc5fc3e-e326-4bfb-8b34-18598f34705a.png)
  
- Balanced Random Forest Classifier
  ![image](https://user-images.githubusercontent.com/81878169/132171805-2d13c448-e534-4aed-bcb5-f697b68507cb.png)

- Easy Ensemble AdaBoost Classifier
  ![image](https://user-images.githubusercontent.com/81878169/132171959-adfb5a6a-948e-441b-ab0c-791929de2355.png)



## Summary
- The F1 score for the high_risk category for all models indicates a high imbalance between sensitivity and precision. The opposite is true for the low_risk category.
- The algorithms for all 6 models are successful in predicting credit worthiness for the low_risk category.
- The algorithms are NOT useful for predicting credit worthiness for the high_risk category.

The support number clearly indicates a very unbalanced dataset; a lot of data for the low_risk category and very little data for the high_risk category.  The Easy Ensemble AdaBoost Classifier model makes the best attempt at balancing this incongruity, but still falls short. In order to more fairly evaluate high risk customers, more data is needed to model results with higher precision.

# Credit-Risk-Analysis

The purpose of this analysis is to demonstrate skills in data preparation, statistical reasoning, and machine learning. With imbalanced-learn and scikit-learn libraries to build models using resampling, we will employ different techniques to train and evaluate models with unbalanced classes.

# Results:


# Naive Random Oversampling:
Accuracy Score: 65%
High Risk Precision: 1%
High Risk Recall: 62%


<img width="919" alt="17 1" src="https://user-images.githubusercontent.com/92793248/154369863-347b9d24-8db9-42f4-8b8b-e27e6dbcfff8.png">


# SMOTE Oversampling
Accuracy Score: 64%
High Risk Precision: 1%
High Risk Recall: 63%


<img width="919" alt="17 2" src="https://user-images.githubusercontent.com/92793248/154369888-3ae093ea-219f-44cf-b870-0370e3cf14e8.png">


# Undersampling
Accuracy Score: 53%
High Risk Precision: 1%
High Risk Recall: 61%


<img width="919" alt="17 3" src="https://user-images.githubusercontent.com/92793248/154369903-8a3f2b67-c2fa-420c-b74c-5a3fe178ad42.png">


# Combination (Over and Under) Sampling
Accuracy Score: 62%
High Risk Precision: 1%
High Risk Recall: 68%


<img width="919" alt="17 4" src="https://user-images.githubusercontent.com/92793248/154369931-46d2e5dd-08d2-4f4d-a87b-f06c9ac0feaf.png">


# Balanced Random Forest Classifier
Accuracy Score: 79%
High Risk Precision: 4%
High Risk Recall: 67%


<img width="1080" alt="17 5" src="https://user-images.githubusercontent.com/92793248/154369940-fcefbe06-7b1c-4e4b-a2db-a58b1bdd280e.png">


# Easy Ensemble AdaBoost Classifier
Accuracy Score: 93%
High Risk Precision: 7%
High Risk Recall: 91%


<img width="1080" alt="17 6" src="https://user-images.githubusercontent.com/92793248/154369955-47ce2d20-3d49-4119-926a-86b6b0dde6ba.png">


# Summary: 


Easy Ensemble AdaBoost Classifier out-performed the other models. The Easy Ensemble learning model makes predictions based of several different models. By combining multiple models, it increases the performance and accuracy of the model. This is important when classifying high risk credit candidates for loans. However, too many of the low risks were incorrectly detected as high risks. This will potentially cause a lot of unnecessary trouble to the lender.

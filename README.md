# Online-Shoppers-Purchasing-Intention

**Context**
The data used in this analysis is an Online Shoppers Purchasing Intention data set provided on the UC Irvine’s Machine Learning Repository. The data set was formed so that each session would belong to a different user in a 1-year period to avoid any tendency to a specific campaign, special day, user profile, or period. The primary purpose of the data set is to predict the purchasing intentions of a visitor to this particular store’s website.

**Objective**
The objective of this project is to use classification models in order to predict whether the user will make a purchase or not(make revenue or not).

**Process**
Before training the classification models, the dataset had to go through some data preprocessing and feature engineering.

  1)Handling missing values
  2)performing EDA
  3)Handling ouliers
  4)Encoding categorical variable
  5)Feature Scaling
  6)Feature Selection

**Model Building**
Because the dataset is imbalanced, oversampling and undersampling was applied using SMOTE and the RandomUnderSampler.

Cross-validation was also used in order to avoid overfitting. For that K-Fold cross validation is applied.

The classification models that were trained were the following:

                1.Logistic Regression
                2.Decision Tree Classifier
                3.Random Forest Classifier
                4.SVC
                5.Gradient Boosting Classifier

After Building the model, by using the evaluation metrics of classification model select best model to predict whether the customer will make a purchase or not.

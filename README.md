Object: Predict telco customer churn

Method and Models: 
  1. Impute missing value with mean, median, or the value from the previous row, depends on column's distribution
  2. Transform text and categorical attributes to proper value
  3. Split data into training and testing datasets
  4. Used MinMaxScaler() to scaling data
  5. Used GridSearchCv and corss-validation to find the best parameters
  6. Applied classification models: KNN classification, Logistic Regression, Linear Support Vector Machine, Kerenilzed Support Vector Machine (rbf, poly, and linear), Decision Tree
  7. Applied voting classifiers (hard voting and soft voting), bagging and pasting, adaboost boosting, and gradient boosting
  8. Applied PCA to dataset and then applied to all classification models above
  9. Applied deep learning 

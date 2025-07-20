## Heart Disease Prediction Using Logistic Regression — Summary

- **Objective:**  
  Predict the risk of heart disease based on patient health indicators from the Framingham Heart Study dataset.

- **Dataset:**  
  Data loaded from a CSV file containing variables like age, cholesterol, blood pressure, smoking status, diabetes, and more.

- **Data Exploration & Preprocessing:**  
  - Loaded dataset and viewed the first few rows.  
  - Checked for missing values and handled them appropriately (e.g., imputation or removal).  
  - Selected relevant features for prediction.  
  - Converted categorical variables if needed.  
  - Split data into training and testing sets.

- **Model Used:**  
  Logistic Regression was chosen because the target variable (`TenYearCHD`) is binary (presence or absence of heart disease risk within 10 years).

- **Training:**  
  The logistic regression model was trained on the training data with selected features.

- **Evaluation:**  
  - Model predictions were evaluated on the test set.  
  - Metrics used include accuracy, confusion matrix, and classification report (precision, recall, F1-score).  
  - Visualized confusion matrix using a heatmap for better interpretation.

- **Results & Conclusion:**  
  The logistic regression model showed promising performance in predicting heart disease risk, indicating it is a useful tool for early detection based on clinical and lifestyle features.

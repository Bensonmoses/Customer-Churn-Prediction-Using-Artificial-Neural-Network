# Customer-Churn-Prediction-Using-Artificial-Neural-Network (DL)

In this project, we tackle the challenge of predicting customer churn using a dataset with details like CreditScore, Geography, Gender, Age, and more. The first step involved cleaning the data by dropping irrelevant identifiers. We then checked for missing values to ensure data integrity. Recognizing the importance of understanding our data, we visualized key demographics and financial behaviors through histograms.

Next, we prepared our dataset for machine learning by encoding categorical variables and splitting the data into training and testing sets. This was followed by normalizing the data to improve model performance. We employed Logistic Regression and Support Vector Machine (SVM) classifiers as our initial predictive models. To address the imbalance in our dataset, which could skew predictions, we used the SMOTE technique, enhancing the representation of minority classes and potentially improving model accuracy.

We further refined our models by optimizing their parameters, specifically conducting a grid search for the SVM model to find the best combination of 'C', 'gamma', and 'kernel'. Our evaluation focused on accuracy, precision, recall, and F1 score, providing a holistic view of model performance.

This project illustrates the comprehensive process of data preparation, feature engineering, model training, and optimization in predictive modeling. Our objective was to develop a reliable model for predicting customer churn, enabling the implementation of effective retention strategies. Through iterative analysis and refinement, we aimed to enhance the accuracy of our predictions, offering valuable insights for reducing churn and fostering customer loyalty.

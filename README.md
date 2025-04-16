# Customer Churn Prediction

The dataset used in this project comes from Kaggle (https://www.kaggle.com/datasets/royjafari/customer-churn/data). It includes information about customers of a fictional telecom company, with features related to their demographics, service subscriptions, account history, and billing — along with a churn label indicating whether they left the company.

##  Problem Statement

Churn hurts long-term business growth, especially for subscription-based services. This project aims to build a machine learning model that predicts whether a customer is likely to leave, based on their account history, usage patterns, and demographics — helping businesses take action before it’s too late.

## Project Workflow
#### 1. Data Exploration
Conducted summary statistics and visualized distributions through histograms and countplots to understand feature characteristics.

#### 2. Data Preprocessing
Handled missing values, removed duplicates, encoded categorical variables, and scaled numerical features for modeling.

#### 3. EDA (Exploratory Data Analysis)
Explored feature correlations and visualized relationships using a heatmap. Removed highly correlated variables to reduce multicollinearity.

#### 4. Model Building
Built a Logistic Regression model, used cross-validation and hyperparameter tuning, and selected the L1 regularization model based on its highest accuracy and better precision and recall scores compared to other models. The L1 regularization also helped with feature selection and addressing multicollinearity.

#### 5. Evaluation
Evaluated model performance with metrics like Accuracy (91.40%), Precision (91.67%), Recall (49.44%), F1-Score (64.23%), and ROC AUC (92.82%).

#### 6. Conclusion
The model performed well, with high precision and ROC AUC, but recall could be improved. Next steps involve exploring techniques to boost recall, such as ensemble models or neural networks.s


## Contact

For questions or feedback, feel free to reach out via https://www.linkedin.com/in/hamza-younus-a1740b1b2/

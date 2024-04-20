Mushroom Classification Project:

This project aims to classify mushrooms as edible or poisonous based on their characteristics using machine learning algorithms.

1. Dataset Overview
The dataset used in this project is "mushrooms.csv", containing 8124 instances of mushrooms with 23 features like cap-shape, cap-surface, cap-color, bruises, odor, etc.

Shape of the Data: (8124, 23)
Missing Values: No missing values found in the dataset.

2. Data Preprocessing
   
Categorical Encoding: Encoded categorical variables using one-hot encoding.

Feature Selection: Removed irrelevant features like 'veil-type' from the dataset.

4. Exploratory Data Analysis (EDA)
   
Univariate Analysis: Examined the distribution of each feature individually to understand its importance.

Multivariate Analysis: Investigated relationships between features and the target variable ('class').

6. Feature Importance Analysis
   
Identified important features using correlation analysis. Notable features include 'gill-color' and 'odor'.

8. Model Training and Evaluation
   
Trained a Decision Tree classifier on the dataset.
Utilized cross-validation to evaluate the model's performance using accuracy, precision, recall, and F1-score metrics.

Results
The Decision Tree model achieved the following average scores across different evaluation metrics:
Accuracy: 0.914305115574081,
Precision: 0.9940520446096655,
Recall: 0.9346938775510203,
f1 : 0.9579567418315692}

Conclusion
This project demonstrates the use of machine learning techniques to classify mushrooms based on their characteristics. By analyzing feature importance and evaluating model performance, we can build a reliable classifier for mushroom classification tasks.

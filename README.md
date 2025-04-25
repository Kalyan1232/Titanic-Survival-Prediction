# Titanic-Survival-Prediction

Using Machine learning algorithm on the famous Titanic Disaster Dataset for Predicting the survival of the passenger
                                                                    
This project aims to predict Titanic passenger survival using features like age, gender, and class. The steps followed include:

1. Data Import and Exploration
The dataset was loaded using pandas, and basic exploration was done to understand its structure and identify missing values. Key features include Pclass, Sex, Age, SibSp, Parch, Fare, Embarked, and Survived (target variable).

2. Data Preprocessing
Handling Missing Values: Missing values in Age were filled with the median, and in Embarked with the most frequent value.

Encoding Categorical Variables: Categorical variables like Sex and Embarked were encoded using Label Encoding.

Feature Selection: Relevant features were selected for training, and the target variable (Survived) was separated.

3. Model Selection
Various classification models were explored, including Naive Bayes, Logistic Regression, Decision Tree, Support Vector Machines (SVM), and K-Nearest Neighbors (KNN). The dataset was split into 80% training and 20% testing. Each model was trained on the training set, and their performances were assessed to determine the most suitable approach.

4. Model Evaluation
The models were evaluated using metrics such as accuracy, confusion matrix, and the classification report, which included precision, recall, and F1-score. Comparisons were made across all models to identify strengths and weaknesses.

5. Results
The accuracy scores of the models guided the final selection process. Based on these scores, models like Naive Bayes and Logistic Regression showed higher accuracy, while others like Decision Tree, SVM, and KNN provided additional insights and potential for specific scenarios. Further improvements could be made by exploring hyperparameter tuning and additional algorithms to refine the overall performance.



Dependencies:

    Python3
    Numpy
    Pandas
    Matplotlib
    Supervised Learning
    Machine Learning Algorithm
    Classification Algorithms
    
This Notebook will show basic examples of:

    Data Handling
    Importing Data with Pandas
    Cleaning Data
    Exploring Data Analysis

Data Analysis:

Supervised Machine learning Techniques: + Logit Regression Model + Plotting results + Support Vector Machine (SVM) using 3 kernels + Basic Random Forest + Plotting results.

# MIT-Earth-Hacks
MIT Earth Hacks
# Customer Churn Prediction

This project aims to predict customer churn in a banking environment using various machine learning techniques. **By understanding the factors influencing customer churn, we can develop strategies to improve customer retention.**

## **Project Overview**

This project was completed as part of the **IE 7275: Data Mining in Engineering** course at **Northeastern University**.

## **Project Structure**

The repository contains the following files and directories:

- `data/`: Contains the dataset used for the project.
- `notebooks/`: Jupyter notebooks detailing the analysis and model building steps.
- `src/`: Python scripts for data preprocessing, feature engineering, and model evaluation.
- `README.md`: Project overview and setup instructions.

## **Dataset**

The dataset used for this project was sourced from **Kaggle**: [Churn Modelling Dataset](https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling/data). **It contains 10,000 rows and 14 columns, including customer attributes such as credit score, geography, gender, age, tenure, balance, number of products, cardholder status, activity level, estimated salary, and churn status.**

## **Installation**

To run the project, you need to have **Python** installed. You can install the required dependencies using pip:

## ```bash
pip install -r requirements.txt

##  Data Preprocessing

The data preprocessing steps include:

1. Checking for null values and duplicates.
2. Dropping irrelevant columns (RowNumber, CustomerId, Surname).
3. Renaming the target variable Exited to ChurnedOrNot and encoding its values.
4. Applying one-hot encoding to categorical features.
5. Addressing class imbalance using SMOTE.
6. Exploratory Data Analysis (EDA)
7. We performed EDA to understand the relationships between features and customer churn. Visualizations included histograms, scatter plots, and correlation matrices.

## Feature Engineering
New features were created to enhance model accuracy. Examples include:

1. Categorizing customers based on the number of products.
2. Grouping customers based on their account balance.
3. Model Building and Evaluation
4. We used several machine learning models to predict customer churn:

- Logistic Regression
- Decision Tree 
- Random Forest

## Results
The models were evaluated based on accuracy, precision, recall, F1 score, and AUC-ROC. The best-performing model was selected for predicting customer churn.

## Conclusion
This project demonstrated the effectiveness of machine learning techniques in predicting customer churn. By identifying key factors influencing churn, banks can develop targeted strategies to improve customer retention.

## License
This project is licensed under the MIT License.

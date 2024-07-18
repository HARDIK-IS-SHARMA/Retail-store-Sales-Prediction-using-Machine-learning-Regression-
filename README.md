# Big-mart Analysis Using Machine Learning


![bigmart](https://github.com/user-attachments/assets/1527e450-5545-42ff-b05e-b21f5e5570e4)



## Objective
The objective of this project is to predict the sales of various products using Big Mart sales data to determine which product will have the highest sales potential. By accurately forecasting sales, the aim is to provide actionable insights that will help the business prioritize products and develop strategies to maximize revenue and growth. This will be achieved using supervised machine learning regression algorithms to analyze historical sales data and predict future trends. The ultimate goal is to support the business in making data-driven decisions that enhance product performance and business growth.

## Data Preprocessing and Exploratory Data Analysis (EDA)
In this project, I performed data preprocessing by filling null values with the mean and mode of their respective columns. I also conducted an Exploratory Data Analysis (EDA), using Seaborn and Matplotlib to plot graphs and uncover insights.

## Data Encoding
Next, I labeled all categorical columns with numerical values using Label Encoder, preparing the data for prediction analysis.

## Model Training and Evaluation
I split the data into training and testing datasets. Then, I evaluated multiple regression models to determine which provided the best accuracy based on the R² score and Mean Squared Error (MSE). The models tested were:

- **Linear Regression**: A simple algorithm that assumes a linear relationship between input variables and the target variable.
- **Random Forest**: An ensemble method that uses multiple decision trees to improve prediction accuracy and control overfitting.
- **Gradient Boosting**: An ensemble technique that builds models sequentially, with each model correcting errors made by the previous ones.
- **Support Vector Regression**: A type of Support Vector Machine that supports linear and non-linear regression, focusing on minimizing error within a certain threshold.
- **XGBoost**: An optimized implementation of Gradient Boosting that is designed for speed and performance.

Among these, the **Gradient Boosting** algorithm achieved the highest accuracy.


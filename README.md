# Medical_Cost_Analysis
In this project, Itried to develop an end-to-end data science application using the
dataset given above. The aim of the project is to estimate the approximate cost of a person's
health insurance based on the given variables. While creating the project, I tried to follow the
instructions below and make sure that the project is unique.
* Dataset: https://www.kaggle.com/datasets/mirichoi0218/insurance

1. Importing Required Libraries
  * Import the required libraries for the project.
  * Import Pandas, NumPy, Seaborn, Matplotlib and Sklearn libraries for data analysis
2. Perform An Exploratory Data Analysis
  * Analyze the data and draw meaningful conclusions from the data.
    - Examine the distribution of Bmi (Body Mass Index)
    - Examine the relationship between “smoker” and “charges”
    - Examine the relationship between “smoker” and “region”.
    - Examine the relationship between “bmi” and “sex”.
    - Find the "region" with the most "children".
    - Examine the relationship between “age” and “bmi”.
    - Examine the relationship between “bmi” and “children”.
    - Is there an outlier in the "bmi" variable? Please review.
    - Examine the relationship between “bmi” and “charges”.
    - Examine the relationship between “region”, “smoker” and “bmi” using bar plot.
  * Try to use data visualization techniques as much as possible while examining the data.
3. Data Preprocessing
  * In this section, prepare the data you have, for training the model.
  * Use Dummy Encoding techniques to deal with categorical variables.
  * Split your dataset into X_train,X_test, y_train, y_test.
  * Scale the dataset by normalizing it(Min-Max Scaling or Standard Scaling).
4. Model Selection
  * Select several regression models and train them with the preprocessed data.
  * Examine the performances of the selected models using cross validation.
  * Choose the best performing model
5. Hyper-parameter Optimization
  * Optimize the hyper-parameters of the model selected in the previous step.
  * Optimize parameters with Grid Search. (Grid Search or Randomized Search)
6. Model Evaluation
  * Evaluate the optimized model using regression model evaluation metrics. (Ex. Mean Squared Error, Mean Absolute Error etc.)

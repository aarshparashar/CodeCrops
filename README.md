# Crop Yield Prediction

This notebook explores and builds machine learning models to predict crop yield based on factors such as area, crop type, year, average rainfall, pesticide usage, and average temperature. 

## Dataset 

The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/patelprashant/crop-yield-prediction-dataset?resource=download) and contains information on crop yields, environmental factors, and agricultural practices across different regions.

## Notebook Contents

1. **Installing Dependencies:** Importing necessary libraries like NumPy and Pandas.
2. **Data Loading and Exploration:**
   - Loading the dataset into a Pandas DataFrame. 
   - Exploring the data structure, data types, unique values, missing values, and duplicates. 
3. **Data Visualization:**
   - Creating interactive plots to visualize:
      - Area-wise crop yield over the years.
      - Area-wise pesticide usage over the years.
   - Generating a correlation matrix to understand relationships between numeric features.
4. **Data Preprocessing:**
   - Separating features (X) and the target variable (crop yield - y).
   - Handling categorical features using OneHot Encoding.
   - Splitting data into training and testing sets using `train_test_split`.
5. **Machine Learning:**
   - Defining a list of regression models to evaluate:
      - Linear Regression
      - Decision Tree
      - Random Forest
      - Extra Trees 
      - Support Vector Machine
   - Creating a pipeline for each model, including preprocessing steps. 
   - Training the models on the training data.
   - Making predictions on the testing data. 
   - Evaluating model performance using metrics:
      - Mean Squared Error (MSE)
      - Mean Absolute Error (MAE)
      - R-squared (R^2) score
   - Comparing the performance of different models. 

## Future Work

- **Hyperparameter Tuning:** Exploring techniques like GridSearchCV to optimize the hyperparameters of the best-performing models and potentially improve their accuracy. 

## How to Use

You can run this notebook in a Google Colab environment using the "Open in Colab" badge at the top of the notebook. Make sure to upload the `yield_df.csv` dataset file to your Colab environment before running the code. 

# USA Housing Price Prediction

This project involves training a linear regression model to predict housing prices using the USA_Housing.csv dataset. The steps include data preprocessing, model training, and evaluating the model's performance.

## Dataset
The dataset used in this project is USA_Housing.csv, which contains various features related to housing data. The address column is dropped, and the remaining columns are used as features, except for the price column, which is the target variable.

## Steps
### 1. Data Preprocessing
- **Load the Data:** Read the data from USA_Housing.csv.
- **Split the Data:** Split the data into training and testing sets (60% for training and 40% for testing).
- **Features and Target:** The address column is dropped. The features are all columns except for the price column, which is the target.

### 2. Model Training
- **Linear Regression Model:** Train a linear regression model using scikit-learn.
- **Fit the Model:** Fit the model to the training data.
- **Model Parameters:** Check the coefficients and intercepts to understand the model.

### 3. Model Prediction and Evaluation
- **Make Predictions:** Use the trained model to make predictions on the test set.
- **Analyze Residuals:** Evaluate the model's performance by analyzing the residuals (errors) using three different metrics.

## Installation
To run this project, you need Python installed on your system. Additionally, install the required libraries using:
```
pip install -r requirements.txt
```

## Usage
1. **Clone the Repository:**
   
   ```
   git clone https://github.com/anishapareek/HousingPricePrediction.git
   cd HousingPricePrediction
   ```
2. **Place the Dataset:**
Ensure USA_Housing.csv is in the root directory of the project.

3. **Run the Script:**
   ```
   python main.py
   ```

## Results
- **Coefficients and Intercept:** Insights into how each feature impacts the target variable.
- **Prediction Metrics:** Mean Absolute Error, Mean Squared Error, and Root Mean Square Error to measure the model's performance.

## Conclusion
This project demonstrates how to preprocess data, train a linear regression model, and evaluate its performance. The model provides insights into the relationship between housing features and prices.

## Acknowledgements
- Thanks to the creators of the USA_Housing.csv dataset.
- This project uses the scikit-learn library for model training and evaluation.


# Car Price Predictor

## Overview

The **Car Price Predictor** is a machine learning project that aims to predict the price of a car based on various features using a linear regression model. This project uses real-world car price data and provides a simple yet effective approach to predicting car prices.

## Project Structure

- `car_price_predictor/`  
  - `CarPrice_Assignment.csv`: Contains the dataset with various attributes related to cars such as make, model, engine size, horsepower, and more.
  - `Data Dictionary - carprices.xlsx`: A detailed dictionary explaining the variables used in the dataset.
  - `car-price-prediction-linear-regression-rfe.ipynb`: Jupyter notebook containing the complete code for data preprocessing, exploratory data analysis, feature selection using Recursive Feature Elimination (RFE), and building the linear regression model.

## Dataset

### CarPrice_Assignment.csv
This dataset contains various features related to cars, including:

- **Car_ID**: Unique identifier for each car.
- **Symboling**: Risk factor rating assigned to the car (-3 to 3).
- **CarName**: Brand name of the car.
- **FuelType**: Type of fuel used (diesel or gas).
- **Aspiration**: Type of aspiration used in the engine.
- **...**: (More features are explained in detail in the data dictionary).

### Data Dictionary - carprices.xlsx
This file explains each variable used in the dataset, providing insights into the data attributes and their significance in the prediction process.

## Key Features

- **Linear Regression**: The project utilizes a linear regression model to predict the car prices.
- **Feature Selection**: Recursive Feature Elimination (RFE) is used to identify the most important features influencing the car price.
- **Exploratory Data Analysis (EDA)**: The notebook includes data exploration and visualization to better understand relationships in the dataset.

## How to Use

1. Clone the repository or download the project folder.
2. Install the necessary Python libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Run the Jupyter notebook (`car-price-prediction-linear-regression-rfe.ipynb`) to view the complete process of data loading, preprocessing, and model building.
4. Adjust the model and dataset as needed to experiment with other machine learning algorithms or improve prediction accuracy.

## Results

The linear regression model predicts car prices with reasonable accuracy. The Jupyter notebook provides detailed steps for feature selection and performance evaluation.

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## Future Improvements

- Explore more advanced machine learning algorithms such as Random Forest, Gradient Boosting, or XGBoost to improve accuracy.
- Enhance data preprocessing techniques to handle outliers and missing data more effectively.
- Integrate a web-based front-end for users to input car details and get price predictions in real time.

## License

This project is for educational purposes and is not intended for commercial use.

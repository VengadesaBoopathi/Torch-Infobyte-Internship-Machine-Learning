# TORCH_ML_01

# House Price Prediction

This repository contains Python code for predicting house prices using a linear regression model. The dataset used for training and testing the model is provided in the dataa.csv file.

## Contents

1. [Introduction](#introduction)
2. [Dependencies](#dependencies)
3. [Usage](#usage)
4. [Results](#results)
5. [Contributing](#contributing)
6. [License](#license)

## Introduction

The goal of this project is to predict house prices based on various features such as the number of bedrooms, bathrooms, square footage of living area, lot size, etc. We utilize a linear regression model for this prediction task.

## Dependencies

The code is written in Python and requires the following dependencies:

- pandas
- matplotlib
- seaborn
- scikit-learn

You can install these dependencies using pip:
pip install pandas matplotlib seaborn scikit-learn


## Usage

1. Clone this repository to your local machine:

git clone https://github.com/your-username/house-price-prediction.git"


2. Navigate to the project directory:

cd house-price-prediction


3. Place your dataset file (dataa.csv) in the project directory.


## Results

After running the script, you will see the following outputs:

- A correlation matrix heatmap showing the correlation between different numerical features.
- Mean Squared Error (MSE) and R-squared (R2) values of the linear regression model on the test data.
- Scatter plots illustrating the relationship between actual and predicted prices, as well as the residuals.

Additionally, you can use the trained model to predict prices for new data points.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

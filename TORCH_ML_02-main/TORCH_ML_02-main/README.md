# TORCH_ML_02

# Customer Segmentation Using K-Means Clustering

This repository contains Python code for segmenting customers using K-Means clustering algorithm based on their annual income and spending score. The dataset used for analysis is provided in the Mall_Customers.csv file.

## Contents

1. [Introduction](#introduction)
2. [Dependencies](#dependencies)
3. [Usage](#usage)
4. [Results](#results)
5. [Contributing](#contributing)
6. [License](#license)

## Introduction

The goal of this project is to segment customers into distinct groups based on their similar characteristics such as annual income and spending score. K-Means clustering algorithm is used for this task.

## Dependencies

The code is written in Python and requires the following dependencies:

- numpy
- pandas
- seaborn
- matplotlib
- scikit-learn

You can install these dependencies using pip:

pip install numpy pandas seaborn matplotlib scikit-learn


## Usage

1. Clone this repository to your local machine:

git clone https://github.com/your-username/customer-segmentation.git


2. Navigate to the project directory:

cd customer-segmentation

3. Place your dataset file (Mall_Customers.csv) in the project directory.


## Results

After running the script, you will see the following outputs:

- Elbow point graph to determine the optimal number of clusters.
- Scatter plot showing the segmentation of customers based on their age, annual income, and spending score.
- Information about the number of customers in each segment and their corresponding customer IDs.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

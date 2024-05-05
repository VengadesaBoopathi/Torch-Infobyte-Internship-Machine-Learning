# TORCH_ML_03

# Cat vs. Dog Image Classification using SVM

This repository contains Python code for classifying images of cats and dogs using a Support Vector Machine (SVM) model. The images are preprocessed and then fed into the SVM for classification.

## Contents

1. [Introduction](#introduction)
2. [Dependencies](#dependencies)
3. [Usage](#usage)
4. [Results](#results)
5. [Contributing](#contributing)
6. [License](#license)

## Introduction

The goal of this project is to classify images of cats and dogs using a linear Support Vector Machine (SVM) classifier. The dataset consists of images of cats and dogs, and the SVM model is trained to predict whether a given image contains a cat or a dog.

## Dependencies

The code is written in Python and requires the following dependencies:

- numpy
- scikit-learn
- skimage
- tqdm
- matplotlib
- seaborn

You can install these dependencies using pip:

pip install numpy scikit-learn scikit-image tqdm matplotlib seaborn


## Usage

1. Clone this repository to your local machine:

git clone https://github.com/your-username/cat-dog-classification.git


2. Navigate to the project directory:

cd cat-dog-classification

3. Ensure that you have a folder named PetImages containing subfolders Cat and Dog, each containing images of cats and dogs respectively.


## Results

After running the script, you will see the following outputs:

- Accuracy of the SVM model on the test data.
- Visualization of sample test images with their true and predicted labels.
- Confusion matrix showing the performance of the model in terms of true positives, false positives, true negatives, and false negatives.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

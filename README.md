# Digit Recognizer with Principal Component Analysis (PCA)

This project aims to explore dimensionality reduction techniques, specifically Principal Component Analysis (PCA), to analyze and visualize handwritten digit data.

## Overview

The script provided in this repository utilizes Python's data science libraries such as NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn to perform the following tasks:

1. Load and preprocess the handwritten digit dataset.
2. Implement PCA both manually and using Scikit-learn's PCA module.
3. Visualize the dataset in reduced dimensions using PCA.
4. Analyze the variance explained by each principal component.
5. Plot the cumulative explained variance to determine the optimal number of components for dimensionality reduction.

## Usage

1. **Clone the repository**
2. **Navigate to the project directory**
3. **Execute the script**

## Dataset

The dataset used in this project is the famous MNIST dataset, which consists of 28x28 pixel grayscale images of handwritten digits from 0 to 9. The dataset is available in CSV format and can be found in the 'digit-recognizer' directory as 'train.csv'.

## Requirements

Ensure you have the following libraries installed:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

You can install these libraries using pip.

## Results

The script provides visualizations and insights into the handwritten digit dataset:

- Visualization of handwritten digits in reduced dimensions using both manual and Scikit-learn's PCA.
- Analysis of the variance explained by each principal component.
- Plotting the cumulative explained variance to determine the optimal number of components for dimensionality reduction.

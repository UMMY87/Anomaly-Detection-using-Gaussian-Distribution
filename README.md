# Anomaly Detection using Gaussian Distribution

This repository contains an implementation of anomaly detection using the Gaussian distribution model. Anomaly detection is a method used to identify outliers or anomalies in data that deviate significantly from the norm. The Gaussian distribution, also known as the normal distribution, is often employed for this purpose due to its simplicity and effectiveness.

## Overview

- **Data Loading and Visualization**: Load the dataset and visualize it to understand the underlying patterns.
  ![Plot First Data](https://github.com/UMMY87/K-Means-Clustering/assets/117314436/33fce69f-5189-4671-8bc1-08dc7555adac)

- **Estimating Gaussian Distribution**: Calculate the mean and variance of each feature in the dataset.

- **Multivariate Gaussian Probability**: Compute the density of the multivariate normal distribution at each data point given the mean and variance.
  ![The Gaussian contours of the distribution fit to the data](https://github.com/UMMY87/K-Means-Clustering/assets/117314436/1ec0926e-f899-467e-87fc-262f6872b45e)
  
- **Threshold Selection**: Find the best threshold for identifying outliers based on evaluation metrics like the F1 score.

- **Visualization of Outliers**: Identify outliers in the training set and visualize them on the scatter plot.
  ![The Gaussian contours of the distribution fit to the data detecting Outliers](https://github.com/UMMY87/K-Means-Clustering/assets/117314436/0b28b444-b2c0-492b-9fc1-c05da89e5424)

- **Extension to Multi-dimensional Data**: Extend the approach to handle datasets with multiple dimensions.

- **Evaluation on Larger Dataset**: Evaluate the model on a larger dataset, estimate Gaussian parameters, and identify anomalies.

## Usage

To use this implementation:

1. Clone the repository.
2. Navigate to the project directory.
3. Run the main script.

## Requirements

Ensure you have the following libraries installed:

- NumPy
- Matplotlib

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

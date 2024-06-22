# SVM Classification on Wine Dataset

This repository contains code for performing SVM (Support Vector Machine) classification on the Wine dataset using scikit-learn in Python. SVM is a powerful supervised learning algorithm that is used for classification tasks. The Wine dataset is a classic and well-known dataset in machine learning, commonly used for practice and benchmarking.

## Table of Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Overview

In this project, we aim to:
- Perform exploratory data analysis (EDA) on the Wine dataset to understand its structure and characteristics.
- Preprocess the data by scaling features and splitting into training and testing sets.
- Train an SVM classifier using GridSearchCV for hyperparameter tuning.
- Evaluate the model's performance using accuracy score, classification report, and confusion matrix.
- Visualize the results including EDA insights and model performance metrics.

## Requirements

- Python 3.x
- Jupyter Notebook (optional, for running the notebook locally)
- Libraries:
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn
  - mlxtend

You can install the required libraries using the following command:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn mlxtend
```

## Installation

To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/J3lly-Been/svm-wine-classification.git
   cd svm-wine-classification
   ```

2. Run Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open `svm_wine_classification.ipynb` in your browser and execute the cells sequentially.

## Usage

- **svm_wine_classification.ipynb**: Jupyter Notebook containing the code for SVM classification on the Wine dataset.
- **data/**: Directory containing the Wine dataset files or references.

## Results

- Exploratory Data Analysis (EDA) insights: Histograms, pairplots, correlation heatmap.
- Model Performance Metrics: Accuracy score, classification report, confusion matrix.
- Visualizations: Distribution of classes, pairplots, decision regions (optional).

Example visualizations are included in the notebook to illustrate the data exploration and model evaluation process.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

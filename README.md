# PRODIGY_ML_01
# PRODIFY INFOTECH 
# Housing Prices Prediction using Regression Techniques

![Housing Prices Prediction](images/house.jpg)

This repository contains the code and resources for predicting housing prices using various regression techniques. The project is based on a dataset from Kaggle, specifically the [Housing Prices Competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) dataset.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Techniques](#regression-techniques)
- [Results](#results)
- [Contributing](#contributing)


## Introduction

Predicting housing prices is a fundamental problem in the field of machine learning and data science. This project aims to explore various regression techniques to predict housing prices using features provided in the dataset. By experimenting with different algorithms and techniques, we aim to find the most accurate model for this specific problem.

## Dataset

The dataset used in this project is the [Housing Prices Competition dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) from Kaggle. It contains a comprehensive set of features related to residential properties. The dataset includes both training and testing data, with corresponding target values.

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/your-username/housing-prices-prediction.git
   cd housing-prices-prediction
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Download the dataset from the [Kaggle competition page](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) and place the CSV files in the `data/` directory.

2. Explore the Jupyter notebooks in the `notebooks/` directory to see the step-by-step process of data preprocessing, feature engineering, model training, and evaluation.

## Techniques

The following techniques are implemented in this project:

- Linear Regression
- KNNimputer
- Heatmap (correlation graph)


## Results

After thorough experimentation and tuning, the best performing model was the **Linear regression** with an RMSE of 50045.870 on the test data. Detailed results and insights can be found in the notebooks.

## Contributing

Contributions are welcome! If you find any issues or want to add improvements, feel free to create a pull request. For major changes, please open an issue first to discuss the changes.


---

Feel free to adapt and modify this README template according to your project's needs. Good luck with your housing prices prediction project! If you have any questions or need further assistance, please don't hesitate to ask.

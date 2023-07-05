# Laptop Price Predictor Regression Project

This project is a laptop price predictor implemented using regression techniques. It aims to predict the prices of laptops based on various features.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Laptop Price Predictor Regression Project is developed to provide an accurate estimation of laptop prices based on different attributes such as brand, processor, RAM, storage, graphics card, etc. It utilizes machine learning algorithms to train regression models on a given dataset and predicts the price of a laptop based on its specifications.

The project is implemented in Python using the following libraries:
1. Pandas
2. NumPy
3. Scikit-learn
   
The project is divided into two parts:
1. Data preparation
2. Model training and evaluation
   
The data preparation step involves cleaning the data and transforming it into a format that can be used by the machine learning model. The model training and evaluation step involves training a regression model on the data and evaluating its performance.

The project is hosted on GitHub. To run the project, you will need to install the following dependencies:
1. Python 3.7+
2. Pip

## Dataset

The dataset used in this project contains information about various laptops, including their brand, processor, RAM, storage, graphics card, screen size, and the corresponding price. The dataset is provided in a CSV format (`laptop_data.csv`), and it is included in the project repository.

## Installation

To run this project locally, please follow these steps:

1. Clone this repository:
   git clone https://github.com/subho004/laptop_price_predictor.git
  
2. Navigate to the project directory:
   cd laptop-price-predictor-regression-project

3. Install the required dependencies using `pip`:
  pip install -r requirements.txt

## Usage

To use the Laptop Price Predictor, you can follow these steps:

1. Ensure that you have installed all the dependencies (see [Installation](#installation)).

2. Open a terminal or command prompt and navigate to the project directory.

3. Run the following command to start the application:
   python app.py

4. Access the application via your web browser at `http://localhost:5000`.

5. Enter the required specifications of the laptop (brand, processor, RAM, storage, graphics card, screen size) in the provided fields.

6. Click on the "Predict" button to get an estimated price for the laptop based on the provided specifications.

## Models

The project implements different regression models to predict laptop prices. The following models are currently supported:

- Linear Regression
- Decision Tree Regression
- Random Forest Regression
- Gradient Boosting Regression

These models are trained on the provided dataset to learn the relationship between the laptop features and their prices.

## Results

The accuracy and performance of the prediction models depend on the quality of the dataset and the specific regression model used. Therefore, the results may vary based on these factors. However, the project aims to provide a reasonably accurate estimation of laptop prices.

## Images

![Screenshot of Interface](https://github.com/subho004/laptop_price_predictor/blob/main/Laptop1.png)

## Contributing

Contributions to this project are welcome. If you have any suggestions, bug reports, or feature requests, please open an issue on the https://github.com/subho004/laptop_price_predictor




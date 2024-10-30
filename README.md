# simple-ml-linear-regression
This repository contains a simple example of linear regression using Python and the `scikit-learn` library. The purpose is to demonstrate a basic machine learning model that predicts weight based on height.

## Concept

Linear regression models a relationship between two variables by fitting a "best fit" line. In this example, we aim to predict a person’s weight given their height.

## Dataset

The dataset is synthetic. We create random heights and add a linear relationship with a bit of noise to simulate real-world data.

## Code Explanation

- **Data Creation**: We use `numpy` to generate random heights, then calculate weights with a linear relationship.
- **Train/Test Split**: We split data into training and testing sets to validate model performance.
- **Model Training**: Using `LinearRegression` from `scikit-learn`, we fit the model to our training data.
- **Evaluation**: We use Mean Squared Error (MSE) to assess how well the model predicts weight.

## Setup Instructions

### Prerequisites
- Python (3.6 or higher)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/simple-ml-linear-regression.git
   cd simple-ml-linear-regression

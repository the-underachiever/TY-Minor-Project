# IPL Score Predictor

This project aims to predict the total score of an IPL match based on various input features such as the batting and bowling teams, runs scored, wickets taken, overs bowled, and performance in the last five overs.

## Table of Contents

- Installation
- Modeling Approach
- Features
- Dependencies
- License

## Installation

Clone the repository:
   ```bash
   git clone https://github.com/the-underachiever/TY-Minor-Project.git
   cd TY-Minor-Project
```
## Modeling Approach

The model uses **XGBoost** for score prediction. The following steps are implemented:

### 1. Data Preprocessing
Clean and preprocess the IPL dataset by handling missing values and converting date columns if necessary.
### 2. Feature Engineering
Extract important features and apply one-hot encoding to categorical variables.
### 3. Model Training
Train the model using XGBoost on the preprocessed data.
### 4. Model Evaluation
Evaluate the model's performance using test data.

## Features

The IPL Score Predictor uses the following features to predict the total score:

- **Batting Team**: The team currently batting in the match.
- **Bowling Team**: The team currently bowling in the match.
- **Runs Scored So Far**: The total runs scored by the batting team up to the current point in the match.
- **Wickets Taken**: The number of wickets lost by the batting team.
- **Overs Bowled**: The total number of overs bowled in the match so far.
- **Runs in the Last 5 Overs**: The runs scored by the batting team in the last 5 overs.
- **Wickets in the Last 5 Overs**: The wickets lost by the batting team in the last 5 overs.

These features help the model to provide an accurate prediction of the total score for the ongoing match.

## Dependencies

This project requires the following Python packages:

- **Python**: 3.x
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib**: For data visualization.
- **Seaborn**: For statistical data visualization.
- **Scikit-learn**: For machine learning algorithms and utilities.
- **XGBoost**: For gradient boosting framework.

You can install the required packages using pip. Here's how:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```
## License

This project is licensed under the MIT License. See the LICENSE file for details.

### MIT License





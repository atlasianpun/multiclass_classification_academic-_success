# Academic Success Prediction

This project aims to predict academic success using machine learning techniques. It includes exploratory data analysis (EDA), feature engineering, model training, and evaluation of different models to determine the best performing one.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Models Used](#models-used)
- [Data Description](#data-description)
- [Feature Engineering](#feature-engineering)
- [Model Evaluation](#model-evaluation)
- [Hyperparameter Optimization](#hyperparameter-optimization)
- [Results](#results)
- [Credits](#credits)
- [License](#license)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/academic-success-prediction.git
   cd academic-success-prediction
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Ensure that the Kaggle datasets are correctly downloaded and placed in the appropriate directory.
2. Run the Jupyter notebooks to explore the data, preprocess it, and train the models.

## Models Used

- Random Forest
- AdaBoost
- Gradient Boosting
- XGBoost
- CatBoost
- LightGBM

## Data Description

The dataset used in this project includes features that are hypothesized to influence academic success. The data is split into training and test sets, and a sample submission file is provided.

## Feature Engineering

Feature engineering involves cleaning the data, handling missing values, and encoding categorical features. This process is crucial for preparing the data for machine learning algorithms.

## Model Evaluation

The models are evaluated using cross-validation. The primary metric used for comparison is accuracy. 

## Hyperparameter Optimization

Hyperparameter optimization is performed using Hyperopt for LightGBM to find the best parameters that improve the model's performance.

## Results

The models are compared based on their accuracy, and the feature importances are plotted to understand which features contribute the most to the predictions.

## Credits

This project is developed using data from Kaggle and various machine learning libraries including Scikit-Learn, LightGBM, XGBoost, and CatBoost.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


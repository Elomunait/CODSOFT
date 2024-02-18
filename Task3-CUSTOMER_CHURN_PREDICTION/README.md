# Customer Churn Prediction

## Overview
This project aims to develop a predictive model for customer churn in a subscription-based service or business. Customer churn, also known as customer attrition, refers to the rate at which customers stop using a service. By analyzing historical customer data and utilizing machine learning algorithms such as Logistic Regression, Random Forests, or Gradient Boosting, the goal is to predict which customers are likely to churn in the future.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Model Building](#model-building)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Model Interpretability](#model-interpretability)
- [Model Evaluation](#model-evaluation)
- [Model Saving](#model-saving)
- [Contributing](#contributing)
- [License](#license)

## Installation
To run the code in this project, you will need Python installed on your machine. Additionally, you can install the required libraries using the following command:

```
pip install -r requirements.txt
```

## Usage
After installing the required dependencies, you can execute the project's main script to train and evaluate the predictive model for customer churn. Follow the steps outlined in the Jupyter notebook or Python script provided.

## Project Structure
- **Notebooks**: Contains Jupyter notebooks for data preprocessing, exploratory data analysis, model building, and evaluation.
- **Scripts**: Python scripts for data preprocessing, model building, and evaluation.
- **Data**: Directory to store the dataset used in the project.
- **README.md**: Description of the project and instructions for usage.

## Data Preprocessing
The dataset is loaded and cleaned by removing unnecessary columns and checking for missing values.

## Exploratory Data Analysis (EDA)
Visualizations are created to explore the distribution of the target variable, categorical variables, and correlation between features and the target variable.

## Model Building
The dataset is split into training and testing sets, and an initial model is built using XGBoost.

## Hyperparameter Tuning
Hyperparameter tuning is performed using RandomizedSearchCV to find the best combination of hyperparameters for the XGBoost model.

## Model Interpretability
The first tree in the XGBoost model is visualized to understand feature importance. Feature importance is also analyzed using both tree-based and SHAP (SHapley Additive exPlanations) methods.

## Model Evaluation
Evaluation curves including ROC-AUC curve, Precision-Recall curve, and Confusion Matrix are plotted to assess the performance of the model.

## Model Saving
The best XGBoost model is saved using the joblib library for future use.

## Contributing
Contributions to this project are welcome. Feel free to open issues or pull requests for any improvements or bug fixes.

## License
This project is licensed under the [MIT License](https://github.com/Elomunait/CODSOFT/blob/main/LICENSE).
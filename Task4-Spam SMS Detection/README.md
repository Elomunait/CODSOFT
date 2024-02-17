# SMS Spam Detection

## Overview

This repository contains code and resources for building a machine learning model to classify SMS messages as spam or legitimate. The model utilizes the TF-IDF technique along with the Multinomial Naive Bayes classifier.

## Table of Contents

- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Model Improvement](#model-improvement)
- [Confusion Matrix Analysis](#confusion-matrix-analysis)
- [Evaluation Curves](#evaluation-curves)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The original dataset can be found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection). The dataset contains labeled SMS messages as spam or ham.

## Installation

1. Clone the repository:

```
git clone https://github.com/your-username/SMS-Spam-Detection.git
```

2. Install the required dependencies:

```
pip install -r requirements.txt
```

## Usage

1. Download the SMS spam collection dataset and unzip it.

2. Run the Jupyter Notebook `SpamSMSDetection.ipynb` to explore, train, and evaluate the model.

## Exploratory Data Analysis

Explore the dataset to understand its structure, distribution, and characteristics.

## Model Training and Evaluation

Train a Multinomial Naive Bayes classifier using the TF-IDF technique and evaluate its performance on test data.

## Model Improvement

Improve the model by fine-tuning hyperparameters using GridSearchCV.

## Confusion Matrix Analysis

Analyze the confusion matrix to understand the model's performance in terms of True Positives, True Negatives, False Positives, and False Negatives.

## Evaluation Curves

Plot ROC-AUC and Precision-Recall curves to further evaluate the model's predictive performance.

## Results

The final model achieves improved accuracy and performance after hyperparameter tuning.

## Contributing

Feel free to contribute to this project. Create issues for bug reports or feature requests, and submit pull requests to enhance the code.

## License

This project is licensed under the [MIT License](LICENSE).

```
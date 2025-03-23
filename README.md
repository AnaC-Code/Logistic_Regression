
# Logistic Regression Project

This repository contains implementations of logistic regression applied to both binary and multiclass classification problems. The project is organized into two main folders:

* **Binary_Classification**
* **Multiclass_Classification**

This code is based on the tutorial: [Logistic Regression Tutorial]()

## Project Structure

```
├── Binary_Classification
│   ├── code
│   └── exercise
├── Multiclass_Classification
│   ├── code
│   └── exercise
└── README.md
```

## Binary Classification

The binary classification problem focuses on predicting outcomes with two possible classes. The `Binary_Classification` folder contains two codes:

1. **Insurance Prediction**: Predicts whether a person bought insurance based on their age.
2. **Employee Turnover Prediction (Exercise)**: Predicts whether a worker leaves their job based on various features: `satisfaction_level`, `last_evaluation`, `number_project`, `average_monthly_hours`, `time_spend_company`, `Work_accident`, `left`, `promotion_last_5years`, `Department`, `salary`.

## Multiclass Classification

For multiclass classification, two datasets from `sklearn.datasets` are used:

1. **Digits Dataset**: Predicts whether the classification of digit images is correct.
2. **Iris Dataset**: Predicts the correct classification of flowers.

Both datasets come from `sklearn` and serve as excellent examples of multiclass classification using logistic regression.

## Requirements

* Python 3.x
* pandas
* matplotlib
* scikit-learn
* seaborn

Install dependencies with:

```
pip install -r requirements.txt
```

## Results

* Binary classification models tries to predict insurance purchase and worker turnover.
* Multiclass classification models tries to classify digits and flowers correctly.

## Contributions

Feel free to fork this project, create feature branches, and submit pull requests. All contributions are welcome!

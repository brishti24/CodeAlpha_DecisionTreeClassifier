# CodeAlpha_DecisionTreeClassifier
"A Decision Tree Classifier model built with scikit-learn to predict credit risk based on the German Credit dataset. Completed as part of the CodeAlpha internship."
# Credit Scoring Model using Decision Tree Classifier

## Project Overview
This project aims to predict an individual's creditworthiness based on their past financial data. Using machine learning classification algorithms such as Decision Trees, Logistic Regression, and Random Forests, the model evaluates whether a person is likely to repay credit reliably.

## Objective
Build a classification model that predicts credit risk to assist financial institutions in making informed lending decisions.

## Approach
- Feature engineering is performed on financial history data to extract meaningful predictors.
- The Decision Tree Classifier is implemented to classify individuals as creditworthy or not.
- Model performance is assessed using metrics including Precision, Recall, F1-Score, and ROC-AUC.

## Dataset
The dataset includes key financial features such as:
- Income
- Outstanding debts
- Payment history
- Other relevant financial indicators

*Note:* The dataset is [mention source if public or note if synthetic] and preprocessing steps like handling missing data and encoding categorical features are done within the notebook.

## How to Run
1. Open the notebook [`DecisionTreeClassifier.ipynb`](DecisionTreeClassifier.ipynb) in Google Colab by clicking [here](https://colab.research.google.com/github/brishti24/CodeAlpha_DecisionTreeClassifier/blob/main/DecisionTreeClassifier.ipynb).
2. Run all the cells sequentially.
3. The notebook uses the following Python libraries (pre-installed in Colab):
   - `pandas`
   - `numpy`
   - `scikit-learn`
   - `matplotlib` (for visualization)

Alternatively, clone this repo and run locally after installing the dependencies.

## Project Structure
- `DecisionTreeClassifier.ipynb` — Main notebook with code, explanations, and results.
- `README.md` — This documentation file.
- `.gitignore` — Git ignore file.
- `LICENSE` — License information.

## Results
- The model’s accuracy and other key performance metrics such as Precision, Recall, F1-Score, and ROC-AUC are calculated and explained within the notebook.
- Visualizations like confusion matrix and feature importance plots help interpret the model’s effectiveness.

## Author
Argharupa Chakraborty  
[GitHub Profile](https://github.com/brishti24) https://www.linkedin.com/in/argharupa-chakraborty-66a540282?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app

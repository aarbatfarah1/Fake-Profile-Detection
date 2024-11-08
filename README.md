# Fake News Detection with Overfitting Control

This project is focused on detecting fake news using various machine learning models while addressing overfitting issues through regularization, model complexity control, and cross-validation.

## Project Structure

- **notebook.ipynb**: The main Jupyter notebook that includes data loading, preprocessing, model training, and evaluation with techniques to control overfitting.
- **README.md**: Documentation and instructions for running the project.

## Project Overview

Fake news detection has become a crucial area in Natural Language Processing and Machine Learning. This project aims to classify news articles as real or fake using a variety of machine learning models. Given the potential for models to overfit, especially in complex tasks like text classification, several strategies are implemented to enhance generalization.

## Key Features

- **Data Preprocessing**:
  - **Text Vectorization**: Converts text descriptions into numerical features using TF-IDF.
  - **Categorical Encoding**: Uses One-Hot Encoding to convert categorical features.
  - **Feature Scaling**: Standardizes numerical features for balanced model performance.

- **Overfitting Control**:
  - **Regularization**: Adds regularization terms in models like Logistic Regression and Support Vector Machines.
  - **Complexity Control**: Limits tree depth in models like Random Forest and Decision Tree to avoid capturing noise.
  - **Cross-Validation**: Uses Stratified K-Fold Cross-Validation to assess the generalization of each model.

- **Model Training and Evaluation**:
  - Six models are compared: Random Forest, Gradient Boosting, Logistic Regression, K-Nearest Neighbors, Support Vector Machine, and Decision Tree.
  - Each model is evaluated on accuracy, precision, recall, F1-score, and a confusion matrix to gain insights into performance.

## Requirements

To run this notebook, you will need the following libraries:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install these packages with:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn


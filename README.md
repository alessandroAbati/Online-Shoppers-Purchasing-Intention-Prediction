# Online Shoppers Purchasing Intention Prediction

## Introduction
This project is part of the coursework for the module "Introduction to AI" for the MSc in Artificial Intelligence at City, University of London. The objective is to apply various artificial intelligence techniques to predict the purchasing intention of online shoppers using a dataset from Kaggle.

## Problem Domain
The problem domain revolves around e-commerce and understanding customer behaviors online. Specifically, the aim is to predict whether a customer will make a purchase based on their browsing behavior and other attributes.

## Dataset
The dataset utilized is the "Online Shoppers Purchasing Intention Dataset" available on [Kaggle](https://www.kaggle.com/datasets/imakash3011/online-shoppers-purchasing-intention-dataset). It comprises various features such as session information, bounce rates, exit rates, and page values that potentially influence purchasing decisions.

## Questions and Analysis Tasks
- What features most significantly impact online shopping purchasing intentions?
- Can we predict a user's purchasing intention with reasonable accuracy?
- How do different AI models compare in predicting online shopper behavior?
- Which model most effectively captures the nuances of online shopping data?

Objectives include exploring data characteristics, performing feature engineering, and implementing several AI techniques to predict purchasing intentions.

## Initial Dataset Investigation
An exploratory data analysis will be conducted to understand data characteristics and distributions. A plan will be developed for data transformation and feature engineering to make the dataset suitable for machine learning models.

## AI Techniques and Observations
We will be using models covered in the module, including:
- Perceptron
- Decision Trees
- Linear Regression
- Support Vector Machines
- Random Forest
- k-Nearest Neighbour
- Naïve Bayes
- Neural Networks
- k-Means and GMM (for unsupervised learning)
- Principal Component Analysis

An additional technique may be considered for comparative analysis.

## Data Splitting Strategy
The dataset will be split into training, validation, and test sets to ensure that the model can be trained and evaluated effectively.

## Analysis Execution
The project will follow an iterative approach:
1. Data preprocessing and feature engineering
2. Baseline model establishment
3. Model training and validation
4. Performance analysis and error analysis
5. Iteration and model tuning

## Baseline Results and Iteration
Baseline results will be established to gauge initial model performance. Subsequent iterations will focus on improving the model by analyzing errors and trying different model variants.

## Close to Data Strategy
Visualization techniques and summary statistics will be employed to remain close to the data. Different parameters and model variants will be experimented with to understand their effects on performance.

## Installation

To run this project, you will need to replicate the Python environment used for the analysis.

If you're using conda, you can create an environment with the following command:

```bash
conda env create -f environment.yml
```

For pip users, ensure you have the same packages installed by running:

```bash
pip install -r requirements.txt
```
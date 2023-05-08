# BoomBikes Demand Prediction: A Multiple Linear Regression Case Study

[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com) [![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

![Bike](https://i.imgur.com/fcIbYn1.jpg)

## Table of Contents
* [Introduction](#introduction)
* [Objective](#objective)
* [Overview of the Analysis Steps](#overview)
* [Installation](#installation)
* [Dataset](#dataset)
* [Contributing](#contributing)
* [License](#license)

## Introduction
BoomBikes, a US-based bike-sharing provider, has experienced a significant decline in revenues due to the ongoing Corona pandemic. As the company faces challenges in sustaining its business in the current market, it seeks to develop a mindful business plan to accelerate revenue growth once the lockdown ends and the economy restores to a healthy state. To achieve this, BoomBikes aims to understand the factors affecting the demand for shared bikes in the American market and how these factors can help predict bike-sharing demand after the pandemic subsides. The company has collected a large dataset on daily bike demands across the American market based on various meteorological surveys and people's preferences.

## Objective
The goal of this analysis is to create a multiple linear regression model using the available independent variables to predict the demand for shared bikes. The model will assist BoomBikes' management in understanding how the demand varies with different features, allowing them to tailor their business strategy to meet demand levels and customer expectations. Additionally, the model will serve as a valuable tool for understanding the demand dynamics in new markets.

## Overview of the Analysis Steps
1. Dataset Evaluation: Assess the dataset's quality and consistency, making necessary adjustments to ensure it is suitable for analysis.
2. Exploratory Data Analysis (EDA): Perform an in-depth examination of the dataset to uncover patterns, trends, and relationships between variables.
3. Data Preprocessing: Convert categorical variables into dummy variables using Pandas, ensuring that the regression model can effectively utilize these features.
4. Split the dataset: Divide the dataset into training (70%) and test (30%) sets to evaluate the model's performance on unseen data.
5. Model Building: Develop a multiple linear regression model using the training data, taking 'cnt' as the target variable (total number of bike rentals).
6. Model Evaluation: Assess the model's performance using the test data by calculating the R-squared score.
7. Interpretation of Results: Analyze the coefficients of the best-fitted line to understand the impact of different variables on bike-sharing demand.
8. Provide Recommendations: Offer actionable insights and suggestions to BoomBikes based on the analysis to help them optimize their business strategy and better serve their customers.

## Installation

To set up this project, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/manikUpgrad/boombikes-linear-regression.git
   ```
2. Create a virtual environment and activate it:
   ```
   python -m venv venv
   source venv/bin/activate (Linux/Mac)
   venv\Scripts\activate (Windows)
   ```
3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
4. Run the Jupyter notebook to explore the analysis:
   ```
   jupyter notebook
   ```

## Dataset

The dataset used in this case study can be found [here](https://ml-course2-upgrad.s3.amazonaws.com/Linear
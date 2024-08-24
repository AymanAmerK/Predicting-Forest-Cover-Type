# Forest Cover Type Prediction

This project aims to predict multi-class forest cover types using various machine learning models. It follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology to analyze and process a dataset from the UCI Machine Learning repository.

## Project Overview

The goal is to predict forest cover type (7 types) based on cartographic variables such as elevation, aspect, slope, and soil type. This analysis can provide insights into the composition and distribution of forest cover types.

## Dataset

The dataset contains 581,012 rows and 55 columns, including:
- Quantitative variables: elevation, slope, hillshade index, etc.
- Qualitative binary variables: wilderness areas and soil types
- Target variable: integer from 1 to 7 representing the forest cover type

## Methodology

The project follows the CRISP-DM methodology:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Model Building
5. Testing and Evaluation
6. Deployment

## Models

Four different models were developed and compared:

1. Decision Tree (DT)
2. Random Forest (RF)
3. Neural Network (MLP type)
4. Logistic Regression (LR)

## Tools Used

- KNIME Analytics Platform

## Key Findings

- The Random Forest model performed best with 0.975 accuracy.
- The Neural Network (MLP) model had the lowest prediction results with 0.918 accuracy.
- Soil type, elevation, and wilderness area type were the most important variables for prediction.

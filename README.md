# AutoML Benchmarking: Housing Price Prediction

## Author Information
**Name:** BOUZID Mohamed El Khallil  
**Specialty:** Organic Process Engineering  

## Project Overview
This repository contains a technical benchmark of four leading Automated Machine Learning (AutoML) frameworks. The objective is to compare their performance and efficiency in solving a regression problem using the **California Housing Dataset**.

## Frameworks Evaluated
The following libraries were implemented and tested under similar constraints:
1. **H2O AutoML**: Uses a distributed in-memory platform (Java-based).
2. **Auto-sklearn**: Builds on scikit-learn using Bayesian optimization for hyperparameter tuning.
3. **TPOT**: Optimizes machine learning pipelines using genetic algorithms.
4. **MLJAR**: A framework focusing on result explainability and tree-based models.

## Dataset Details
- **Source**: Scikit-learn Library (`fetch_california_housing`)
- **Type**: Regression
- **Target Variable**: Median House Value
- **Features**: 8 numerical features (MedInc, HouseAge, AveRooms, etc.)
- **Training/Testing Split**: 80% / 20%

## Requirements
To reproduce the results, a Linux environment is recommended (e.g., Google Colab) due to `auto-sklearn` dependencies.

```bash
pip install pandas numpy scikit-learn h2o auto-sklearn tpot mljar-supervised

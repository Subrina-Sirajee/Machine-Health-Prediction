# Machine Health Monitoring System

This repository contains code for a machine health monitoring system that predicts maintenance requirements based on temperature and vibration sensor readings. The system utilizes machine learning techniques, including preprocessing, modeling, and prediction.

## Overview

The machine health monitoring system consists of the following components:
- Data preprocessing: Power transformation and min-max scaling are applied to the sensor readings.
- Modeling: An XGBoost classifier is trained to predict maintenance requirements based on sensor data.
- Prediction: Given new sensor readings, the system predicts whether maintenance is needed immediately, soon, or not at all.


## Files

- `Machines' Health Data Analysis and Labeling.ipynb`: Notebook for data exploration, analysis and labeling.
- `Machine Health Model's Pipeline Creation.ipynb`: Notebook for creating machine learning pipeline.
- `Machine Health Prediction.ipynb`: Notebook for making predictions using the trained model.
- `requirements.txt`: List of dependencies required to run the code.
- `xgboost_pipeline_model.joblib`: Trained model saved in joblib format.
- `labeled_data.csv`: Dataset containing sensor readings and maintenance status labels.

## Acknowledgments

- The implementation utilizes scikit-learn, XGBoost, and joblib libraries for machine learning tasks.

## Required Dependencies

The following dependencies are required to run the machine health monitoring system:

- `pandas`: For data manipulation and handling.
- `numpy`: For numerical computations and array operations.
- `matplotlib`: For creating plots and visualizations.
- `seaborn`: For statistical data visualization.
- `statsmodels`: For statistical modeling and analysis.
- `scikit-learn`: For machine learning tasks such as preprocessing, modeling, and evaluation.
- `xgboost`: For implementing the XGBoost classifier, a gradient boosting algorithm.
- `joblib`: For serialization and deserialization of Python objects, including machine learning models.

These dependencies can be installed via `pip` using the provided `requirements.txt` file:




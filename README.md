# VaxPredict Overview

This project aims to predict the likelihood of individuals receiving their xyz and seasonal flu vaccines. We are tasked with predicting two probabilities: one for `xyz_vaccine` and one for `seasonal_vaccine`.

## Data Description

The dataset consists of 36 columns, including a unique identifier (`respondent_id`) and 35 features describing various aspects of the respondents, such as their opinions, behaviors, demographics, and health conditions. The target variables are binary, indicating whether the respondent received the xyz or seasonal flu vaccine.

### Target Variables

- `xyz_vaccine`: Whether the respondent received the xyz flu vaccine (0 = No, 1 = Yes).
- `seasonal_vaccine`: Whether the respondent received the seasonal flu vaccine (0 = No, 1 = Yes).

### Features

The dataset includes a wide range of features, such as concerns and knowledge about the flu, behavioral factors, opinions about vaccine effectiveness and risks, demographic information, and more.

## Submission Format

Submissions should consist of a CSV file with three columns: `respondent_id`, `xyz_vaccine`, and `seasonal_vaccine`. Each entry should contain the predicted probability of the individual receiving each vaccine, ranging from 0.0 to 1.0.

## Performance Metric

Performance will be evaluated based on the Area Under the Receiver Operating Characteristic Curve (ROC AUC) for each target variable. The mean of these two scores will determine the overall performance score.

## Code Setup

### Dependencies

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

This documentation provides a structured overview of the project, from data description to submission format and performance metrics. It serves as a comprehensive guide for anyone working on this project.

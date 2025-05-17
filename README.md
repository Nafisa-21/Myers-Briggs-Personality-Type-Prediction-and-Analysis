# Myers-Briggs Personality Type Prediction and Analysis

**Author**: Nafisa Anjum  
**Project Type**: Data Analysis and Classification  
**Technologies**: Python, Pandas, Seaborn, Plotly, Scikit-learn, Wolta Toolkit

## Overview

This project explores the Myers-Briggs Type Indicator (MBTI) and builds a machine learning pipeline to predict personality types based on individual survey data. The MBTI categorizes people into 16 personality types derived from four psychological dimensions:

- Introversion (I) / Extraversion (E)
- Sensing (S) / Intuition (N)
- Thinking (T) / Feeling (F)
- Judging (J) / Perceiving (P)

## Objectives

- Understand the distribution and characteristics of MBTI personality types.
- Perform exploratory data analysis to uncover trends and patterns.
- Train and evaluate classification models to predict personality type.

## Key Features

### Data Analysis
- Cleaned and explored dataset containing gender, age, education, interest, and MBTI scores.
- Checked for missing values and basic statistics.

### Visualizations
- Pairplots, histograms, KDEs, and boxplots for distribution analysis.
- Correlation heatmaps for numerical features.
- Pie charts for categorical distributions (gender, interest).
- Scatter and 3D plots to observe interactions between traits.

### Modeling and Evaluation
- Trained a Random Forest classifier for MBTI prediction.
- Evaluated using accuracy, classification report, and confusion matrix.
- Visualized feature importance to interpret the model.

### Model Benchmarking
- Compared multiple classifiers (AdaBoost, CatBoost, LightGBM, Random Forest, Extra Trees, etc.) using Wolta's `compare_models`.
- Selected the best model based on accuracy and precision.
- Final evaluation included confusion matrix display and metrics reporting.

## Conclusion

This project provides insights into personality data and demonstrates how machine learning can be applied to psychological profiling. It blends statistical visualization with practical model evaluation, supporting both educational and analytical use cases.

# RESTAURANT-DATASET-ANALYSIS
## Overview

This project involves a comprehensive data analysis pipeline, starting from data extraction and preprocessing, through to descriptive and geospatial analysis, predictive modeling, and data visualization. The aim is to gain insights and make predictions based on the provided dataset.

## Table of Contents

- Dataset 
- Project Workflow  
  - Data Extraction 
  - Data Preprocessing  
  - Descriptive Analysis  
  - Geospatial Analysis 
  - Predictive Modeling 
  - Data Visualization 
- Results

## Dataset

shape: (9551, 21)
- columns: 'Restaurant ID', 'Restaurant Name', 'Country Code', 'City', 'Address', 'Cuisines', 'Has Table booking',
       'Has Online delivery', 'Is delivering now','Price range', 'Aggregate rating', 'Rating color', 'Rating text',etc.,
       
## Project Workflow:

### Data Extraction

Extracted data from data source.
Cleaned and standardized raw data for further analysis.

### Data Preprocessing

Handled missing values, data type conversions, and outlier detection.
Normalized or scaled features as necessary to ensure compatibility with models.

### Descriptive Analysis

Conducted basic statistical analysis to understand data distributions.
Computed key metrics and explored relationships between variables.

### Geospatial Analysis

Used geospatial data (e.g., latitude and longitude) to conduct analysis and visualize geographic trends.
Tools used-folium.

### Predictive Modeling
steps:
1.Encoding
2.Train Test split
3.Feature scaling
4.Feature selection

Built and evaluated multiple predictive models to make data-driven forecasts.
Selected the model with the highest performance based on R², accuracy, or other relevant metrics.

### Data Visualization

Created visualizations using libraries like Matplotlib, Seaborn, or Plotly to present insights and model results.
Visualized important trends, distributions, and model predictions.

## Results

This model is effective in predicting the aggregate rate based on the selected features, with high accuracy and valuable insights into feature importance. 

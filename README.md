# SpaceX Falcon 9 First-Stage Landing Prediction

## IBM Data Science Capstone Project

## Project Overview

This project analyzes SpaceX Falcon 9 launch data to investigate and predict whether the first stage of a Falcon 9 rocket will land successfully.

SpaceX's ability to recover and reuse rocket boosters can reduce launch costs. By analyzing historical launch records, this project explores the factors associated with landing success and applies machine learning classification models to predict landing outcomes.

The project combines data collection, data wrangling, exploratory data analysis (EDA), SQL queries, geographic visualization, interactive dashboards, and predictive modeling.

## Objectives

- Collect and prepare SpaceX launch data for analysis.
- Explore relationships between launch characteristics and landing outcomes.
- Use SQL to answer questions about launch records.
- Visualize launch sites and their geographic context using Folium.
- Build an interactive dashboard with Plotly Dash.
- Train and evaluate machine learning classification models.
- Compare model performance and identify the most relevant findings.

## Project Workflow

### 1. Data Wrangling

Load, inspect, and prepare the datasets. Review data types, missing values, and relevant variables before analysis.

### 2. Exploratory Data Analysis and Feature Engineering

Explore launch patterns using visualizations and statistical summaries. Prepare model features by encoding categorical variables and selecting relevant predictors.

### 3. SQL Analysis

Use SQL queries to investigate launch records, compare launch sites, and examine landing outcomes across relevant categories.

### 4. Geographic Visualization with Folium

Create interactive maps to display launch sites and explore their geographic context.

### 5. Interactive Dashboard with Plotly Dash

Develop a dashboard that allows users to filter launch records by launch site and payload mass, visualize landing outcomes, and explore the relationship between payload mass and landing success.

### 6. Machine Learning

Train and compare classification models to predict first-stage landing outcomes. Evaluate performance using appropriate metrics, including accuracy, precision, recall, F1-score, and confusion matrices where applicable.

## Tools and Technologies

- **Python**
- **Pandas and NumPy**
- **Matplotlib and Seaborn**
- **SQL**
- **Folium**
- **Plotly and Plotly Dash**
- **Scikit-learn**
- **Jupyter Notebook**

## Repository Structure

```text
spacex-falcon9-landing-prediction/
├── README.md
├── SpaceX_Capstone_Consolidated.ipynb
├── SpaceX_Capstone_Presentation.pdf
├── SpaceX_Capstone_Presentation.pptx
└── data/
    └── Supporting datasets (if applicable)
```

*Update the filenames above to match the files actually uploaded to the repository.*

## Key Findings

This section will summarize the main findings after the notebook has been executed and the results have been validated.

The final analysis will highlight:

- The most relevant patterns observed during exploratory data analysis.
- Differences in landing outcomes across launch sites and other launch characteristics.
- Insights obtained from SQL queries and geographic visualization.
- The best-performing classification model and its evaluation metrics.

## Conclusion

This project demonstrates an end-to-end data science workflow applied to SpaceX Falcon 9 first-stage landing prediction. It combines data preparation, exploratory analysis, SQL, visualization, and machine learning to investigate historical launch outcomes.

The final conclusions will be based on the validated model results and the evidence obtained throughout the analysis.

## Limitations

The analysis depends on the available historical data and the quality of its labels. Model performance on historical records does not guarantee accurate predictions for future launches. Results should be interpreted as an educational data science analysis rather than a real-time operational or flight-safety system.

## Author

**Matías Montenegro**

IBM Data Science Capstone Project

## Acknowledgments

This project was developed as part of the IBM Data Science Professional Certificate learning path, using the SpaceX Falcon 9 capstone project framework and associated educational datasets.

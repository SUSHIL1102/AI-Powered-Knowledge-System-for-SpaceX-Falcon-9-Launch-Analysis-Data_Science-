# SpaceX Falcon 9 First Stage Landing Prediction

## Overview

This repository contains an individual project focused on predicting the success of SpaceX Falcon 9 first-stage landings. The analysis uses machine learning to determine factors influencing landing outcomes, which can help estimate launch costs by assessing reusability. The project involves data collection from APIs and web scraping, data wrangling, exploratory data analysis (EDA), SQL queries, visualizations, interactive dashboards, and predictive modeling.

Publicly available data from Wikipedia and the SpaceX API is processed using Python libraries such as Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Folium, and Plotly Dash. The implementation is demonstrated in a comprehensive final notebook, phase-specific notebooks, and a summary PDF.

## Project Structure

- **SpaceY_final.ipynb**: The complete Jupyter notebook combining all phases, including data collection, preprocessing, EDA, modeling, and evaluation.
- **labs/**: A folder containing separate notebooks for each phase:
  - `1)jupyter-labs-spacex-data-collection-api.ipynb`: Data collection via API.
  - `2)jupyter-labs-webscraping.ipynb`: Web scraping for launch data.
  - `3)labs-jupyter-spacex-Data wrangling.ipynb`: Data cleaning and wrangling.
  - `4)jupyter-labs-eda-sql-coursera_sqllite.ipynb`: EDA with SQL queries.
  - `5)edadataviz (copy).ipynb`: Data visualization.
  - `6)lab_jupyter_launch_site_location(Folium).ipynb`: Launch site mapping with Folium.
  - `8)SpaceX_Machine Learning Prediction.ipynb`: Machine learning model development and prediction.
- **Interactive Dashboard with Ploty Dash.pdf**: A PDF summary of the interactive dashboard built with Plotly Dash, including visualizations and insights.
- **data/**: Directory for raw and processed datasets (e.g., CSV files from API and scraping).
- **images/**: Folder for generated plots and visualizations.
- **README.md**: This file.

## Methodology

### Phase 1: Data Collection
- Collected launch data using the SpaceX API and web scraping from Wikipedia.
- Extracted details like booster versions, launch sites, payloads, and core outcomes.

### Phase 2: Data Wrangling
- Cleaned and formatted the data, handling missing values and inconsistencies.
- Created features such as payload mass, orbit type, and landing class.

### Phase 3: Exploratory Data Analysis (EDA)
- Performed statistical analysis and visualizations (e.g., success rates by launch site).
- Used SQL for querying datasets and Folium for mapping launch locations.

### Phase 4: Data Visualization and Dashboard
- Generated plots with Matplotlib and Seaborn.
- Built an interactive dashboard with Plotly Dash to explore trends dynamically.

### Phase 5: Machine Learning Prediction
- Developed models (e.g., logistic regression, SVM, decision trees, KNN) using Scikit-learn.
- Tuned hyperparameters with GridSearchCV and evaluated using accuracy, F1-score, and confusion matrices.

### Phase 6: Evaluation and Insights
- Assessed model performance on test data.
- Identified key predictors like launch site and payload mass for landing success.

## Requirements

- Python 3.7+
- Required libraries (install via `pip`):

# Thesis Project: Systems Analysis and Forecasting of MAANG Stock Prices Dynamics

## Overview

This repository contains the code and analysis developed for my Bachelor's diploma project focused on analysing and modelling time-series behaviour of major technology stocks (MAANG: Meta, Apple, Amazon, Netflix, Google).  

The project investigates statistical relationships between these assets and evaluates several machine learning and time-series forecasting approaches for modelling their dynamics. The work includes exploratory data analysis, feature construction, regression and classification modelling, neural network experiments, and time-series forecasting.

The repository is organised as a structured research pipeline implemented in Jupyter notebooks.

Additional classification experiments used in a related article are available in the `classification_for_theses` branch.

---

## Repository Structure

```
diploma_project/
├── README.md
├── requirements.txt
├── .gitignore
├── notebooks/
│   ├── 01_data_preparation.ipynb
│   ├── 02_external_data_exchange_rates.ipynb
│   ├── 03_eda_correlation.ipynb
│   ├── 04_regression_models.ipynb
│   ├── 05_classification_models.ipynb
│   ├── 06_neural_network_models.ipynb
│   ├── 07_forecasting_baseline.ipynb
│   ├── 08_forecasting_future.ipynb
│   └── 09_results_summary_tables.ipynb
├── reports/
│   └── correlation_analysis/
│       ├── corellations_visualization_amazon.html
│       ├── corellations_visualization_apple.html
│       ├── corellations_visualization_google.html
│       ├── corellations_visualization_meta.html
│       └── corellations_visualization_netflix.html
│   ├── figures/
│   ├── tables/
└── data/
    ├── raw/
    └── processed/
```



---

## Notebooks

The notebooks follow the logical workflow of the project:

**01_data_preparation.ipynb**  
Data loading, cleaning, and construction of the main dataset used throughout the analysis.

**02_external_data_exchange_rates.ipynb**  
Collection and integration of additional financial indicators (e.g., exchange rates) used as explanatory variables.

**03_eda_correlation.ipynb**  
Exploratory data analysis of MAANG stock time series, including correlation analysis and visualisation of relationships.

**04_regression_models.ipynb**  
Evaluation of regression-based models for predicting stock behaviour using engineered features.

**05_classification_models.ipynb**  
Binary classification experiments aimed at predicting the direction of price movements.

**06_neural_network_models.ipynb**  
Experiments with neural network architectures applied to financial time-series data.

**07_forecasting_baseline.ipynb**  
Baseline time-series forecasting models used to establish initial predictive performance.

**08_forecasting_future.ipynb**  
Extended forecasting experiments investigating predictive performance on future time horizons.

**09_results_summary_tables.ipynb**  
Generation of summary statistics and comparison tables for model performance.

---

## Data

The datasets used in this project are not included in the repository due to size constraints.

Raw financial time-series data should be placed in:
```
└── data/
    └── raw/
```

Processed datasets generated during the pipeline will be stored in:
```
└── data/
    └── processed/
```


The datasets can be reconstructed by running the notebooks starting from **01_data_preparation.ipynb**.

---

## Environment Setup

Create a virtual environment and install dependencies:

```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Then start Jupyter:
```jupyter notebook```

## Reproducing the Analysis

Run the notebooks sequentially:

1. Data preparation
2. Exploratory analysis
3. Model training and evaluation
4. Forecasting experiments
5. Results aggregation

The notebooks are designed to follow the same workflow used during the diploma research.


## Related Work

Additional experimental code used for a related article is available in the branch:

classification_for_theses

This branch contains specialised classification experiments derived from the main research pipeline.





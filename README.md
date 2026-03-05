# Classification Experiments for Related Article

## Overview

This branch contains additional classification experiments developed as part of a research article related to the main Bachelor's diploma project.

While the main repository focuses on a broader analysis of MAANG stock time-series behaviour (including regression models, neural networks, and forecasting approaches), this branch isolates a specific set of classification experiments used for the preparation of an accompanying article.

The goal of these experiments was to evaluate the ability of machine learning models to predict the direction of stock price movements based on engineered features derived from historical time-series data.

---

## Relation to the Main Project

The experiments in this branch build directly on the data preparation and feature engineering pipeline implemented in the main project.

Key differences from the main branch include:

- additional feature engineering steps tailored for classification tasks
- focused evaluation of classification algorithms
- statistical evaluation used for article results

The underlying data processing logic and overall analytical framework remain consistent with the main repository.

---

## Main Notebook

The primary notebook used for these experiments is:
```classification.ipynb```


This notebook contains:

- dataset preparation for classification
- feature selection and preprocessing
- training and evaluation of classification models
- analysis of model performance metrics

---

## Reproducibility

To run the experiments:

```bash
pip install -r requirements.txt
jupyter notebook```

Then open:
```classification.ipynb```

## Notes

This branch preserves the experimental setup used for the article and is maintained separately to avoid interfering with the main project workflow.

For the full research pipeline and broader analysis, see the main branch of the repository.


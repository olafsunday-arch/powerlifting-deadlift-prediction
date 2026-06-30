# Powerlifting Deadlift Prediction

## Project Overview

This project focuses on exploratory data analysis and machine learning using OpenPowerlifting data. The main goal is to analyze powerlifting performance and build regression models to predict the best deadlift result based on athlete characteristics and other lift results.

## Goal

The goal of the project is to predict the athlete's best deadlift result using selected numerical and categorical features from competition data.

## Dataset

The project uses two datasets:

1. **OpenPowerlifting dataset** – competition results and athlete performance data.
2. **Countries and continents dataset** – additional country-to-continent mapping used for geographical analysis.

The raw datasets are not stored in this repository because of their size. Instructions for downloading and placing the data are available in the `data/` folder.

Data sources:

- OpenPowerlifting dataset: https://www.openpowerlifting.org/
- Countries by Continent dataset: https://www.kaggle.com/datasets/hserdaraltan/countries-by-continent

Expected local data structure:

```text
data/
├── openpowerlifting-2024-01-06-4c732975.csv
└── countries and continents.csv
```


## Main Notebook

The full analysis is available here:

[Open the Jupyter Notebook](notebooks/powerlifting_deadlift_prediction.ipynb)

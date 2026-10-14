
# ERA5 Meteorological Data Analysis Using PCA

This repository contains an exploratory machine learning experiment using ERA5 meteorological reanalysis data.

The project investigates dimensionality reduction and feature representation using Principal Component Analysis (PCA), with a case study based on meteorological data from Fars, Iran.

## Overview

The experiment includes:

- Meteorological data preprocessing
- Temporal aggregation of weather variables
- Feature standardization
- Principal Component Analysis (PCA)
- Explained variance analysis
- Regression using AdaBoost
- Model evaluation using R² and RMSE

## Dataset

The notebook uses processed ERA5 meteorological data from the Fars region of Iran.

The data include precipitation, temperature, wind, cloud cover, humidity-related variables, and surface pressure.

The original dataset is not included in this repository.

ERA5 data source:
https://cds.climate.copernicus.eu/datasets/reanalysis-era5-single-levels

## Repository Structure

```text
.
├── README.md
└── impact_PCA.ipynb
```

## Code

`impact_PCA.ipynb` contains the data analysis and machine learning experiments.

The notebook explores the proportion of meteorological feature variance explained by principal components and evaluates a regression model using PCA-transformed features.

## Tools

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Notes

This repository preserves an early exploratory experiment. The input dataset is not included, and the notebook may require local data-path adjustments before execution.


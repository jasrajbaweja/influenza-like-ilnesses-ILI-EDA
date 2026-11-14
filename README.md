# Influenza-Like Illness (ILI) Data Analysis

Exploratory data analysis of 27,000+ influenza-like illness, weather, and pollen records across 15 cities using Python.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-EDA-150458?logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)

## Overview

This project cleans and merges weather, pollen, and ILI datasets to explore seasonal patterns and possible relationships between environmental factors and influenza-like illness.

## Key Findings

- [Finding 1, e.g. ILI activity peaks in ___ months across most cities]
- [Finding 2, e.g. relationship (or lack of one) between temperature and ILI]
- [Finding 3, e.g. how pollen levels compare with ILI trends]
- [Finding 4, e.g. differences between cities]

## Visualizations

![Seasonal ILI trend](images/ili_seasonal_trend.png)
![Weather vs ILI](images/weather_vs_ili.png)

## Objectives

- Clean and preprocess multiple datasets
- Handle missing values, duplicates, and inconsistent data
- Merge weather, pollen, and ILI information
- Analyze seasonal patterns and potential relationships
- Create visualizations to communicate findings

## Dataset

- 27,000+ records across 15 cities
- Weather measurements
- Tree, grass, and weed pollen data
- Influenza-like illness data
- Source: [add where the data came from]

## Project Structure

```
├── ili.ipynb        # ILI data cleaning and analysis
├── pollen.ipynb     # Pollen data cleaning and analysis
├── weather.ipynb    # Weather data cleaning and analysis
├── images/          # Exported visualizations
├── requirements.txt
└── README.md
```

## How to Run

```bash
git clone https://github.com/jasrajbaweja/influenza-like-ilnesses-ILI-EDA.git
cd influenza-like-ilnesses-ILI-EDA
pip install -r requirements.txt
jupyter notebook
```

Run the notebooks in this order: `weather.ipynb`, `pollen.ipynb`, `ili.ipynb`. [Adjust if your order differs.]

## Technologies

Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## Limitations and Future Work

- [e.g. correlation does not imply causation]
- [e.g. add predictive modeling to forecast ILI activity]
- [e.g. include additional cities or years]
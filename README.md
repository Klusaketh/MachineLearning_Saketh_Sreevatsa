# COVID-19 Data Analysis

Exploratory data analysis of a country-level COVID-19 dataset: data cleaning, descriptive statistics, monthly trends, country comparisons and a correlation heatmap.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

## What the Notebook Does

1. **Inspect** - shape, column types, missing values and duplicates
2. **Clean** - fill numeric gaps with the median and categorical gaps with the mode, drop duplicates, fix data types
3. **Describe** - mean, median, variance and standard deviation for confirmed, deaths, recovered, active, new cases and new deaths
4. **Trend** - monthly new cases and new deaths
5. **Compare** - country-wise confirmed cases, deaths and recoveries
6. **Correlate** - heatmap of relationships between all case metrics (Matplotlib, Seaborn)

## Findings

- USA had the highest confirmed cases in the dataset (790,860).
- March 2025 had the most new cases (333,307) and the most new deaths (5,404).

## Files

| File | Description |
|---|---|
| `machinelearningtask.ipynb` | Full notebook with outputs |

The notebook reads `corona_analysis_dataset.csv`, which is not included in this repo.

## Author

**Paramkusam Saketha Sreevatsa** - [GitHub](https://github.com/Klusaketh) · [LinkedIn](https://www.linkedin.com/in/paramkusamsakethasreevatsa)

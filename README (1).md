# Fatal Force Analysis

An exploratory data analysis of the Washington Post's database of fatal police shootings in the US, cross-referenced with US Census data on household income, poverty rates, high school completion rates, and racial demographics by city/state.

## Overview

Since January 1, 2015, [The Washington Post](https://www.washingtonpost.com/) has compiled a database tracking every fatal shooting by an on-duty police officer in the United States. This notebook explores that dataset alongside socioeconomic indicators to look for patterns and correlations.

## Data Sources

This notebook expects the following CSV files in the project directory (not included here — see note below):

- `PoliceKillingsUS.csv` — Washington Post fatal shootings database
- `Median_Household_Income_2015.csv`
- `Pct_People_Below_Poverty_Level.csv`
- `Pct_Over_25_Completed_High_School.csv`
- `Share_of_Race_By_City.csv`

> **Note:** Add the actual CSV filenames/sources here once confirmed, and either include the data files in a `data/` folder or link to where they can be downloaded (e.g. Kaggle).

## Setup

```bash
python -m venv venv
source venv/bin/activate  # on Windows: venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

Then open `Fatal_Force_Analysis.ipynb`.

## Tools Used

- pandas / numpy — data wrangling
- matplotlib / seaborn — static visualizations
- plotly — interactive visualizations

## License

MIT

# Weather Data Analytics

A data analysis project focused on exploring long-term daily weather patterns across India from 2000 to 2024. The repository contains a cleaned and preprocessed weather dataset, exploratory analysis notebooks, and a set of charts summarizing temperature, precipitation, and seasonal trends.

## Project Overview

This project analyzes historical weather conditions to understand:

- Temperature variation across cities and years
- Seasonal and monthly weather patterns
- Rainfall and precipitation trends
- Relationships between weather variables such as temperature, humidity, and wind
- Distribution of daily weather conditions over time

## Dataset

The project uses daily weather records from multiple Indian cities covering the period 2000-2024.

Files included:

- `india_2000_2024_daily_weather.csv` — raw daily weather dataset
- `preprocessed.csv` — cleaned/preprocessed version of the dataset

## Repository Structure

```text
weather-data-analytics/
├── charts/                                 # Generated weather analysis visualizations
├── eda.ipynb                               # Exploratory data analysis notebook
├── preprocessing.ipynb                     # Data cleaning and preprocessing notebook
├── india_2000_2024_daily_weather.csv       # Raw weather dataset
├── preprocessed.csv                        # Processed dataset
├── REVIEW PRESSENTATION.pptx               # Project presentation
├── README.md                               # Project documentation
└── .gitignore                              # Git ignore configuration (if present in repo)
```

## Analysis Highlights

The analysis includes visualizations such as:

- Yearly average maximum temperature
- Monthly average precipitation trends
- Temperature distributions by city
- Correlation matrix of weather variables
- Comparison of max vs min temperature
- Seasonal box plots for temperature and precipitation
- Scatter plots for temperature-precipitation and wind relationships

## Tools and Libraries

The notebooks are built using common Python data science tools, including:

- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn

## How to Use

1. Clone the repository.
2. Open the notebooks in Jupyter Notebook or JupyterLab.
3. Run `preprocessing.ipynb` to clean and transform the data.
4. Explore the results in `eda.ipynb`.
5. Review generated figures in the `charts/` directory.

## Example Setup

```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook
```

## Purpose

This project demonstrates how weather data can be explored and visualized for insight generation, trend analysis, and decision support using data analytics techniques.

## License

This project does not currently include a formal license file. If you plan to share or reuse the project publicly, consider adding an appropriate open-source license.

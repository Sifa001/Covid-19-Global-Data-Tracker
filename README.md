#  COVID-19 Global Data Analysis

This project explores global trends in COVID-19 cases, deaths, and vaccination efforts using data from **Our World in Data**. Through data cleaning, visualization, and analysis, it highlights insights about the pandemic's progression across countries and regions.

---

## Objectives

- Import and clean COVID-19 global data
- Analyze time-based trends in cases, deaths, and vaccinations
- Compare pandemic metrics across countries and continents
- Visualize data using clear and informative charts/maps
- Communicate key findings and insights in a Jupyter Notebook report

---

## Tools & Libraries Used

- **Python 3.x**
- **Jupyter Notebook**
- [pandas](https://pandas.pydata.org/) – data manipulation
- [matplotlib](https://matplotlib.org/) – basic plotting
- [seaborn](https://seaborn.pydata.org/) – enhanced visualizations
- [plotly](https://plotly.com/python/)  – for choropleth maps
- [numpy](https://numpy.org/) – numeric computations

---

## How to Run / View the Project
Python 3.8+: Install via python.org or Anaconda
Dataset: Download owid-covid-data.csv from Our World in Data

Installation
# Option 1: Install from python.org (https://www.python.org/downloads/)
# Option 2: Install Anaconda (recommended for data science)
conda create -n covid_env python=3.8
conda activate covid_env
# Create and activate conda environment (recommended)
conda create -n covid_env python=3.8
conda activate covid_env

# Install required packages
pip install pandas matplotlib seaborn plotly jupyter

# Download the Dataset
Download owid-covid-data.csv and place it in your project folder.

# Launch Jupyter Notebook
bash
jupyter notebook
Then open covid_tracker.ipynb from the notebook interface.
## Key Insights
Countries like India experienced multiple waves with sharp spikes in cases and deaths.

High-income countries showed faster vaccination rollout, especially in early 2021.

Some countries had disproportionately high case fatality rates, often tied to healthcare system capacity or reporting standards.

## Reflections
This project was a great exercise in:

Real-world data cleaning and exploration

Understanding global disparities in healthcare response

Building visual storytelling through data

Using Python tools effectively for public health analysis

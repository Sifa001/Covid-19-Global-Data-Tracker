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
bash
# Create and activate conda environment (recommended)
conda create -n covid_env python=3.8
conda activate covid_env

# Install required packages
pip install pandas matplotlib seaborn plotly jupyter
Project Setup
Directory Structure:

covid_project/
├── covid_tracker.ipynb
├── owid-covid-data.csv
└── README.md
Launch Jupyter Notebook:

bash
cd path/to/covid_project
jupyter notebook
Running the Analysis
Open covid_tracker.ipynb in Jupyter

Run cells sequentially to:

Load and clean COVID-19 data

Generate visualizations:

Time series of cases/deaths

Vaccination progress by country

Interactive choropleth maps

Calculate key metrics:

Mortality rates

Vaccination percentages

Case fatality ratios

Key Insights
After running the notebook, update this section with your findings. Example metrics:

Global peak death rate: X% on [date]

Top 3 vaccinated countries: [Country A] (X%), [Country B] (Y%), [Country C] (Z%)

Case fatality ratio range: X% (lowest) to Y% (highest) by country

Troubleshooting
Ensure the CSV file is in the same directory as the notebook

Restart kernel if plotly charts don't render

Update packages with pip install --upgrade pandas plotly

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

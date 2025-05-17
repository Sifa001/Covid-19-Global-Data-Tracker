# COVID-19 Global Data Analysis
This project explores global trends in COVID-19 cases, deaths, and vaccination efforts using data from [Our World in Data](https://ourworldindata.org/covid-deaths). Through comprehensive data analysis and visualization, it reveals insights about the pandemic's progression across different regions.

##  Objectives
- Import and clean global COVID-19 dataset
- Analyze temporal trends in cases, deaths, and vaccinations
- Compare pandemic metrics across countries and continents
- Create informative visualizations (charts, maps, dashboards)
- Generate actionable insights from the data

## Tools & Technologies

| Category        | Tools/Libraries |
|----------------|---------------|
| **Core**       | Python 3.8+, Jupyter Notebook |
| **Data Processing** | pandas, numpy |
| **Visualization** | matplotlib, seaborn, plotly |
| **Environment** | Anaconda (recommended) |

## Getting Started

### Prerequisites
- Python 3.8+ ([python.org](https://www.python.org/downloads/))
- OR Anaconda ([anaconda.com](https://www.anaconda.com/download))

### Installation
1. **Set up environment**:
   ```bash
   conda create -n covid_env python=3.8
   conda activate covid_env
   ```

2. **Install packages**:
   ```bash
   pip install pandas matplotlib seaborn plotly jupyter
   ```

3. **Get the data**:
   - Download [owid-covid-data.csv](https://ourworldindata.org/covid-deaths)
   - Place in project root directory

### Running the Project
```bash
jupyter notebook
```
Open `covid_tracker.ipynb` and run all cells

##  Key Findings

- **Wave Patterns**: Countries like India experienced multiple distinct waves with sharp case spikes
- **Vaccination Disparities**: High-income countries achieved 50% vaccination 3-6 months faster than others
- **Fatality Rates**: Case fatality rates varied from 0.5% to 8% across nations
- **Regional Impact**: Europe and Americas showed highest per-capita death rates

##  Sample Visualizations
1. Time-series of global cases/deaths
2. Vaccination progress by income group
3. Interactive choropleth of case fatality rates

##  Reflections
This project demonstrated:
- Real-world data cleaning challenges
- The power of visualization in public health communication
- Global disparities in pandemic response
- Python's effectiveness for end-to-end data analysis

## 📂 Project Structure
```
covid-analysis/
├── data/                   # Raw data files
│   └── owid-covid-data.csv
├── covid_tracker.ipynb     # Main analysis notebook
├── README.md               # This file
└── visuals/               # Generated charts
```

## 📜 License
[MIT](https://choosealicense.com/licenses/mit/)
```

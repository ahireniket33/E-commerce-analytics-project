# Global Food Crisis Analysis (2019-2025)

Analysis of food price inflation across 94 countries using 1.96M+ records from World Food Programme data.

## Project Overview

Identified countries most affected by food crises between 2019-2025:
- **Nicaragua**: 13,955% inflation
- **Zimbabwe**: 8,262% inflation  
- **Tanzania**: 5,841% inflation

Interactive Tableau visualization shows top 50 affected countries with food category breakdowns.

## Dataset Sources

**World Food Programme Global Food Prices**
- Source: https://data.humdata.org/dataset/wfp-food-prices
- 1,960,406 records across 94 countries, 831 commodities, 1,500+ markets
- Download and place CSV files in `Raw_Data/WFP/`

**World Bank Development Indicators**
- Source: https://data.worldbank.org/
- Download inflation (FP.CPI.TOTL.ZG) and GDP per capita (NY.GDP.PCAP.CD)
- Place in `Raw_Data/WorldBank/`

**IMF Currency Exchange Rates**
- Source: https://data.imf.org/
- Place in `Raw_Data/IMF/`

## Tech Stack

- Python 3.10, Pandas, NumPy (data processing)
- Matplotlib, Seaborn (exploratory analysis)
- Tableau Desktop 2024.3 (interactive visualization)
- Jupyter Notebook (development)

## Project Structure
```
├── Python_Scripts/          # Data processing code
├── Processed_Data/          # Analysis-ready datasets
├── Tableau_Files/           # Interactive dashboard
└── Raw_Data/               # Download datasets here (not included in repo)
```

## Key Findings

- Pulses & Legumes showed highest inflation (1,521.6%)
- Cereals & Grains second most affected (511.9%)
- Politically unstable nations suffered disproportionately
- COVID-19 (2020) and Ukraine conflict (2022) caused major price spikes

## Authors

**Robert Borkar** - Visualization design, Tableau implementation, critical analysis  
**Niket Ahire** - Data gathering, processing pipeline, exploratory analysis

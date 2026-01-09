# Immobiliare.it Housing Prices Analysis

A comprehensive data analysis project focused on Italian real estate market, analyzing housing prices and property characteristics from [Immobiliare.it](https://www.immobiliare.it), Italy's leading real estate platform.

## 📊 Project Overview

This project performs ELT (Extract, Load, Transform) and EDA (Exploratory Data Analysis) on housing sale listings from across Italy, with data starting from 2021. The analysis examines various property characteristics, prices, locations, and trends to derive insights about the Italian housing market.

## 🎯 Objectives

- Clean and transform raw housing data into a structured format
- Analyze housing price distributions across different Italian regions
- Identify relationships between property characteristics and prices
- Visualize geographical price patterns using interactive maps
- Perform univariate, bivariate, and multivariate statistical analyses
- Build regression models to understand price determinants

## 📁 Dataset Description

The dataset contains information about property sales listings from www.immobiliare.it with the following key features:

- **Price** (`prezzo`): Sale price in euros
- **Property Details**: Number of rooms (`stanze`), square meters (`m2`), bathrooms (`bagni`)
- **Location**: Floor (`piano`), city (`citta`), region (`regione`)
- **Property Type**: `tipologia` (apartment, villa, etc.)
- **Building Info**: Total floors (`totale piani edificio`), property class
- **Listing Info**: Contract type (`contratto`), availability (`disponibilità`)
- **Description**: Detailed property description
- **Date**: Listing announcement date

The cleaned dataset (`sale_clean.csv`) contains thousands of property listings across all Italian regions.

## 🛠️ Technologies Used

### Python Libraries
- **Data Processing**: `pandas`, `numpy`
- **Visualization**: `matplotlib`, `seaborn`, `plotly`
- **Geospatial Analysis**: `folium`
- **Statistical Modeling**: `statsmodels`
- **Database**: `sqlalchemy`

### Analysis Tools
- Jupyter Notebook for interactive analysis
- Interactive maps with Folium

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/federicocanali02-01/Immobiliare.it-Housing-Prices.git
cd Immobiliare.it-Housing-Prices
```

2. Install required Python packages:
```bash
pip install pandas numpy matplotlib seaborn plotly folium statsmodels sqlalchemy
```

Alternatively, install Jupyter Notebook environment:
```bash
pip install jupyter notebook
```

## 💻 Usage

1. Open the Jupyter Notebook:
```bash
jupyter notebook "ELT-EDA prezzo delle case in Italia Federico Canali.ipynb"
```

2. Run the cells sequentially to:
   - Load and clean the data
   - Perform exploratory data analysis
   - Generate visualizations
   - Create statistical models
   - Generate interactive maps

3. View the interactive price map by opening `mappa_prezzo_case_italia.html` in a web browser.

## 📂 Project Structure

```
Immobiliare.it-Housing-Prices/
│
├── ELT-EDA prezzo delle case in Italia Federico Canali.ipynb  # Main analysis notebook
├── sale_clean.csv                                              # Cleaned dataset
├── mappa_prezzo_case_italia.html                              # Interactive price map
└── README.md                                                   # Project documentation
```

## 📈 Analysis Components

### 1. ELT (Extract, Load, Transform)
- Data loading and initial inspection
- Handling missing values and duplicates
- Data type conversions and standardization
- Feature engineering

### 2. EDA (Exploratory Data Analysis)
- Univariate analysis of key variables
- Distribution analysis of housing prices
- Regional price comparisons
- Correlation analysis between features
- Temporal trends in listing prices

### 3. Visualizations
- Price distribution histograms
- Regional price heatmaps
- Interactive geographical maps with Folium
- Scatter plots for price relationships
- Statistical plots with Seaborn and Plotly

### 4. Statistical Modeling
- Regression analysis to identify price determinants
- Correlation matrices
- Statistical significance testing

## 🗺️ Key Features

- **Interactive Map**: Visualize housing prices across Italian regions using Folium
- **Comprehensive Cleaning**: Robust data cleaning pipeline removing nulls and duplicates
- **Rich Visualizations**: Multiple chart types for in-depth insights
- **Regional Analysis**: Compare prices and characteristics across different Italian regions
- **Statistical Rigor**: Statistical modeling to understand price factors

## 📊 Results

The analysis generates:
- Cleaned dataset ready for further analysis
- Interactive HTML map showing price distribution across Italy
- Statistical insights into factors affecting housing prices
- Visualization dashboards for data exploration

## 👤 Author

**Federico Canali**

## 📝 License

This project is available for educational and research purposes.

## 🔗 Data Source

Data sourced from [Immobiliare.it](https://www.immobiliare.it), Italy's leading real estate marketplace.

---

*Note: This analysis is for educational purposes. Housing prices are subject to market changes and the data reflects listings from 2021 onwards.*

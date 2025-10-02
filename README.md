# Urbanization &amp; Climate Impact on Crop Yields

# Urbanization Impact on Climate and Crop Yields Analysis

## Project Overview

This project analyzes the relationship between urbanization, local climate patterns, and agricultural productivity. Using historical data from 1990-2015, we examine how urban expansion affects rainfall patterns and crop yields, providing insights for farmers and agricultural scientists.

## Key Questions Addressed

- How does urbanization affect local rainfall?
- What is the relationship between urban development and crop productivity?
- Which factors most strongly predict agricultural yields?
- 
##  Requirements

### Python Version
- Python 3.8 or higher

### Required Libraries
bash
pip install pandas numpy matplotlib seaborn jupyter
pip install scikit-learn scipy statsmodels


Or install from requirements file:
bash
pip install -r requirements.txt


##  How to Run

1. *Clone the repository*
bash
git clone https://github.com/nbilasals/crop_yield_prediction.git


2. *Install dependencies*
bash
pip install -r requirements.txt


3. *Launch Jupyter Notebook*
bash
jupyter notebook analysis.ipynb


4. *Run all cells*
   - Click Cell → Run All in Jupyter
   - Or run cells sequentially to see step-by-step analysis

## Data Sources

- *Urbanization Data*: World Urbanization Prospects dataset
- *Climate Data*: Global climate datasets including rainfall and temperature
- *Agricultural Data*: Crop yield data by country and urbanization level

All datasets are publicly available and cited within the notebook.

##  Key Findings
Urbanziationm matter more than climate
Country with higher urban population (%) consistently show higher crop yields, regardless of rainfall or temperatire Levels.
Rainfall and temperature still matter, but not decisive.
Over decades, both crop yield and urbanization increased all in parallels.
So, urbanziation has a stronger and more consistent positive association with crop yields compared to rainfall. Climate sets the baseline, but urbanization through modernization, infrastucture, is what really drives productivity differences across countries)


##  Visualizations

The analysis includes 15+ visualizations covering:
- Time series trends
- Distribution analysis
- Scatter plots with multiple dimensions
- Correlation heatmaps
- Bar charts for comparative analysis



---

*Note*: This analysis is based on historical data and should be used alongside expert agricultural advice for decision-making.

Last updated: October 2025

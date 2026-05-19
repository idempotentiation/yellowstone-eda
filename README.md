# Yellowstone Wolf-Elk Population Analysis

Exploratory data analysis of the northern Yellowstone elk herd across 
three demographic eras, examining the relationship between wolf 
reintroduction, snowpack, and elk population dynamics.

## Data Sources

- **Wolf population & pack counts:** Yellowstone Wolf Project Annual 
  Reports, National Park Service (1995–2024)
- **Elk population:** Northern Yellowstone elk herd survey, National 
  Park Service (1923–2024)  
- **April snowpack (SWE):** NRCS SNOTEL station, Lupine Creek WY 
  (10E01), accessed via the NRCS Report Generator

## Requirements

Python 3.x with the following packages:
pandas, matplotlib, seaborn, scipy, statsmodels, odfpy

Install with:
pip install pandas matplotlib seaborn scipy statsmodels odfpy

## Structure

yellowstone_eda.ipynb   — main analysis notebook
data/                   — raw data files as originally obtained
outputs/                — generated figures

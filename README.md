# Global Coffee Market Analysis (2010-2022)

## Overview
This project presents a comprehensive analysis of the global coffee market from 2010 to 2022. Using data from the International Coffee Organization (ICO), World Bank, and other sources, I've analyzed production trends, consumption patterns, price dynamics, and sustainability factors to provide strategic recommendations for industry stakeholders.

![Coffee Market Value Projection](reports/figures/market_value_projection.png)

## Problem Statement
The global coffee industry faces significant challenges including climate change impacts, price volatility, and evolving consumer demands. This analysis provides data-driven strategic planning recommendations to ensure sustainable growth from 2023 onward.

## Key Findings
- **Market Concentration Risk**: Top 3 countries control 58% of global coffee production, creating significant supply vulnerability
- **Climate Impact**: Strong correlation (0.65) between climate factors and yield fluctuations, threatening production stability
- **Consumption Growth**: Income levels strongly drive consumption growth (0.81 correlation)  
- **Premium Segment**: Premium coffee segment growing 3.2x faster than conventional coffee

## Data Sources
- International Coffee Organization (ICO): Production and price data
- World Bank Economic Indicators: Economic metrics
- UN Comtrade Statistics: Trade data
- Industry Sustainability Reports: Sustainability metrics

## Methodology
1. **Data Collection**: Gathered 12 years of annual data covering production, consumption, prices, and market metrics
2. **Data Preprocessing**: Standardized units (60kg bags), normalized price data to USD/lb
3. **Exploratory Data Analysis**: Identified key trends and relationships in the coffee market
4. **Correlation Analysis**: Measured relationships between production, price, climate, and consumption
5. **Growth Projection**: Developed market value growth projections through 2030

## Repository Structure
- `data/`: Raw and processed datasets
- `notebooks/`: Jupyter notebooks showing the analysis process
- `src/`: Python modules for data processing, visualization, and modeling
- `reports/`: Presentation slides and figures
- `requirements.txt`: Required Python packages

## Setup and Reproduction
```bash
# Clone this repository
git clone https://github.com/keerthidasari/coffee-market-analysis.git

# Install required packages
pip install -r requirements.txt

# Run the notebooks in sequence
jupyter notebook notebooks/

# RenewableEnergyMarketAnalysis

## Project Overview
This repository contains a comprehensive analysis of global renewable energy adoption trends, with a particular focus on wind and solar energy in the UK. Using data from the UNSD Energy Statistics Database, the project applies advanced data science techniques to segment countries based on renewable adoption patterns, analyze energy flows, and forecast future capacity growth.

## Key Features
  1. Country Clustering Analysis: K-means clustering to identify distinct renewable adoption patterns across countries
  2. Time Series Forecasting: Hybrid models combining ARIMA with machine learning techniques (Random Forest, SVR) to project renewable capacity growth to 2030
  3. Energy Flow Analysis: Detailed breakdown of UK energy consumption by sector and source
  4. Blockchain Integration Potential: Assessment of opportunities for blockchain applications in renewable energy markets
  5. Stakeholder Analysis: Tailored insights for energy companies and real estate managers

## Technical Implementation
  1. Data Processing: Cleaning, transformation, and feature engineering on UNSD energy statistics
  2. Statistical Analysis: Calculation of capacity factors, growth rates, and market penetration metrics
  3. Machine Learning: Implementation of clustering and forecasting models with hyperparameter optimization
  4. Data Visualization: Creation of interactive visualizations of energy trends and forecasts

## Repository Structure
    --> /data: Raw and processed datasets
    --> /notebooks: Jupyter notebooks containing the analysis
    --> /visualizations: Generated charts and figures
    --> /reports: Final briefing documents for stakeholders
    --> /models: Serialized machine learning models for forecasting

## Getting Started

### Clone this repository
git clone https://github.com/yourusername/renewable-energy-analysis.git

### Install required packages
pip install -r requirements.txt

### Run the Jupyter notebooks
jupyter notebook

### Technologies Used
  1. Python 3.12
  2. Pandas & NumPy for data processing
  3. Scikit-learn for machine learning models
  4. Statsmodels for time series analysis
  4 Matplotlib & Seaborn for visualization

## Future Work
  * Integration of additional renewable sources (hydro, geothermal, bioenergy)
  * Regional analysis within countries to identify local trends
  * Enhanced blockchain implementation models with smart contract examples
  * Real-time data pipeline for continuous monitoring of renewable growth

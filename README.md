# 601-Project

## Project Overview

This project aims to explore traffic accident patterns in Calgary under various weather conditions and detect if any patterns exist in incident details. We sourced traffic incident data from Open Calgary and climate data from the Government of Canada.

## Repository Structure
1. Main Folder - Contains the primary report, datasets, initial project proposal document, and this README file.
2. CityMaps - Contains images and details about the map of the City of Calgary.
3. Hourly Precipitation Data 2024 - Contains additional datasets used for precise aggregation and analysis of precipitation.

## How to Use This Repository
1. Open the Jupyter Notebook (Project 601.ipynb) to review the step-by-step data processing and visualization done in this project.
2. Original dataset sources can be viewed in .csv format if desired.
3. High-quality images of the city map and scatterplots can be viewed in CityMaps if desired.

## Data Processing & Analysis
The analysis was conducted using Python, employing the following techniques:

- Data Cleaning: Handled missing values by imputing mean values for numerical data and mode values for categorical data. Date formats were standardized using regex.

- Exploratory Data Analysis: Used a variety of libraries (pandas, matplotlib, seaborn, geopandas, plotly) and functions to identify key metrics and patterns relating to traffic incidents.

- Visualizations:
  - Heat maps, Scatterplots & Correlation Matrices (seaborn)
  - Line Plots, Histograms, & Pie Charts (matplotlib.pyplot)
  - Interactive Maps (geopandas and plotly)
  - Key Insights
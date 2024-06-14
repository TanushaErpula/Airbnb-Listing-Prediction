# Airbnb Australia Analysis

This repository contains an analysis of Airbnb listings in Melbourne, Victoria, Australia. The project involves data cleaning, exploratory data analysis (EDA), and predictive modeling to understand and predict various aspects of Airbnb listings.

## Table of Contents

- [Project Overview](#project-overview)
- [Files and Directories](#files-and-directories)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)


## Project Overview

The aim of this project is to analyze Airbnb data for Melbourne to uncover insights about price distribution, availability, and the influence of various factors on these attributes. The analysis is carried out using Python and Jupyter notebooks, with a final report summarizing the findings.

## Files and Directories

- **data/**
  - `Airbnb_Australia.csv`: The original dataset containing Airbnb listings.
  - `cleaned_data.csv`: The cleaned dataset generated after preprocessing.

- **notebooks/**
  - `Airbnb_Australia_Final.ipynb`: The main Jupyter notebook with the full analysis and modeling.
  - `data_cleaning.ipynb`: Notebook detailing the data cleaning process.

- **reports/**
  - `Airbnb_Austrlia_Final_Report-1.pdf`: The final report summarizing the analysis and results.

- **src/**
  - `data_preprocessing.py`: Python script for data cleaning.
  - `exploratory_analysis.py`: Python script for exploratory data analysis.
  - `modeling.py`: Python script for building and evaluating predictive models.

- **visualizations/**
  - `price_distribution.png`: Visualization of the price distribution.
  - `room_distribution.png`: Visualization of room types distribution.
  - `correlation_plot.png`: Correlation plot of various features.
  - `availability_price.png`: Scatter plot showing availability vs. price.


- **README.md**: This README file.


## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/Airbnb-Australia-Analysis.git
   cd Airbnb-Australia-Analysis
## Usage
## Data Cleaning

To clean the dataset, run the data_cleaning.ipynb notebook or the data_preprocessing.py script:

jupyter notebook notebooks/data_cleaning.ipynb


python src/modeling.py
## Results
The key findings from the analysis include:

**Price Distribution**: Detailed insights into how prices are distributed across different neighborhoods and room types.

**Availability Patterns:** Analysis of availability in relation to various factors like price and location.

**Predictive Models:** Models predicting listing availability with high accuracy, particularly using Random Forest Regressor.
Refer to the Airbnb_Austrlia_Final_Report-1.pdf in the reports/ directory for a comprehensive summary.




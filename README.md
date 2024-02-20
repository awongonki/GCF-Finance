Green Climate Fund (GCF) Project and Financial Analysis Feb 2024

Overview
This repository contains an analysis of the Green Climate Fund (GCF) projects and financial allocations, offering an in-depth perspective on the fund's undertakings from 2015 to 2023.

Data Sources
The analysis harnesses two principal data sources:

GCF-Projects_Finance_Feb2024: Provides detailed financial information related to GCF projects.
GCF-Projects_Feb2024: Offers a comprehensive overview of GCF projects.

Methodology

Data Harmonization
To ensure consistency across the dataset, all monetary values in Euros were converted to US dollars using a 1:1.08 exchange ratio.

Preliminary Data Exploration
An exploratory analysis was conducted to understand the scope of the GCF's activities. Key findings include:

The GCF has been involved in over 243 projects across 129 countries.
These projects were executed in collaboration with 58 different entities.
The aggregate financing for these projects amounted to $51.83 billion.

Financing Trend Analysis
A linear regression analysis was deployed to assess whether the current financing trajectory could meet the $50 billion target by 2030. This analysis was conducted using the Python SKlearn library, based on the assumption that the GCF budget would change at a uniform rate over time.

Dependencies

Python 3
SKlearn library

Usage
To replicate the analysis, run the Jupyter Notebook GCF_Analysis.ipynb in this repository.

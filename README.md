**This repository contains an analysis of the Green Climate Fund projects and financial allocations, offering an in-depth perspective on the fund's undertakings from 2015 to 2023.**

**Data Sources** <br>
The analysis harnesses two principal excel workbook download from GCF Open Library:<br>
https://data.greenclimate.fund/public/users/signin-required <br>

**Methodology** <br>

**Data Harmonization** <br>
To ensure consistency across the dataset, all monetary values in Euros were converted to US dollars using a 1:1.08 exchange ratio.

**Preliminary Data Exploration** <br>
An exploratory analysis was conducted to understand the scope of the GCF's activities. Key findings include:

The GCF has been involved in over 243 projects across 129 countries.
These projects were executed in collaboration with 58 different entities.
The aggregate financing for these projects amounted to $51.83 billion.

**Financing Trend Analysis** <br>
A linear regression analysis was deployed to assess whether the current financing trajectory could meet the $50 billion target by 2030. This analysis was conducted using the Python SKlearn library, based on the assumption that the GCF budget would change at a uniform rate over time.

**Usage** <br>
To replicate the analysis, run the Jupyter Notebook in this repository.

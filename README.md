# Kickstarter Campaign Analysis

Has Kickstarter Peaked? What does crowd-funding on Kickstarter look like in 2019? 

A data-driven exploration of 182k unique Kickstarter campaigns explored these questions and identified the characteristics of successful Kickstarter campaigns.

The analysis is summarized in a [brief report on medium.](https://medium.com/@mikebrady44/peak-kickstarter-35dc7f242a2a) 

Within this repository, you can view and explore all of the data and code that supported the report. This repository includes: 
- **Jupyter notebooks:** Separate notebooks walkthrough the data wrangling, exploration, and visualization stages of the project
- **Raw Data:** The original source of the data is a scraping company, [Web Robots](https://webrobots.io/kickstarter-datasets/). This repository contains the inidivudal CSV files for the March, 14, 2019 scrape of Kickstarter's website. The compiled and cleaned dataset is too large for Github; please reach out if you would like access to the compiled dataset (can also be replicated with the data wrangling notebook). 
- **Supplemental Data:** These datasets are mostly slices of the master dataset used to support the analysis. There is also a generic US states dataset that is useful for mapping state initials to state names.
- **Graphics:** .png files are available for all of the visualizations used in the report. The chlorpleth was made with Vega-lite (via Altair), the .json file is avialable within the visualizations folder


# COVID-19 Data Analysis Report - Nairobi, Kenya 
## Overview

This Jupyter Notebook (`COVID-19_Analysis_Report.ipynb`) provides a comprehensive analysis of the COVID-19 pandemic using the Our World in Data (OWID) dataset. The report includes data loading, cleaning, exploratory data analysis (EDA), visualization, and key insights.

The analysis aims to explore global trends in the pandemic, with a specific context for the user's location in Nairobi, Kenya. However, the primary analysis is based on historical data available up to April 12, 2023, as per the last data interaction. For a truly up-to-date understanding of the situation in Nairobi as of May 6, 2025, the latest version of the OWID dataset would need to be analyzed.

## Contents

The notebook is structured as follows:

1.  **Setup and Data Loading:** Imports necessary libraries and loads the OWID COVID-19 dataset from a specified CSV file.
2.  **Data Cleaning and Preparation:** Converts the 'date' column to datetime objects and performs basic handling of missing values by filling key numeric columns with 0.
3.  **Exploratory Data Analysis (EDA):**
    * Identifies the latest date in the dataset.
    * Filters data for selected countries: Kenya, USA, India, and Afghanistan.
    * Generates line charts visualizing total cases, total deaths, daily new cases, and the death rate over time for the selected countries.
    * Creates a bar chart showing the top 10 countries by total COVID-19 cases as of the latest date.
    * Produces interactive choropleth maps illustrating the global distribution of total cases and the percentage of the population vaccinated (at least 1 dose) as of the latest date.
    * Includes sections to visualize hospitalization and ICU patient data over time for the selected countries, if available in the dataset.
4.  **Key Insights and Narrative:** Presents a Markdown-formatted summary of the key findings based on the analysis up to April 12, 2023. It highlights global trends, discusses the situation in the selected countries, and provides considerations for the current context in Nairobi, Kenya, as of May 6, 2025.

## Prerequisites

To run this Jupyter Notebook, you will need the following Python libraries installed:

* **pandas:** For data manipulation and analysis.
* **matplotlib:** For basic plotting.
* **seaborn:** For enhanced statistical visualizations.
* **plotly.express:** For creating interactive visualizations, including choropleth maps.
* **ipywidgets:** (Optional, for interactive elements within the notebook itself, though the current version focuses on static outputs).
* **IPython.display:** For displaying Markdown content.

You can install these libraries using pip:

```bash
pip install pandas matplotlib seaborn plotly ipywidgets


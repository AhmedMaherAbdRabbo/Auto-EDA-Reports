# Auto-EDA-Reports

This repository provides an automated solution for generating Exploratory Data Analysis (EDA) reports. It is designed to streamline the process of understanding and analyzing datasets by automatically creating comprehensive and insightful reports. This tool is particularly useful for data scientists, analysts, and anyone who needs to quickly gain insights from a dataset.

## Overview

The **Auto-EDA-Reports** repository is a Python-based tool that automates the generation of EDA reports. It uses popular data analysis and visualization libraries to analyze datasets and produce detailed reports, including summary statistics, visualizations, and insights. The tool is designed to save time and effort by automating repetitive tasks in the data exploration process.

## Dataset

This dataset contains Quality of Life Indices for countries worldwide. It includes metrics like Quality of Life Index, Purchasing Power Index, Safety Index, Health Care Index, Cost of Living Index, and more. Each country is ranked based on its overall quality of life, with additional indices providing insights into affordability, safety, healthcare, pollution, and climate. The dataset is ideal for comparing living standards across countries and analyzing global trends in quality of life.

## Tools and Libraries

The following tools and libraries are used in this project:

- **Python**: The primary programming language used for the project.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib**: For creating static visualizations.
- **Seaborn**: For creating more advanced and aesthetically pleasing visualizations.
- **Plotly**: For interactive visualizations.
- **Sweetviz**: For automated EDA report generation.
- **Pandas Profiling**: For generating detailed EDA reports.
- **AutoViz**: For automatic visualization of datasets.

## Install Required Libraries

To install the required libraries, run the following command:

```bash
pip install pandas numpy matplotlib seaborn plotly sweetviz pandas-profiling autoviz
```

## Repository Structure

The repository is structured as follows:

```
Auto-EDA-Reports/
├── data/
│   └── sample_data.csv           
├── notebooks/
│   └── Auto_EDA_Report.ipynb      
│   └── sample_report.html         
│   └── autoviz_plots
│   └── images
├── README.md                      
```

## Kaggle Notebook

A Kaggle notebook demonstrating the use of this tool is available [here](https://www.kaggle.com/code/ahmedmaherabdrabbo/quality-of-life-auto-eda-reports). The notebook provides a step-by-step guide on how to use the tool to generate EDA reports.

## Results

The tool generates an interactive HTML report that includes:

- **Dataset Overview**: Summary of the dataset, including the number of rows, columns, and missing values.
- **Variable Analysis**: Detailed analysis of each variable, including distribution, statistics, and visualizations.
- **Correlation Analysis**: Heatmap and correlation matrix showing relationships between variables.
- **Missing Data Analysis**: Identification and analysis of missing data in the dataset.


---
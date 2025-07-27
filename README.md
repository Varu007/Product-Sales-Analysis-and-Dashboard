# Product-Sales-Analysis-and-Dashboard
This repository contains an end-to-end analysis of sales data using Jupyter Notebook and an interactive Power BI dashboard. The primary dataset used is `superstore_sales.xlsx`, which captures sales transactions for a fictional retail superstore. The project provides actionable insights into sales and profit trends, supporting data-driven decision-making.

## Table of Contents

- [Project Overview](#project-overview)
- [Prerequisites](#prerequisites)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Analysis and Visualizations](#analysis-and-visualizations)
- [Results](#results)

---

## Project Overview

The Product Sales Analysis and Dashboard project aims to:
- Analyze historical sales data to uncover trends and patterns.
- Provide actionable insights through data visualization.
- Build an interactive dashboard for real-time exploration of sales metrics.

### Prerequisites

- Python (Recommended: 3.x)
- Jupyter Notebook
- Power BI Desktop
- Required Python libraries (see individual notebook requirements)

## Features

- **Comprehensive Data Analysis:**  
  - Data cleaning and preprocessing  
  - Exploratory data analysis (EDA)  
  - Sales and profit trend analysis  
  - Key performance metrics and visualizations

- **Interactive Dashboard:**  
  - Drill-down capability by region, category, and time  
  - Dynamic filters for tailored insights  
  - Visual tracking of both sales and profit trends over time

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Varu007/Product-Sales-Analysis-and-Dashboard.git
   cd Product-Sales-Analysis-and-Dashboard
   ```

2. **Install required packages:**
   Make sure you have [Anaconda](https://www.anaconda.com/) or Python 3.x installed.
   ```bash
   pip install -r requirements.txt
   ```
   Or set up the environment using an environment.yml file if provided:
   ```bash
   conda env create -f environment.yml
   conda activate sales-analysis
   ```

3. **Open Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. **Use the Power BI Dashboard**
    - Open `superstore_sales.xlsx` in Power BI Desktop.
    - Load the Power BI dashboard file provided in the repository.
    - Interact with visualizations and filters to analyze sales and profit trends.

## Usage

- Open the main notebook (e.g., `Product_Sales_Analysis.ipynb`) in Jupyter.
- Follow the instructions in each cell to run the analysis.
- Update the data file path if you use your own dataset.

## Data

- The analysis uses a sample sales dataset located in the directory.
- Dataset columns typically include: `Order ID`, `Product`, `Category`, `Quantity Ordered`, `Price Each`, `Order Date`, `City`, etc.
- You can replace the sample data with your own sales data (ensure similar column names for compatibility).

## Analysis and Visualizations

Key analyses and visualizations include:
- Monthly sales trends
- Top-selling products and categories
- Sales by city and region
- Revenue analysis
- Interactive dashboard (e.g., using Plotly, Voila, or other tools)

## Results

- The dashboard provides an at-a-glance view of key metrics and trends.
- Insights can help inform inventory decisions, marketing strategies, and sales forecasting.
<img width="914" height="493" alt="image" src="https://github.com/user-attachments/assets/de75d9b8-6288-4ab8-9da7-fda02b37baeb" />




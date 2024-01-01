# Economic-EDA

# EDA Project: Economic Analysis of Unemployment and Labor Force Participation Rates

## Overview
This project explores and analyzes economic data related to unemployment and labor force participation rates in the United States. The primary focus is on understanding the impact of these economic indicators at both the national and state levels. The analysis utilizes data from the Federal Reserve Economic Data (FRED) API and incorporates visualizations to provide insights into trends and patterns.

## Prerequisites
To run this project, you need to install the required Python packages. Use the following command to install them:

```bash
!pip install fredapi > /dev/null
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import plotly.express as px
from fredapi import Fred
import time
```

## Data Collection
The project utilizes the FRED API to fetch economic data related to the S&P 500, unemployment rates, and labor force participation rates. The API key is required for accessing FRED data. You can obtain your API key from the FRED website ([https://fred.stlouisfed.org/](https://fred.stlouisfed.org/docs/api/fred/)).

## S&P 500 Analysis
The initial analysis involves fetching and plotting the historical data of the S&P 500 index to visualize its trends over time.

## State-Level Unemployment Analysis
The project further explores state-level unemployment rates by fetching and joining multiple data series. The analysis includes handling missing data, filtering based on specific criteria, and cleaning the dataset for meaningful insights.

## Visualization
Visualizations are an integral part of this project. Plotly Express and Matplotlib are used to create various visualizations, including line charts, bar charts, and comparative plots, providing a comprehensive view of the economic trends.

## State-Level Comparison
The project compares unemployment rates with labor force participation rates for each state, offering a deeper understanding of the relationship between these economic indicators.

## Project Structure
- **Economic EDA with Pandas.ipynb**: Jupyter Notebook containing the code for data collection, analysis, and visualization.
- **README.md**: This file, providing an overview of the project, prerequisites, and instructions.

## Instructions for Running the Code
1. Obtain a FRED API key from [https://fred.stlouisfed.org/](https://fred.stlouisfed.org/docs/api/fred/).
2. Install the required Python packages using the provided command.
3. Run the code cells in the Jupyter Notebook sequentially.

## Results
The project concludes with visualizations showcasing the unemployment rates and labor force participation rates for each state. Comparative analyses highlight patterns and variations in economic indicators over time.

Feel free to explore, modify, and build upon this project for further analysis and insights into economic trends.

**Note:** Ensure you comply with FRED's terms of use when using the API key for data retrieval.

Happy exploring!

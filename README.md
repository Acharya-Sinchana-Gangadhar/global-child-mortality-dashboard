# Global Child Mortality Dashboard (UNICEF Data)

## Introduction
This interactive Shiny dashboard allows users to explore global child mortality trends using UNICEF data. Users can upload an Excel dataset, analyze mortality trends for individual countries and rank countries based on their child mortality rates.

## Features
- **Upload Data**: Load an Excel file containing UNICEF child mortality data.
- **Country Trend Analysis**: View historical trends in child mortality for a selected country.
- **Country Ranking**: See how different countries rank based on their child mortality rates over time.
- **Rank Table**: View a detailed tabular representation of ranked countries for a selected year.

## How to Use
1. **Upload Data**: Click the "Upload Excel File" button and select a valid `.xlsx` file.
2. **Process Data**: After uploading, click "Process Data" to clean and transform the dataset.
3. **Select a Country**: Use the dropdown menu to choose a country and view its trend analysis.
4. **Navigate Tabs**: Use the tab panel to switch between different visualizations:
   - "Country Trend" for mortality trends over time.
   - "Country Ranking" to see ranks over time.
   - "Rank Table" for detailed rankings in a specific year.

## Explanation of Plots
### 1. Country Trend Plot
- **What it Shows**: A time series line chart displaying child mortality trends for a selected country.
- **Why it is Useful**: Helps analyze how child mortality rates have changed over time and observe improvements or deteriorations.

### 2. Country Ranking Plot
- **What it Shows**: A line chart tracking the ranking of a selected country over time.
- **Why it is Useful**: Helps in understanding how a country's mortality ranking has evolved over the years relative to others.

### 3. Rank Table
- **What it Shows**: A table listing countries ranked by child mortality for a selected year.
- **Why it is Useful**: Offers a detailed, sortable, and searchable list for deeper analysis.

## Additional Notes
- **SDG Region & UNICEF Region**: Displays the Sustainable Development Goals (SDG) region and UNICEF region for the selected country.
- **Data Cleaning**: The app automatically cleans and processes the uploaded dataset to ensure consistency.

## Requirements
- R should be installed.
- Required libraries: `shiny`, `shinydashboard`, `readxl`, `dplyr`, `tidyr`, `ggplot2`, `plotly`, `leaflet`, `DT`.

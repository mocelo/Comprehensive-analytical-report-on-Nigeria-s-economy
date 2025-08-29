# Comprehensive-analytical-report-on-Nigeria-s-economy
A data on current situation of Nigeria's economy 

# Analysis of Macroeconomic Data: GDP Growth, Inflation, and Company Profitability

This notebook performs an analysis of macroeconomic data, focusing on the relationship between GDP growth, inflation (CPI), and the profitability of selected companies.

## Data

The analysis uses data from an Excel file named "Macro Data - N.xlsx". The data is split into different sheets:

- **"GDP sheet"**: Contains GDP data by sector and sub-sector across several years.
- **"CPI sheet"**: Contains Consumer Price Index (CPI) data for various items across several years.
- **"COMPANY PAT"**: Contains Profit After Tax (PAT) data for selected companies across several years.

## Analysis Steps

The analysis is structured into several key sections:

1.  **GDP Data Preparation and Growth Rate Calculation**:
    - Loads the GDP data.
    - Cleans and prepares the data, including assigning sectors to sub-sectors and rounding numerical values.
    - Calculates the year-on-year GDP growth rate for the overall economy and for each sector (Agriculture, Manufacturing, and Services) and sub-sector.

2.  **CPI Data Preparation and Inflation Rate Calculation**:
    - Loads the CPI data.
    - Cleans and prepares the data, including renaming columns and removing unnecessary rows.
    - Calculates the year-on-year inflation rate for "All Items" and for specific CPI items (e.g., Food, Transport, Housing).

3.  **Analysis of Relationship between Overall Inflation and GDP Growth**:
    - Reshapes the GDP growth rate data and "All Items" inflation data for easy comparison.
    - Merges the growth rate and inflation data based on the year.
    - Calculates the correlation between the "All Items" inflation rate and the GDP growth rate for each sub-sector.
    - Visualizes the relationship using scatter plots and line plots for selected sub-sectors.

4.  **Analysis of Relationship between Specific CPI Inflation and Related GDP Sector Growth**:
    - Reshapes the inflation rates for key specific CPI items.
    - Merges the melted growth rate data with the specific CPI inflation data.
    - Defines relationships between specific CPI items and potentially related GDP sub-sectors.
    - Calculates the correlation between the inflation rates of specific CPI items and the GDP growth rate of potentially related sub-sectors.
    - Creates visualizations (scatter plots and line plots) to show the relationship between inflation in specific CPI items and the growth of relevant GDP sectors.

5.  **Company Profitability Data Preparation**:
    - Loads the company profitability data.
    - Cleans and prepares the data by dropping unnecessary rows.

## Key Findings (Based on the analysis performed in the notebook)

*   The correlation analysis between "All Items" inflation and GDP growth revealed varying relationships across sub-sectors. Some sectors showed positive correlation (growth increases with inflation), others showed negative correlation (growth decreases with inflation), and some showed little to no linear relationship.
*   Analysis of specific CPI inflation categories and related GDP sectors also showed mixed results, with some categories of inflation appearing to be negatively associated with the growth of certain sectors (e.g., Food inflation and Agriculture GDP growth, Housing/Utility inflation and Power GDP growth).
*   Visualizations helped to illustrate these relationships and trends over time.

## How to Use

1.  Ensure you have the "Macro Data - N.xlsx" file in the same directory as the notebook.
2.  Run the notebook cells sequentially.
3.  Examine the outputs and visualizations to understand the relationships between GDP growth, inflation, and company profitability.

## Dependencies

The notebook requires the following libraries:

-   pandas
-   numpy
-   matplotlib
-   seaborn

These can be installed using pip if not already available in your environment.

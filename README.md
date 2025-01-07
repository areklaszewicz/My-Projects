# Veteran Work Support Project

![image](https://github.com/user-attachments/assets/85e44a7b-1308-4c20-a215-6921cbf5362f)


## Project Goal

The main goal of this project is to analyze veterans' data from all counties across the United States and identify the 100 counties with the highest need for employment programs supported by the Department of Veterans Affairs. This analysis will involve investigating various factors that may inform in which counties these programs will most effectively improve employment outcomes.

## Data Details
Atlas of Rural and Small-Town America - datasets from Economic Research Service (U.S. Department of Agriculture)

- People — Demographic data from the American Community Survey (ACS), including age, race and ethnicity, migration and immigration, education, household size, and family composition.
  -	295,507 rows
  -	5 columns

- Jobs — Economic data from the Bureau of Labor Statistics and other sources, including information on employment trends, unemployment, and industrial composition of employment from the ACS.
  -	248,192 rows
  -	7 columns
  
- Income — Data on median household income, per capita income, and poverty (including child poverty).
  -	42,160 rows
  -	5 columns

- Veterans — Data on veterans, including service period, education, unemployment, income, and other demographic characteristics.
  -	104,317 rows
  -	5 columns
  
- Variable Name Lookup — Data that explains the values in the 'Attribute' column, which can be found in each table.
  -	249 rows
  -	5 columns

  
- Table: Income, People, Veterans were updated to 2017–21 (5-year average county-level data) by data from the American Community Survey (ACS)
- LINK: [Download Here](https://www.ers.usda.gov/data-products/atlas-of-rural-and-small-town-america/documentation/)
- File type: CSV

## Tools 
- Excel - Power Query - Data Cleaning
- Power BI - Exploratory Data Analysis, Data Visualization

## Data Cleaning
- Importing and reviewing data.
- Handling missing and unnecessary values.
![image](https://github.com/user-attachments/assets/154185c4-2755-4a19-8d1a-e72cd2b1c7c7) - excluding columns with "000"

- Pivoting and removing columns.
- Transporting columns to other table by merging queries.
- Adding conditional columns.
![image](https://github.com/user-attachments/assets/265ed28d-f8ec-4266-bb8a-288ef59be0eb)

- Standardizing Formats.
- Creating a fact table for the star schema.
![image](https://github.com/user-attachments/assets/2f6e931f-409f-4e91-938e-a4396bc1b28f)

## Exploratory Data Analysis

In the EDA phase, I explored the stocked data to answer questions essential for this project:
- What is the rate and number of veterans in a given region?
- What is the rate of disability among veterans in a given region?
- What is the proportion of males and females among veterans?
- What is the rate of unemployed veterans in a given region?
- In which counties is the veteran labor force participation rate the lowest?
- What is the difference in educational levels between veterans and the overall population?
- How does the correlation look between the rate of unemployed veterans and the percentage of veterans with a college degree/the percentage of veterans without a High School diploma?"
- In which counties is the median yearly income of veterans the lowest?
- How does the correlation look between veterans' yearly income and the rate of unemployed veterans/the percentage of veterans with a college degree/the percentage of veterans without a High School diploma?
- What is the rate and number of veterans in poverty in a given region?
- How does the correlation look between the veteran poverty rate and the rate of unemployed veterans/the percentage of veterans with a college degree/the percentage of veterans without a High School diploma?

### Interesting codes used in the project:
![image](https://github.com/user-attachments/assets/6e9bee2b-a179-482f-8c4e-eb78a0174d79)
- a calculation of civilian labor force average for 2017-2021

![image](https://github.com/user-attachments/assets/82be3552-c0b2-4cef-962c-4fa7c5011baf)
- changing "year" column to date


## Data Visualization 

1. Step by step data visualization
- Customizing special theme.
- Transforming JSON file.
- Adopting Menu Tab.
- Mapping population of veterans
- Making table visual.
- Adding Drill-Through.
- Donut chart and pie chart.
- Grouping and modifying cards.
- Bar chart.
- Editing interactions.

2. Step by step "Employment" page
- Customizing table and map.
- Date Hierarchy in line chart.
- Making visual cards.
- Bar chart.

3. Step by step "Education" page
- Donut charts.
- Constructing correlation charts.
- Adding slicer to chart and deleting blanks in it.

4. Step by step "Income" page
- Adding table chart.
- Bar charts.
- Scatter plot and excluding outliers.
- Navigating Scatter Plots with Bookmarks.

5. Step by step "Poverty" page
- Creating information cards.
- Bar charts.
- Correlation charts.

Step by step process: [Data visualization](https://github.com/user-attachments/files/18336834/Data.visualization.docx)

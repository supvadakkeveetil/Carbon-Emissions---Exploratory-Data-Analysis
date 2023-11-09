# Carbon-Emissions---Exploratory-Data-Analysis
Carbon Emissions across America - An exploratory study using visualizations
## Exploratory Data Analysis Report 
Detailed report for analysis can be found under the link 
......

### Project Title: Carbon Emissions across America: Unveiling Regional Disparities, Key Contributors
#### Introduction 
This report presents a Comprehensive Analysis of CO2 Emissions in the United States, focusing on trends across various sectors and individual states. The objective is to understand the patterns, variations, and potential impacts of CO2 emissions
The motivation for the project comes from the need to tackle the Environmental challenges and the leading causes for these issues. 
#### Data Description 
The Dataset comprises of detailed Co2 emissions across different sectors including Transportation, Electric Power, Industrial Sectors, and others. The data spans a timeline from 2010 to 2021 covering both national and state-level analysis.
Data Source: 
1.	US EPA (Environmental Protection Agency – Data (Historical) on the Greenhouse gas emissions in the United States.
2.	US EIA (Energy Information Administration) – Data on State level emissions, Energy production and Electricity Generation Source.
#### Data Cleaning and Preparation(DataExp_Cleaning_CarbonEmissions.ipynb) 
1.	Import Libraries – Import the necessary libraries, like Pandas, Matplotlib. 
2.	Load Data into the Data Frame – loading the US and Statewise datasets
Converted our data from Excel and CSV files into Pandas Data Frames using the pandas .read_excel() and .read_csv()
3.	Preliminary Data Examination –Used various Pandas function to get an overview of the data.  Looked at the structure of the data frame using .head(), the .info() to check the datatypes and values, and the .describe() for Summary Statistics 
4.	Data Cleaning
•	Handling missing values – Checked for missing values in the data frame using the   df.is.null().sum()
•	Checking for duplicates – using the df.duplicates()
•	Removal on unnecessary Data –drop() function
•	Quality checks on the data – looked to see the final structure of the cleaned-up data frame and made sure that the information and format is consistent across the Data Frames used for our analysis
5.	Data Visualizations – Bar charts and Plots for showing the Trends across the years for different states, sectors.

#### Analysis - 
1. How do the emissions vary across regions /states in US?
CO2 Emissions for States in the US (Average Bar Chart)
A bar chart was created to display the average CO2 Emissions for each state. This visualization allowed for a comparison of emission levels across different states.
![image](https://github.com/supvadakkeveetil/Carbon-Emissions---Exploratory-Data-Analysis/assets/144635564/85b93e67-f257-47b8-9a54-c76f26fa46ae)


Analysis - 
•	Texas and California, two of the largest states in the US, are the two highest producers of Co2 Emissions, followed by Florida, Pennsylvania, Illinois, and Ohio. This could be because they are both rank in the top 2 states for population and economic size.
•	Texas’ emissions are significantly higher than any other state. (Approximately 650 million metric tons)
•	States with Significantly lower emissions- According to EPA, these states often exhibit a combination of lower population density, less energy-intensive industries, cleaner energy sources, and proactive environmental policies contributing to their reduced carbon footprint.

#### Impact Analysis
The analysis revealed several key insights
•	The steady increase in CO2 emissions at the national level, indicates a pressing need for mitigation strategies.
•	Variance in Sectoral contributions across states emphasizing specific sectors demands targeted interventions
•	Disparities between states and the national average signaling the need for tailored policies at the state level.
#### Conclusion
The analysis of CO2 emissions from 2010-2021 showcased diverse trends, sectoral contributions, and state-level variations. The findings show the urgency for proactive measures and polices to address emissions with a particular focus on high -contributing sectors and regions. This data-driven analysis can serve as a valuable guide for formulating targeted strategies to mitigate environmental impacts and foster sustainable practices
#### References
1.	https://www.eia.gov/environment/emissions/state/
2.	https://cfpub.epa.gov/ghgdata/inventoryexplorer/#allsectors/allsectors/allgas/gas/all
3.	https://www.statista.com/statistics/220174/total-us-electricity-net-generation-by-fuel/
4.	https://www.epa.gov/ghgemissions/sources-greenhouse-gas-emissions
5.	https://calmatters.org/environment/2023/01/california-electric-cars

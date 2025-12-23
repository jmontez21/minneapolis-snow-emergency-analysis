Minneapolis Snow Emergency Parking Enforcement Analysis
An analysis of Minneapolis snow emergency parking data examining patterns in vehicle tags and tows across different zones and days during the 2024 snow emergency events.
Overview
This project analyzes real municipal data from Minneapolis snow emergencies to understand parking enforcement patterns. By comparing the number of parking tags issued versus vehicles actually towed across different zones and days, the analysis reveals insights about enforcement intensity and compliance patterns throughout the city.
Technologies Used

R - Statistical programming and data analysis
Quarto - Reproducible data analysis and reporting
tidyverse - Data manipulation and transformation
ggplot2 - Data visualization
dplyr - Data wrangling (joins, grouping, summarizing)

Data Sources
The analysis uses two datasets from the 2024 Minneapolis snow emergencies:

Tags Dataset: Parking violations tagged during snow emergencies
Tows Dataset: Vehicles towed during snow emergencies

Data is publicly available from the Minneapolis Open Data portal.
Key Analysis Features

Multi-table joins to combine tags and tows data by zone
Data aggregation to count tags and tows per zone
Faceted visualization showing patterns across different days
Comparative analysis between tags issued vs. vehicles towed
Zone-based insights identifying high-enforcement areas

Visualizations
The analysis produces visualizations comparing:

Number of tags issued per zone
Number of vehicles towed per zone
Day-by-day enforcement patterns
Zones ordered by enforcement intensity

Key Findings
The analysis reveals which tow zones experienced the highest enforcement activity and how enforcement patterns varied across different days of the snow emergency period.

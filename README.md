Project: UK Accident Trends Casualty Analysis
Author: Muhammad Suleman
Description: Analyzed UK road accident data (2005 – 2014) to identify accident trends, casualty patterns, dangerous regions, road conditions, and accident severity using interactive visualizations and geospatial analysis.
Environment: Python, Jupyter Notebook, Pandas, GeoPandas, Plotly
Project Overview

This project provides a comprehensive analysis of road accident trends in the United Kingdom (UK) between 2005 and 2014. The analysis focuses on accident frequency, casualty distribution, dangerous road conditions, regional accident patterns, highway authorities, and accident severity.

Interactive visualizations and geospatial analysis were used to uncover insights and patterns from more than 1.5 million accident records.

Dataset Information

The project uses UK road accident datasets from:

2005 – 2007
2009 – 2011
2012 – 2014
Dataset Features

The dataset includes:

Accident locations
Number of vehicles involved
Number of casualties
Road type
Speed limits
Weather conditions
Road surface conditions
Light conditions
Highway authorities
Urban/Rural classifications
Accident severity
Technologies Used
Python
Pandas
NumPy
GeoPandas
Matplotlib
Seaborn
Plotly
Jupyter Notebook
Data Preprocessing

The following preprocessing steps were performed:

Combined accident datasets from multiple years
Removed columns with excessive missing values
Handled null values
Converted date and time columns into datetime format
Created additional features:
Hour
Month
Week in Month
Merged external datasets for:
Regional analysis
Road network classification
Highway authority mapping
Key Questions Explored
1. Accident Trends
What is the trend of road accidents in the UK from 2005 – 2014?
How did casualty numbers change over time?
2. Regional Analysis
Which UK regions had the highest and lowest accident rates?
Did accident trends vary across regions?
3. Highway Authority Analysis
Which highway authorities were the most dangerous?
Which were the safest?
4. Time-Based Analysis
Which hours of the day recorded the highest accidents?
Which weekdays and months had the most accidents?
5. Road Network & Road Type Analysis
Which road network groups were most dangerous?
Which road types had the highest accident rates?
6. Environmental Conditions Analysis
How weather, road surface, and light conditions affected accidents.
7. Pedestrian Crossing Analysis
Whether pedestrian crossings influenced accident occurrence.
8. Casualty & Vehicle Distribution
Number of casualties per accident.
Number of vehicles involved per accident.
9. Speed Limit Analysis
Which speed limits were most associated with accidents.
10. Urban vs Rural Analysis
Accident occurrence comparison between urban and rural areas.
11. Accident Severity Analysis
Distribution of fatal, serious, and slight accidents.
Visualizations Included

The project includes:

Line Charts
Scatter Plots
Bar Charts
Histograms
Pie Charts
Interactive Maps
Geospatial Visualizations
Major Insights
Accident Trends
Road accident casualties generally declined between 2005 – 2014.
A noticeable increase was observed around 2012.
Regional Findings
South East England recorded the highest number of casualties.
North East England recorded the lowest.
Time-Based Findings
Accident peaks occurred around:
8 AM
5 PM
Saturdays recorded the highest accident frequency.
Road Type Findings
Single carriageways had the highest accident rates.
Environmental Findings
Most accidents occurred during:
Fine weather
Dry road conditions
Daylight conditions
Speed Limit Findings
Most accidents were associated with 30 mph speed limits.
Urban vs Rural
Urban areas experienced significantly more accidents than rural areas.
Accident Severity
Most accidents were classified as slight severity.
Fatal accidents represented only a small percentage.
Project Structure
UK-Road-Accident-Analysis/
│
├── UK_road_accident_analytics.ipynb
├── uk-data/
│   ├── accidents_2005_to_2007.csv
│   ├── accidents_2009_to_2011.csv
│   ├── accidents_2012_to_2014.csv
│   ├── LAD.csv
│   ├── LAD3.csv
│   └── LAD4.csv
│
├── images/
└── README.md
Conclusion

This project provides a detailed analysis of UK road accident patterns over a 10-year period. Through exploratory data analysis, geospatial mapping, and interactive visualizations, the project identifies critical risk factors and accident trends that can support road safety awareness and data-driven decision making.

Author

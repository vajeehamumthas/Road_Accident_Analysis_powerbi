# Road Accident Analysis (Power BI Dashboard)

An interactive Power BI dashboard analysing **307,973 UK road accidents** from 2021 and 2022, to understand when, where and why accidents become severe.

## Objective
- Understand accident patterns over time, by area, day and hour
- Identify high-risk conditions: speed limit, light, weather, road type and junctions
- Measure severity and casualties
- Let users filter by year, severity and area

## Dataset
- 307,973 accident records, 21 attributes, covering 2021 and 2022
- Groups: time, location, road, environment, vehicles and outcome (severity and casualties)
- The file `Road_Accident_Data.zip` contains the data as a CSV

## Tools
Power BI, Power Query, DAX, Excel

## Method
1. Collect data from Excel
2. Clean: nulls, duplicates, label typos, data types
3. Model: Calendar table and DAX measures for the KPIs
4. Visualize: 3-page dashboard with slicers and navigation
5. Analyse: patterns, risk factors and recommendations

## Dashboard pages
| Page | What it shows |
|---|---|
| Accident Analysis | Accident volume, severity, area, days and trend |
| Casualty Analysis | Casualties by vehicle type, severity, area and road surface |
| Analysis | Speed limit, light, weather, road type and junctions |

## Key findings
- Accidents fell **11.7%** in 2022 (163,554 to 144,419); fatal accidents fell **34.2%** (2,355 to 1,549)
- **64.5%** of accidents are in urban areas, but rural accidents are more severe (17.9% fatal or serious vs 12.7%)
- Accidents peak at **8 am and 5 pm**, and on **Fridays**
- 60 mph roads have the highest severe share (**21.6%**)
- Unlit roads at night: **22.5%** severe vs **13.7%** in daylight
- T-junctions account for **31.4%** of accidents; roundabouts have the lowest severe share (**8.9%**)
- Cars are involved in **77.9%** of accidents; motorcycles in **8.1%**

## Limitations
The dashboard shows patterns in the data, not proven causes.

## Files
- `Road Accident Data powerbi_Dashboard.pbix`: the Power BI report
- `Road_Accident_Analysis_ppt.pptx`: the presentation
- `Road_Accident_Data.zip`: the dataset (CSV)

## Author
Vajeeha Mumthas PV
[LinkedIn](https://linkedin.com/in/vajeeha-undefined-169594438) | [GitHub](https://github.com/vajeehamumthas)

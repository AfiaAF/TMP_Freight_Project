# TMP Freight Project
Analyzing US–Canada & US–Mexico Freight Trends using CRISP-DM Framework
________________________________________

## 1. Project Overview  
The objective of this project is to analyze the transportation data provided by the Bureau of Transportation Statistics (BTS) to uncover insights related to the efficiency and impacts of freight transportation across various modes (road, rail, air, pipeline and water). Using this data, the goal is to identify inefficiencies, recognize patterns, and propose actionable solutions to improve the overall performance and sustainability of the transportation systems.
________________________________________

## 2. Business Questions  
1.	What are the overall trends in freight volume and value or revenue over time? 
2.	Which transport mode (truck, rail, pipeline, air, vessel) dominated in terms of weight and value? 
3.	How did trade values evolve per country (U.S.–Canada vs. U.S.–Mexico)? 
4.	Which ports of entry consistently handled the highest number of shipments? 
5.	What were the top commodity types traded with each country? 
6.	What was the total number of shipments and value made across the years? 
7.	Which freight modes had higher freight charges on average? 
________________________________________

## 3. Data Understanding
•	Source: U.S. Bureau of Transportation Statistics (Transborder Freight Data)

Initial Observations:

•	Missing or partial data entries

•	Some aggregated values by mode or commodity

•	Lacks external context such as pricing, weather, and real-time tracking
________________________________________

## 4. Data Preparation
•	Cleaning: Handled nulls and duplicates, and changed data types where appropriate

Feature Engineering:

•	Grouped by mode of transport, trade type, country, etc

•	Calculated average charges and shipment ratios

•	Created year-over-year trend indicators
________________________________________

## 5. Analysis & Visualization
•	Used line charts, bar graphs, and donut charts to explore:

•	Freight trends by year and mode

•	Port activity levels and bottlenecks

•	Mode cost comparison

•	Country-specific commodity flows

________________________________________

## 6. Key Insights & Recommendations
•	Freight peaked in 2021, with a decline through 2024; likely tied to pandemic-related effects which caused surge in shipments due to lockdown and increased purchases.

•	Trucks led by value, vessels by volume; rail and vessel were more cost-effective than pipelines.

•	Low-Valued Trade (70XX) and Dallas/Ft. Worth were top ports, raising capacity concerns.

•	Canada trade was led by Special Provisions (Code 98), and Mexico by Medical Instruments (Code 90).


Recommendations:
•	Enhance port infrastructure and flow efficiency

•	Use predictive modeling for demand and disruption planning

•	Promote lower-cost, high-volume modes

•	Integrate pricing, weather, and real-time data for better insights
________________________________________

## 7. Limitations & Future Work
•	Data Gaps: Partial 2024 data and aggregated values reduce resolution

•	Missing Context: No integration of commodity pricing, weather data, or live tracking


Future Plans:
• Enrich data with external sources

•	Develop predictive models for freight trends and cost forecasting

• Incorporate sustainability metrics (emissions, fuel usage)
________________________________________

## 8. Project Files
•	Notebooks & Scripts: File Extraction and preparation

•	Presentation Slides: Key findings and recommendations

•	Power BI Report: Data processing, analysis, and visualization

(Link to Presentation Slides and Power BI Report: "https://drive.google.com/drive/folders/1jVEa-0RT2qCwcDQqV4kLd1Zi_ikjaQBm?usp=sharing")

•	Documentation: Project summary and methodology (Readme)





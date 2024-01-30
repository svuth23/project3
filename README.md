## Project 3
  
This project involves an in-depth analysis of flights coming out of Australia from the most popular airports. This tool can be used by travellers and the aviation industry to gain insights into various aspects that will be detailed below.

Data Source - .CSV file: https://www.kaggle.com/datasets/pandeyg0811/australian-flight-dataset-2003-2022

Presentation Deck : https://docs.google.com/presentation/d/1Q7hEIeMO3RyBboSzN1zpecjcRga_2AGq9CsqxfRdmHc/edit#slide=id.g2b225874ef8_4_20

### Ethical considerations:
The data used is available in an open platform with open-access. During the development of this code, assistance from an artificial intelligence platform such as Anaconda Assistance has been used. 
the original data used by Author of "australian-flight-dataset-2003-2022" falls under the specifications: 
- Sources:
The data is collected from https://www.data.gov.au/.
- Collection Methodology
The data was well researched for usability purposes with the least cleaning required for EDA, Insights Collections and Trend Analysis.
- License:
Database Contents License (DbCL) v1.0

### Part 1: Reading and Cleaning Data - Developer Sookie
Data has been pulled into SQLite database (database_path ="sqlite:///C:/Users/sooki/OneDrive/Desktop/Project_3/Flights_Data_Out.sqlite")
Selection of: Month - "March 2022"; In_Out: "Out" 

### Part 2: Visualisations
#### 1) Top Airlines Departing from Australia - Developer Patricia De Assis
![image](https://github.com/sookie22/Project_3/assets/143486132/96393f79-7f19-4356-a6da-794193a903b3)
#### 2) Popular Destinations by Total Flights - Developer Shenae Pepper
This static graphic provides an overview of the total number of flights from all airports for each "International_City". This could be used to infer the most popular destinations.
![image](https://github.com/sookie22/Project_3/assets/143486132/671ae71b-67b6-4090-9fb2-15f90ec08e24)
#### 3) Total Flights per Route per Airline - Developer Patricia
![image](https://github.com/sookie22/Project_3/assets/143486132/74ae85ad-16f8-4845-a16f-965eb8607b77)
#### 4) Airline Routes Distribution - Developer Shenae Pepper
This interactive sunburst chart provides a dynamic representation of airline routes, allowing users to visually explore and understand the distribution of total flights across different airlines and their respective routes. 
Hover over different segments of the sunburst to view specific information about airlines and their respective routes.
Zoom in by clicking on a particular segment to focus on a specific airline or route.
Understanding the Chart:
The color intensity represents the total number of flights for each segment.
Use the legend to identify different airlines.
Navigate through the hierarchy by clicking on the chart to explore individual routes within airlines.
![image](https://github.com/sookie22/Project_3/blob/main/Visualizations/Airline%20Routes.png?raw=true)
#### 5) Average Maximum Seat in Flights Across Australian Cities - Developer Shenae
![image](https://github.com/sookie22/Project_3/assets/143486132/9065cfa2-bfa9-419a-8b02-1ea2ca910670)
#### 6) Heatmap of busiest airports - Developer Sookie
![image](https://github.com/sookie22/Project_3/assets/143486132/c264857a-941b-4c0c-bd2e-e62a398661dd)
This Heatmap was created centered around Australia for better visualisation. Users can to zoom in for a detailed view and zoom out for an overall perspective. The color density on the Heatmap corresponds to the volume of flights departing from different Australian airports.
#### 7) Top routes filtered by Airways - Developer Sookie
![image](https://github.com/sookie22/Project_3/assets/143486132/177115f2-bfea-482a-acaf-5699ac9b4007)
This interactive bar chart will allow you to select the Airline and identify the top 5 routes based on total flights.  
#### 8) Top Airlines based on the amount of Flights - Developer Swapna
This interactive map allows you to select the Australian City that you would like to start the route, the international city of preferred destination and the preferred airline. As a result, it will provide you the total number of flights and provide you a visualisation of the route on the map with related bar chart.
![image](https://github.com/sookie22/Project_3/assets/143486132/2b90aa83-34a6-4e94-9f23-057a99170c91)



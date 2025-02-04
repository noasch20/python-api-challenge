### Weather Patterns and Latitude Analysis
## Overview
This repository contains an analysis of the relationship between certain weather patterns and latitude, with an evaluation of certain cities meeting vacation criteria.
The study utilizes CitiPy to generate a list of cities from randomly generated longitude and latitude which are then used for the analysis.

## Dataset
The data used for in this project was gathered using the open weather api for each city generated using CitiPy. Key variables for each city included in this data were:
- Latitude
- Longitude
- Max Temperature
- Humidity
- Cloudiness
- Wind Speed
- Country
- Date

## Analysis
The analysis of the project consists of:
## 1. Weather vs. Latitude
The 4 relationships studied in this portion include:
# Latitude and Max Temperature
![download](https://github.com/user-attachments/assets/d3102740-fec9-43af-b863-c23811ca87d5)
![download](https://github.com/user-attachments/assets/0b2f5fa5-18b2-4404-9024-888f06654465)
![download](https://github.com/user-attachments/assets/cab467d4-3ffe-4bb1-8c70-8d2a6c078f6a)

# Latitude and Humidity
![download](https://github.com/user-attachments/assets/6ce4a227-12f8-4879-a982-246f1db0e4f1)
![download](https://github.com/user-attachments/assets/0b10aa92-e0d7-4fab-8955-bea2487f27de)
![download](https://github.com/user-attachments/assets/d0a14cc9-1009-4245-8af6-abeb03688311)

# Latitude and Cloudiness
![download](https://github.com/user-attachments/assets/c33e63a9-0ff5-4cbe-abeb-425153ef2194)
![download](https://github.com/user-attachments/assets/3a38ae33-8b36-4019-9433-02b114793a17)
![download](https://github.com/user-attachments/assets/cc19a68d-7a8d-4cb0-b4b3-567d15a8a42d)

# Latitude and Wind Speed
![download](https://github.com/user-attachments/assets/3322c268-7f95-402e-9da4-a96fa257ad05)
![download](https://github.com/user-attachments/assets/8b2b3e07-921f-4b81-8332-d2007e52b855)
![download](https://github.com/user-attachments/assets/ad429bd2-75dc-4194-aaad-4dec5c01268e)

## 2. Vacation Selection
From the initial list of cities, cities were selected that:
- Max Temperature > 22C
- Latitude between -2 and 20
- Cloudiness < 20%
- Wind Speed < 3  m/s
An output map was created highlighting the selected cities, as well as adding in nearest hotel and country information as hover columns.

## Summary
When analyzing relationships between latitude and weather patterns, we can see the strongest correlation lies in the latitude vs. max temperature, specifically in the northern hemisphere. 
When looking at humidity, cloudiness, and wind speed, the most we see is weak correlation for both hemispheres.
The relationship is weakest for wind speed, with r-squared values for both hemispheres being very close zero.
The five cities selected in the vacation portion were:
- Coahuayana de Hidalgo, MX
- Kottapalli, IN
- Palasa, IN
- San Luis de la Loma, MX
- Beli, NG

## Tools and Libraries
- Pandas
- Numpy
- Matplotlib
- Requests
- Scipy.stats
- CitiPy
- GeoViews and hvPlot
- OpenWeatherAPI
- GeoApiFy API

  

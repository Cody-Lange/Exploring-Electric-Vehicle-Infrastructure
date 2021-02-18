# Exploring-Electric-Vehicle-Infrastructure

Electric vehicles have been emerging as a significant response to the current climate crisis, providing a novel way to reduce global greenhouse gas emissions. EVs will make up 10% of global passenger vehicle sales in 2025, 28% in 2030 and 58% in 2040. EVs will make up 31% of all cars on the road in 2040, 67% of municipal buses, 47% of two-wheeled vehicles and 24% of light commercial vehicles. Electric vehicles are gaining in popularity, but does the United States currently have the infrastructure for electric vehicles to be a practical alternative to traditional gas cars? This project explores the practicality of using electric cars by examining existing EV infrastructure, principally charging stations, the types of charging available, and EV adapters. The availability of EV charging stations, the degree to which adapters are interchangeable, the rates of charging, and the range of existing EVs are key determinants of whether or not existing infrastructure supports EV use in a practical manner.

Additionally, this project examines the growth of e-bike and e-scooter usage in urban transit. These smaller vehicles have also started to play an important role in helping cities transition to sustainable, emissions-free transportation. We will be looking at how these vehicles have grown in usage over the past few years and the overall growth of the micromobility market. We also want to observe real time data to visualize vehicle trips through various cities.

**Final Report:** Team 25 591_592 Final Report.pdf

**Charging Station EDA_v2.ipynb** provides the code for importing alternative fuel station data from the US Department of Energy website, cleaning and manipulating the data to give insight on what regions have the most charging stations, creating bar charts, and creating an interactive choropleth that shows the total number of charging stations and supported levels of charging in each US county.

**Interactive Choropleth of US Public, 24/7 EV Charging Stations by County is Viewable Here:** https://nbviewer.jupyter.org/github/Cody-Lange/Exploring-Electric-Vehicle-Infrastructure/blob/main/us_chargingstations_county.html

![Static Choropleth](https://github.com/Cody-Lange/Exploring-Electric-Vehicle-Infrastructure/blob/main/Charging_Station_Choropleth.PNG?raw=true)

**Austin and Louisville Scooter EDA.ipynb** uses Spark SQL to examine the growth of e-bike and e-scooter usage in urban transit. Creates heatmaps of scooter and bike usage by month and year. Also uses Kepler gl to visualize individual scooter trips in Louisville, KY during February 2019.

**Kepler.gl Dashboard of Louisville Scooter Trips is Viewable Here:** https://kepler.gl/demo?mapUrl=https://raw.githubusercontent.com/Cody-Lange/Exploring-Electric-Vehicle-Infrastructure/main/keplergljson.json

![Static Dashboard](https://github.com/Cody-Lange/Exploring-Electric-Vehicle-Infrastructure/blob/main/Louisville%20Dashboard.PNG?raw=true)

**EV_range.ipynb** creates interactive scatter plots of EV Range vs Annual Fuel Costs, Annual Fuel Costs vs. Model Year, EV Range vs. Model Year, and Level 2 Charging Time vs. Range

![Static Scatter Plots](https://github.com/Cody-Lange/Exploring-Electric-Vehicle-Infrastructure/blob/main/Scatter%20Plots.PNG?raw=true)

**Statement of Work:** Ryan Ball is credited for the items in EV_range.ipynb, Cody Lange is credited for Charging Station EDA_v2.ipynb, and Viraj Pande is credited for Austin and Louisville Scooter EDA.ipynb

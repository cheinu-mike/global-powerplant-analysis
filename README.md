__Download the jupyter file to see the graphs__
  
### Libraries required
- numpy
- pandas
- plotly

# Global powerplant data analysis
By Inwoo Choi, Gaurav Malik and Tomasz Wojcik 

# Proposal and Goals
## Introduction: 

In this day and age, many countries are looking into renewable energy sources and ways they can use energy more efficiently. An example would be the large scale investments that countries like China, Saudia Arabia, Germany, Denmark, etc. are doing to diversify their energy portfolio’s. Some of these investments include looking into renewable energy markets such as wind, solar, geothermal and tidal. 

These investments not only allow diversification into cleaner forms of energy that increase air quality, slow down environmental degradation and protect local wildlife but also increase the capacity factor. 

Our goal with this project is to explore the different kinds of energy sources each country utilizes and compare them against those of other countries. This analysis will lead to an accurate illustration of the percentage distribution of power generation and allow us to answer the guiding questions that we have come up with (mentioned in the next topic of this proposal).

## Describing the Data Set:

The data set that we will be analyzing and attempting to provide a direct visualization of is the Global Power Plant Database. This database is an open source database, licensed under the MIT License, that provides the public a comprehensive and holistic overview of power plants around the world. It is intended to make it easier for individuals to analyze, understand and share energy generation from varying plants from around the world.

There are over 30,000 power plants that are provided in this data set which span over 164 countries and include different types of power plants such as coal, gas, oil (which all can be considered a subset of the hydrocarbon energy power plants), hydro, wind and solar. The last three energy generation methods can be considered to be a subset of renewable energy.

Another advantage of this data set is that it provides information on the location of where these power plants are located. Specifically it mentions the longitude and latitude which will be helpful in locating the distance of these plants to major population centers like cities and towns. Along with the location, this data includes capacity (given in mW) and estimated generation (given in gWh). 

Finally by using this data we will be able to provide a clear picture of the types of energy generation methods that are being utilized around the world and will also allow to determine which countries focus on what type of energy generation techniques the most and allow us to compare countries against each other as previously mentioned. 

The MIT License permits us to use the data privately and commercially, as well as make modifications and distribute it. (MIT License)
## Guiding Questions:


1. What are the sources of energy from country to country? Specifically focusing on what the relative proportions are utilized (such as non-renewable and renewable)?
We need to look at absolute levels of energy use especially for non-renewables as that is what affects the environment the most. Relative or proportional use of non-renewables and renewables will show what the average person in each country is consuming and whether or not the country is making strides in implementing green energy.

1. Which countries are over/under utilizing their power plants? The capacity factor would give us an insight into whether the energy source is being used effectively. We can determine if certain countries are under or over utilizing their power plants. One issue that is brought up frequently is that wind and solar can potentially have lengthy downtimes as they are highly reliant on weather conditions. A subquestion may be whether the location will affect the overall capacity factor for green energy sources or is this taken into account in the design of the power plant? This information can be used to determine if the use of certain power sources is appropriate for a given geographical location.

1. Which countries are investing more in renewable and non-renewable resources? Comparison of GDP to the amount of total energy generation and GDP comparison to proportional use of green energy power plants. We suspect that wealthier nations have the money to invest in more green energy projects thus there must be consideration given to the economies of each country to see if the investment into certain power plants is appropriate for their respective economies. 


References to the data set are below. We may change these to the IEEE standard later.
# References

 1. Lukes. (n.d.). lukes/ISO-3166-Countries-with-Regional-Codes. Retrieved 25, 2019, from              https://github.com/lukes/ISO-3166-Countries-with-Regional-    Codes/blob/master/all/all.csv.  
 
 2. GDP per capita (current US$). (n.d.). Retrieved 25, 2019, from https://data.worldbank.org/indicator/NY.GDP.PCAP.CD.
 
 3. Wri. (2019, May 21). wri/global-power-plant-database. Retrieved 25, 2019, from https://github.com/wri/global-power-plant-database
 
 4. GDP (current US$). (n.d.). Retrieved 25, 2019, from https://data.worldbank.org/indicator/ny.gdp.mktp.cd.
 
 5. Data.worldbank.org. (2019). Population, total | Data. [online] Available at: https://data.worldbank.org/indicator/SP.POP.TOTL [Accessed 25 Sep. 2019].

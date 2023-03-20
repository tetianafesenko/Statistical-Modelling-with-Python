# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The goal of the project is to access the data using API, get comfortable when using API like Foursquare and Yelp and work with the given data. Also, when data is received, clean and transform it using Python. 

## Process
### Access data using API for citybikes and chose any city for analysis. For my project I chose Antwerpen city in Belgium. Europe is known for its amazing infrastructure when it comes to the bike lines and network, so it was an interesting way of exporing for me. 

### When data became available, I use Python to call out the required information like: 
a) Name of the stations
b) Latitude and longtitude of the bike stations 
c) Number of bikes available at any given bike station location

This was interesting to see as we know that this number can change anytime.

Once the data was available to me, I've added it into the Pandas dataframe using Python.

### Step #3. Connecting to Foursquare and Yelp APIs
This part of the project required connecting the existing data about the network of bike stations of Antwerpen city in Belgium and connecting it to the places nearby. 
a) Finding the places 1000m around the chosen bike station. Places like bars, restaurants and etc. For my project I chose to find all the nearby coffee restaurants and coffee spots because I love coffee. Also, I wanted to specify for the POI to be open. 

###4 1. Put in some ideas on how the data can be joined togehter, which parametrs/columns to use
2. Created dataframes for FOURSQUARE and CITY BIKES and inner joined them uing long/lat
3. Connecting the newly created database and uploading into PostgreSQL

## Results
As an example, I chose one of the bike stations in  Antwerpen, main station and its address Koningin Astridplein 27, 2018 Antwerpen, Belgium. Using API Fourthsquare I called a list of places nearby that have a name coffee in them or somehow associated with the "coffee". As a results, I found 10 places that satisfies my parameters.

## Challenges 
 A lot of trips with distance 0
 - People use bikes for recreation purposes
- There is a huge number of riders who ride for less than half an hour per trip and most less than 1 hour.

Also, there are more smaller trips on the weekend, which keeps more people in the area to buy some coffee.  Having colder weather is also a factor. Less people drive bikes but more people stay inside. 

The more distance from the nearest restauran, the less available bikes we see and the less available bike stations. The population decreses, so there is no need to have many stations. 

## Future Goals
When I went to the website with the analytics about the Antwerp city, it shows that the city is very touristic with a lot of places depending on tourists. That made me think, that taking shorter trips, visiting places nearby stations is common since tourists who come into the city do not own any cars and would prefer taking bikes over driving. 
CHALLANGES
The data is not enough to make a compehensive analysis to determine , next time I might select English speaking country or a city. Something to consider for the future.

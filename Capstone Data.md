# Recommendation of London Boroughs

## Data

In order to make recommendations on London boroughs based on user preferences, the following data are needed:  

1. Information about rent prices in all Greater London boroughs for various types of accommodation
2. Information about the venues and their types within each borough
3. User preferences for:  
    * rent (min, max)
    * type of acommodation (Studio, One Bedroom, etc.)
    * most important venues in the area (Shopping, Entertainment, Green spaces, etc)

For points 1 and 2 in the above list, an external data is needed, while all items in point 3 are entered by the user. The rent data up to the 31st of March, 2019 is available from the [UK Government's data portal](https://data.london.gov.uk/dataset/average-private-rents-borough). The venue information can be retrieved using [Foursquare API](https://developer.foursquare.com/). As this problem deals with boroughs, it will be useful to have a GeoJSON file with the limits of Greater London boroughs that is conveniently available (here)[https://joshuaboyd1.carto.com/tables/london_boroughs_proper/public].

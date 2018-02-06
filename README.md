I was curious which neighborhoods in Chicago have the oldest buildings. The map created in this notebook shows the average building age of each neighborhood in the city.

### Data Used
 - [Chicago Neighborhood Boundaries (2012)](https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Boundaries-Neighborhoods/9wp7-iasj)
 - Parcel data that I (somewhat creatively) scraped from [Cook County's Map Application](https://maps.cookcountyil.gov/cookviewer/mapViewer.html)

### Caveats
I don't know how accurate the parcel data from Cook County is, although generally this map looks consistent with that I was expecting. Parcels with an age of 0 were removed from the data, since it occurs pretty frequently and is likely a null value indicator


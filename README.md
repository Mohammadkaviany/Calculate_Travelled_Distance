# Calculate_Travelled_Distance

In this code we have a datasheet with 4 columns named " RouteId", "Latitude", "Longitude" and " LogDate".
We loaded the data py Pandas and sort over RouteId & LogDate.
A function has defined as name as Dist(DF, List) in order to calculate the distance between the geographical coordinates which are appended to our dataset by GPS.
The calculated value in Dist function is dist and it is multiplied by 111.139 to convert its unit into kilometer.
In last and main part of programe we have loop over every uniqued value of RouteId.Then we filter our dataset over the loaded value of RouteId which we call 'i' .
So we have all reported valued of "Latitude" and "Longitude" of corresponding RouteId.
In order to calculate distance , we send our data set to the Dist function as "DF" parameter and iterate over the DF coordinates.
Finally, we append all calculated distance for every RouteId to a data set named "result". In result we have "RouteId" and "TotalDistance" for that "RouteId"

After all these , we report result as the program result.

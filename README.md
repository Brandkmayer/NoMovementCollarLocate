# NoMovementCollarLocate

The no Movement script provides an estimated day that collars dropped off of an animal by totaling the number of GPS points found within the average gps error range. By summing the number of gps points we can identify episodes were movement doesnt occur. This can include resting periods but also allows us to identify when collars have dropped since the all points following a drop should reside within the error range. 

After smoothing the data, the gps point with a lag total closest to the total counted.

## Identifying collars 
Collars should be organized and stored in their own "virtual herd". This allows herd with active collars to be updated and managed more readily but also to store and consolidate missing or dead batteries. Locating dropped collars can be identified through the notification tabs or through the grazing by observing the single collar history associated with a suspected collar. 

![[Images/Herd Organization.png]]

Once properly stored, collars list can be organized base on the "last location time" under the advanced tab within the Herds to display tab. Active collars should be processed separately from long term missing collars. Recently dropped collars can be filtered by unclicking the More than a day box.  

![[Images/Last Location.png]]

"Select collars on map" tab under advanced allows the user to select the desired collars on the map and the "Export selected collars" creates a csv of the selected collars. This is stored in the "CollarsList" folder. 

![[Images/Advanced tab.png]]

Using the Vence-API will allow you to select a few months to pull data which will be stored in the Vence-API_Data folder. 

These are the only components necessary to get a shapefile of the desired collars. 
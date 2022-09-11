# Mapping_Earthquakes

A multi-layered map showing reported earthquakes within the last seven days.

## Purpose of Repository

This repository has nine branches an multiple .json files not used in the final project located in the Earthquake_Challenge folder in order to display the various ways maps can be used to track data and allow others to learn how to build not only a simple map (as seen in the Simple_Map branch) but various options for layering depending on the type of data wished to be displayed.

For example, mapping polygons is a helpful starting point to use if one wants to display the tectonic plates on the map, but can also be used to map the effected radius of an earthquake if data is found on the devestation after effects.  This could also be used in a similar study on volcanos and lava radius or ashfall over the last decade.

It could be used in combination with the branches covering lines and linestrings again in the case of volcanic activity in corrolation with flight routes and rerouting requirements for avoiding dangerous ashfall and volcanic activity such as had been seen in the 2010 Eyjafjallajökull eruption.

## Produced Map

The map produced allows for the user to choose various settings according to their own visual needs.  The map defaults to 
a street view world map with all earthquakes and tectonic plates overlayed, as well as a legend indicator for the earthquake colors on the bottom right-hand side.

![default page settings](https://user-images.githubusercontent.com/107294123/189512699-707059bc-2250-4549-abc5-70562ab86565.png)


However, the toggle feature on the top right corner also offers a satellite image, as well as dark and light maps for those who find the standard backgrounds too distracting and need a simple backdrop to see the data better.  

![Major Earthquakes](https://user-images.githubusercontent.com/107294123/189512707-8e09c3e4-88eb-4beb-abdc-d112426fb4e0.png)


The overlays are set up in such a way that they can be selected individually, overlayed on top of eachother, or completely removed from view to offer users the most controlled experience.

![toggle settings](https://user-images.githubusercontent.com/107294123/189512717-381874aa-5f4d-4861-a7fe-96096d1bba65.png)


## Conclusion

The map is a great way to quickly see a large amount of earthquake data.  Though the date and time of the quakes are not listed, the code could be edited to include this information.  A link to more information on the USGS site could also be added in if users wanted more details on specific earthquakes.  Because there is such a huge wealth of information available in the geojson file, anyone wanting to modify or add code to the logic.js file has a number of options available to gear the map towards the user requirements quite easily.

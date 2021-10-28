# World_Weather_Analysis

## Overview

The project was developed for the company My Trip, a top travel technlogy company that specializes in hotel and lodging services. The objective is to collect and present information about the ideal hotels for customers using simple criteria such as the preferred type of climate.

The Jupiter notebook and the citypy module were used to obtain the closest cities from 2000 random coordinates. Weather data is obtained from each cities through API calls on the Open Weather Maps page.

Then, using the Google Places API, the name of the first hotel result for each city is obtained, filtering by the minimum and maximum temperature we obtain the name of the city, the weather and the name of the hotel in the information boxes that fits with the criteria.

Finally, by choosing 4 cities from our filter we can create maps with a travel route for the selected cities.

## Search Result View
![](https://github.com/Jponce25/Election_Analysis/blob/1abab17e1a8a015fe71b7d77a430fa9cda1658b6/Resources/Imagen3.png)

## Itinary Result View
![](https://github.com/Jponce25/Election_Analysis/blob/1abab17e1a8a015fe71b7d77a430fa9cda1658b6/Resources/Imagen3.png)
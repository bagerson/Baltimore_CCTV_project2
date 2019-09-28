# Baltimore CCTV Project 2

Website and graph visualizations: https://github.com/MrScottGregory/project2_group7/tree/master/presentation_website

Heatmap visualizations: https://github.com/tduszyk/Baltimore_CCTV/tree/BenG

Working branch repository: https://github.com/tduszyk/Baltimore_CCTV/tree/master

## Team 007 <br/>
## JS Project

### Contributors
Geuntae Jang</br>
Scott Gregory</br>
Ben Gerson</br>
Tom Duszyk<br/>

### Data sources

Baltimore CCTV locations. from data.world : <br/>
https://www.kaggle.com/sohier/crime-in-baltimore <br/>

Baltimore Closed circuit camera locations: <br/>
https://data.baltimorecity.gov/Public-Safety/CCTV-Locations/h32e-c3r6 <br/>

Baltimore Victim Crime locations: <br/>
https://data.baltimorecity.gov/api/views/wsfq-mvij/rows.json </br>

Baltimore Police Department Arrests: <br/>
https://data.baltimorecity.gov/resource/3i3v-ibrt.json </br>


### Summary

The goal of this project was to explore the location data of crimes reported to the Baltimore Police Department as well as the proliferation of CCTV cameras.  Assuming a causative theory, CCTV Cameras should reduce crime nearby, or high crime areas should increase the proliferation of CCTV cameras.  Using a heatmap we expected to find "cool" areas surrounding CCTV cameras.

Data was collected from the Baltimore open data system.  Crime data was cleaned and sorted by type of crime "homicide", "shootings", "property crime" and "larceny" and mapped using a leaflet heatmap plugin.  

![Baltimore Shootings:](https://github.com/bagerson/Baltimore_CCTV_project2/blob/master/Screen%20Shot%202019-09-28%20at%2010.19.23%20AM.png "Baltimore Shootings Heatmap")

![Baltimore Homicides](https://github.com/bagerson/Baltimore_CCTV_project2/blob/master/Screen%20Shot%202019-09-28%20at%2010.19.41%20AM.png "Baltimore Homicides Heatmap")

In the cases of violent crimes, such as shootings and homicides, it became immediatedly clear that camera placement had little to do with violent crime.   Homicides occurred on the same stretchs of commercial streets with CCTV cameras, or nearby.  

![Baltimore Larceny](https://github.com/bagerson/Baltimore_CCTV_project2/blob/master/Screen%20Shot%202019-09-28%20at%2010.20.18%20AM.png "Baltimore Larceny Heatmap")


Petty crimes such as larceny were widespread and bore little to no relationship with CCTV cameras.

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")


The presentation website also explores the relationship between race, income and crime.  Census data seems to indicate that crime is related to locations where there is a larger non-white population and lower household income.

## Technical Limitations
While the individual components were successfully coded, integrating the heatmap into the presentation website proved difficult.  In addition, the use of javascript "promises" to generate the heatmap confounded the ability to make a multilayered map despite many hours of coding.


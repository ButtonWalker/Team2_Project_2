[![INSERT YOUR GRAPHIC HERE](https://github.com/ButtonWalker/Team2_Project2/blob/master/resources/Images/geoSpatialVis.png)](Images/geoSpatialVis.png?raw=true)

<!-- TABLE OF CONTENTS -->
## Table of Contents

- [Team 2 Project 2](#Team-2-Project-2)
- [Introduction](#Introduction)
- [Purpose of the Analysis](#Purpose-of-the-Analysis)
- [Project Requirements](#Project-Requirements)    
- [Results](#Results)
- [Over All Map](#Over-All-Map)
- [City and Hospital Data](#City-and-Hospital-Data)
- [Coding Style](#Coding-Style)
- [API Calls](#API-Calls)
- [Observation](#Observation)
- [Coding Documentation](#Coding-Documentation)
- [Challenges and Limitation](#Challenges-And-Limitation)
- [Authors](#Authors)
- [Git Version Workflow](#Git-Version-Workflow)
- [Acknowledgments](#Acknowledgments)

# Team 2 Project 2

### Introduction
While the decision to relocate and concur a new city is exciting, it can also be a daunting prospect with so many factors to consider when determining where to live.  The timing of this project is spot on as one of our team members is in the process of finding a new city to relocate and call home. As a team we decided to offer our help by developing a location-based analytics app that will help alleviate the burden by allowing the user to eliminate the guesswork and make data driven decisions based on customizable criteria that visualized the results in an interactive dashboard.

In parallel, we will be telling a tale of three very different cities.  Our goal is to provide meaningful insights and highlight the underlying data which contributes to what is expected to be a stark contrast between the selected cities of San Francisco, Dallas, and Jackson. 

### Purpose of the Analysis
The objective of Project 2 is to use the selected data for the three selected cities (Dallas, Jackson and San Francisco) to tell a story through data visualizations of the users’ interaction exploring the data themselves. Our purpose is to allow the user to select a city of interest (move to city) and choose from a list of given criteria that will return the results in a graphical visualization of the comparative underlying data. Through this interactive experience the user will be able to make a decision on the best city to relocate based on their chosen criteria. 
 
### Project Requirements
1. Visualization had to include:

a.	Python Flask – powered restful API
b.	HTML/CSS
c.	JavaScript
d.	At least one database (SQL, Mongo DB, SQLite, etc)

2.	Tracks
a.	Use of a custom D3.js (nonstandard graph or chart)
b.	Combination of web scraping and Leaflet or Plotly
c.	Dashboard of multiple charts that update from the same data
d.	Thick server that performs multiple manipulations of data in a database prior to visualization

3.	Include at least one JS Library that was not covered in class
4.	Data set with at least 100 records
5.	Include some level of user driven interactions
6.	Final visualization of at least three views


The following data sets were used throughout the project.



### Observations
Based on the crime comparison analysis of the three cities, it was noted that Dallas has the highest crime rate and Jackson with the lowest.

San Francisco has the  highest average home price

Cost of owning a house appears to be consistent across all three cities

The number of people who have achieve a Bachelor’s Degree was approximately 3.5 times higher for San Francisco as compare to Jackson and approximately 2 times more than Dallas.

The cost of healthcare is fairly similar between cities ranging from a high of $139 for San Francisco to a low of $78.5 for Jackson


### Over All Map

[![INSERT YOUR GRAPHIC HERE](https://github.com/ButtonWalker/Team2_Project_2/blob/master/Images/siteImage1.png)](Images/siteImage1.png?raw=true)

### City and Hospital Data

[![INSERT YOUR GRAPHIC HERE](https://github.com/ButtonWalker/Team2_Project_2/blob/master/Images/siteImage2.png)](Images/siteImage2.png?raw=true)

[![INSERT YOUR GRAPHIC HERE](https://github.com/ButtonWalker/Team2_Project_2/blob/master/Images/siteImage3.png)](Images/siteImage3.png?raw=true)


### Coding Style

The following sources and tools were used: 
	Attom Data Solutions and CityData websites were used to obtain the source data 
	Pandas Library for manipulation and analysis of the source data; 
	Jupyter Notebook and Visual Studio Code (IDE) to write the codes 
	JavaScript was the primary language
	SQLAlchemy an object relational mapping tool used to map the data to SQLlite database for storing the datato run where queries. 
	Leaflet Js was use for markers and custom masters
	Ajax to convert multiple datasets in real time
	Github a web-based hosting service used as the repository

List of dependencies:
```sh
   pip install gunicorn
   pip install psycopg2
   pip install flask
   pip install flask-sqlalchemy
   pip install pandas
```
### API Calls

[ATTOM Data Point](https://api.gateway.attomdata.com/propertyapi/v1.0.0/property/detail?id=1234)

### Data Extraction

### Coding Documentation
[Mapbox](https://www.mapbox.com/)

[Attom](https://api.developer.attomdata.com/home)

### Challenges and Limitations
The following are limitations encountered:

From Project Visualization
   Time and experience with the data and creating the visualization
   The source datasets obtained and used were limited to three cities. 
   Inconsistencies in the data type, style and format as a result of the different sources from which the data was obtained.   
   Working with two or more Json files with different formats. 
   Rendering to Heroku was an issue so Github was used as the host
   Getting the two custom icons to rendered on the same map overlay using two independent dataset

From General Visualization
  While data visualizations can be generated in real-time, they do not provide any explanations. 
  Different users confronted with the same data visualization may not necessarily draw the same conclusion but interpret it differently,   depending on their previous experiences and particular level of expertise.  
  Graphics are great for conveying simple ideas quickly; however, at times they might not be enough and are not able to express a         complex situation. Sometimes the visualization doesn’t tell the full or underlying stories and as such, language is required to make     sure the end user really understands.
 	

## Authors

Ka-Ri Walker - Initial work - [SMU DataTeam 2](https://github.com/ButtonWalker)

Hao Bai - Inital Work - [SMU DataTeam 2](https://github.com/haobaids)

Jonas Haskins - Inital Work - [SMU DataTeam 2](https://github.com/jhhaskins)

Escoffrey Thomas - Inital Work - [SMU DataTeam 2](https://github.com/Escoffrey)

## Git Version Workflow

[![GIT Workflow](https://github.com/ButtonWalker/Team3_Project1/blob/master/GitWorkFlow.png)]()
```sh
Name Features (featureKW01)
Name Bugs (BugKW01) feature number and bug number to match
```
## Acknowledgments
Giving credit to those who helped

Special thanks go out to KaRi for going over and beyond to bring this project to completion.  KaRi was the heavy hitter and without his dedication, determination, drive and coding skills this would not have been possible.  Thanks go out to Hao for whom this project is dedicated as she leaves us to relocate to San Francisco.  Hao was the master behind the extraction, transforming and loading of the data.  Jason lent his expertise to the front end side and provides the images to go along.  

Thanks to the Graham, Alexander and Guy for all the help in getting the codes to work and for your valuable inputs.

THANKS TEAM!!


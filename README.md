#  UFO Analysis

##  Overview of the analysis
The UFO sightings project was created to show ufo sighting information and to display that information in a table on a website.
The data for the sightings was provided in the data.js file.  The app.js file, index.html, and style.css were created and then placed
into a repo for the proper folder structure.   This aloud for the needed files and folders of the structure to be used by the 
wedsite.   The analysis of the project came form the app.js file which held the javascript for the table displayed on the website.
The challnge of this project was to create further javascript functionality with used filters for the sightings table.

##  Results

The initial website only had date as the filter for searching the sightings.  The field preview date formate was displayed which prompted
the date then click search.  This function was coded in the index.html page inside a div container using Bootstrap as a css style.  The challenge 
portion of this project was to creat four additional filters.  These were city, state, country, and shape.  All of theses filter displays were placed inside 
of list item tags.   The functions for these fields were created in the app.js file using javascript.


### Index.html
![](https://github.com/crashdean/UFOs/blob/main/static/images/Fiter_fields.png)


This javascript was used to create the table for the data.js to be displayed.   The data rows were first appended the the table rows and then the 
object values were appended to the row cells.  This created the table of data to display on the website.

### Create Table
![](https://github.com/crashdean/UFOs/blob/main/static/images/Table_create.png)


The fields were used to filter the existing data and display with the data entered by the user.   Javascript functions were created to compare the
entered data to the data in the table.   If the data was the same, it was used to filter that field.   If the data entered was not the same as the
data in the table, then the field was not used as a data filter.

### Update Filters
![](https://github.com/crashdean/UFOs/blob/main/static/images/Filter_update.png)


The entered field filter data was then used to search the data table and the response was the website would update the user with the data selected.
This made it possible to scan the data for the sightings that were more relevent to the user.

### Filter Table Data
![](https://github.com/crashdean/UFOs/blob/main/static/images/filter_table.png)  
  
  

##  Summary

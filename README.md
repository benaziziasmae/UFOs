# UFOs

Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape.

## Overview of the project 

This project focuses on building a dynamic webpage that accepts user inputs and adjusts accordingly to display information about UFO sightings.
In order to perform their analysis, users will be able to filter the UFO sightings table based on multiple criteria such as the event date, city, state, country and shape.

## Resources

- Data Source: [UFO Data](/static/JavaScript/data.js)
- Software : HTML/CSS, JavaScript, Visual studio Code, BootStrap, d3-js.


### Link to UFO Sightings webpage : 

## Deliverable 1

This is the initial page. The user can re-initialize the page by clicking on the navbar at the top.

![filter_screen](/static/images/filter_screen.PNG)

1- Filtering by event date

The user enters the desired date, the change is detected and the table is updated accordingly.

![filter_bydate](/static/images/filter_bydate.PNG)

2- Filtering by city

The user enters the desired city, the change is detected and the table is updated accordingly.

![filter_bycity](/static/images/filter_bycity.PNG)

3- Filtering by country

The user enters the desired country, the change is detected and the table is updated accordingly.

![filter_bycountry](/static/images/filter_bycountry.PNG)


4- Filtering by state and shape

The user enters the desired state and shape observed, the changes are detected and the table is updated accordingly.

![filter_byshape](/static/images/filter_byshape.PNG)


5- Filter using all the filter at the same time 

All filter parameters can be entered simultaneously.


![filter_byall](/static/images/filter_byall.PNG)

## Summary 

- One drawback of this design is the difficulty for the user to know what parameter to use for the filtering. For example to pick a city, the user would have to go through the table a find the city desired for the analysis.
- A way to address this would be to present drop-down lists including all filter values in place of the input fields.
Each list would need to update after a parameter is selected in any filter.


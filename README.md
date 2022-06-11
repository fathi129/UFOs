# UFOs
An UFO Sightings web page is built using JavaScript, which dynamically loads the data based on user input.

## Overview of the Analysis
JavaScript is typically a front-end development language, bringing extra functionality and customizations to enhance the user experience. It also has several uses specific to data visualization, such as dashboards. It has released several versions, but the most popular one is ES6.In this module, we will be using the ES6 version of JavaScript.This analysis aims to build a dynamic webpage.<br>
Dynamic webpages are pages that will accept user inputs and visually adjust, to reflect that interaction. It is created by inserting Javascript into an HTML Page. We will be using Basic HTML, Bootstrap, and CSS to build and style the entire page. We will also include an attention-grabbing header, article, and summary on the page. Our result will be a visually appealing and interactive presentation of data. The Dynamic webpage is built by building a table to hold and neatly display the data we want to work with. Then we will add filters to that table, letting users refine their search on more than one level.

## Purpose of the Analysis
This analysis aims to help Dana write about her hometown McMinnville, Oregon. It is famous for its UFO sightings and has an annual gathering of UFO enthusiasts. Using the JavaScript file, we have to filter the UFO sightings based on the countries, cities, states, and type of the sightings.<br> 
We can manipulate the data by adding filters. We need to apply the filters, and based upon it; the data is displayed. We will create the filters to make this table fully dynamic, meaning it will react to the user input. The table is placed on an HTML page for easy viewing. The customization is done using Bootstrap.<br>
<img src = "https://github.com/fathi129/UFOs/blob/master/Screenshot%20UFO's/ufo_img.jpg" width = 700><br>
 

## Resources Used
*DataSources*: [data.js](https://github.com/fathi129/UFOs/blob/master/Static/js/data.js)<br>
*Software used*: HTML, CSS, Bootstrap 3.3.7,D3.js Library<br>
*Language*: JavaScript <br>


## Results
The Javascript is beneficial for DOM manipulations and Event handling. Using the D3 Library, We can listen to the events on the HTML page and write javascript according to that. Some of the events are Change, On Click, etc. The change event occurs whenever the user enters anything in the input field; on click takes place when the user presses the button. We can write code for the HTML element; If any reaction occurs in that component, we can perform specific action using javascript.<br>
The webpage and dynamic table are built as intended, the table is created by referring to the table body and row, and each table data is retrieved and placed on the page. But we would like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria simultaneously. In addition to the date, we will add table filters for the city, state, country, and shape. For location-based data, a user can opt to view the results located in certain countries or cities. Our table will be inserted into and visually displayed by an HTML page. The initial web page looks like this header and article.<br>

 <img src = "https://github.com/fathi129/UFOs/blob/master/Screenshot%20UFO's/ufo.png" width = 900><br>
 
The table is built using the data stored in a javascript array, and the table is inserted into the HTML, filters are added, and the final HTML page looks like this.<br>

 <img src = "https://github.com/fathi129/UFOs/blob/master/Screenshot%20UFO's/initialstate.png" width = 900><br>
 
 ## Deliverable 1: Filter UFO sightings on multiple criteria
 
 To filter the UFO sightings on multiple criteria, We have created a filter object which keeps track of the filter element ID and element value. First, we need to create a variable called ChangedElement, which keeps track of changes in the filter. If any value is changed in the input field of the HTML page, those values are entered into the filter object. The table is filtered based on the filter id and value; the new table is built with the filtered data. So in this way, the dynamic table is created by listening to the changes made in the input fields.By entering the city's name as el cajon and shape as light, we can retrieve the matching data from the table.<br>
 
  <img src = "https://github.com/fathi129/UFOs/blob/master/Screenshot%20UFO's/search.png" width = 900><br>
 When we enter all the fields like a date as 1/1/2010, city as el cajon, state as ca, country as us, and shape as a triangle, the filtered table looks like below.<br>
  
  <img src = "https://github.com/fathi129/UFOs/blob/master/Screenshot%20UFO's/Final%20img.png" width = 900><br>
  
  ## Summary
  We have successfully built a dynamic web page. But the drawback of this web page are
  - The user has to specify the inputs as lower case, which is in the given data. They are case-sensitive and will not fetch the data from the table if the information does not match the table.<br>
  
  <img src = "https://github.com/fathi129/UFOs/blob/master/Screenshot%20UFO's/casesensitive.png" width = 900><br>
  
  - We have to specify the date as a date, month, and year format; we cannot retrieve the data by just selecting the month and year.<br>
  
  <img src = "https://github.com/fathi129/UFOs/blob/master/Screenshot%20UFO's/month.png" width = 900><br>
  
  - There is no proper instruction given to the user that we must press enter after entering a value in the text field to see the result.<br>
  
  ### Some of the recommendations given to this web page are
  - We can add the button as an event handler that handles the changes made by the user instead of listening to all the input field changes.
  - We can make the Countries, Cities, and Shapes filters as a drop-down box so that the user can select the value instead of entering it.
  - Making the input text case insensitive and adding a trim function to remove the blank spaces while searching for the data inside the filter field will make user friendly.
  - We can make the date option to choose by specifying the range of dates instead of manually typing the date, allowing the user to select the date more easily.
  - We can make the web page live by inserting the new updated table, latest news, and articles.

 
 







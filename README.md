# UFOs
An UFO Sightings web page is built using Javascript,which dynamically loads the data based upon the user input.

## Overview of the Analysis
JavaScript is typically known as front end development language,it brings extra functionality and customizations to enhance the user experience.It has also several uses specific to data visualization such as dashboards.It has released several versions but most popular one is ES6.In this module we will be using ES6 version of Java Script.The aim of this analysis is to build dynamic webpage.Dynamic webpages are pages that will accept user inputs and visually adjust, to refect that interaction.It is built by inserting Javascript in to an HTML Page. We will be using Basic HTML,Bootstrap and CSS to build and style the entire page.We will also include an attention grabbing header,article and summary.Our end result will be a presentation of data that is both visually appealing and interactive.
The Dynamic webpage is built,by building a table to hold and neatly display the data we want to work with.Then we will add filters of that table,which let's users to refine their search on more than one level.

## Purpose of the Analysis
The aim of this analysis,is to help Dana to write about her hometown McMinnville,Oregon.It is famous for its UFO sightings and even has an annual gathering of UFO enthusiasts.Using Java Script file,we have to filter the UFO sightings based on the countries,cities,state and type of the sightings.We can manipulate the data by adding the filters.We need to apply the filters and based upon on it the data is displayed.We will create the filters to make the this table fully dynamic,meaning it will react to the user input.The table is placed in to an HTML page for easy viewing.The customization is done using Bootstrap.<br>
<img src = "https://github.com/fathi129/UFOs/blob/master/Screenshot%20UFO's/ufo_img.jpg" width = 700><br>
 

## Resources Used
*DataSources*: data.js <br>
*Software used*: HTML, CSS, Bootstrap 3.3.7,D3 Library<br>
*Language*: JavaScript <br>


## Results
The Javascript is very useful for DOM manipulations and Event handling.By using D3 Library,We can listen to the events taking place in the html page and write javascript according to that.Some of the events are Change,On Click etc.The change event takes place when ever the user enter anything in the input field,On click takes place when the user presses the button.We can write code for the HTML element,If any reaction takes place in that component we can perform certain action using javascript.
The webpage and dynamic table are built as intended,the table is built by refering the table body,table ro,,each table data is retrieved and placed in the page. But we would like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, we will add table filters for the city, state, country, and shape.For location based data,a user can opt to view the results located in certain countries or cities.Our table will be inserted in to,and visually displayed by an HTML page.
The initial web page looks like this we header and article.<br>

 <img src = "https://github.com/fathi129/UFOs/blob/master/Screenshot%20UFO's/ufo.png" width = 900><br>
 
The table is built using the data stored in a javascript array,and the table is inserted in to HTML and filters are also added and the final HTML page looks like this.<br>

 <img src = "https://github.com/fathi129/UFOs/blob/master/Screenshot%20UFO's/initialstate.png" width = 900><br>
 
 # Deliverable 1: Filter UFO sightings on multiple criteria
 
 To filter the UFO sightings on multiple criteria,We have created filters object which keeps track of the filter element ID and element value.First we need to create a variable called ChangedElement which keeps track of any changes in the filter.If any value is changed in the input field of the HTML page,those values are entered in to the filter object.The table is filtered based on the filter id and value,the new table is built with the filtered data.
 So in this way,the dynamic table is built by listening to the changes made in the input fields.
 We can see by entering the name of city as el cajon and shape as light we can retrieve the matching data from the table.<br>
 
  <img src = "https://github.com/fathi129/UFOs/blob/master/Screenshot%20UFO's/search.png" width = 900><br>
  When we enter all the fields like date as 1/1/2010 ,city as el cajon,state as ca,country as us,shape as triangle,the filtered table looks like below<br>
  
  <img src = "https://github.com/fathi129/UFOs/blob/master/Screenshot%20UFO's/Final%20img.png" width = 900><br>
  
  ## Summary
  We have successfully built a dynamic web page.But the drawback of this web page are
  - the user has to specify the inputs as lower case,as such it is in the given data.They are case sensitive and it will not fetch the data from the table,if the input does not match with  the table<br>
  
  <img src = "https://github.com/fathi129/UFOs/blob/master/Screenshot%20UFO's/casesensitive.png" width = 900><br>
  
  - We have to specify date as date,month,year format,we cannot retrieve the data by just specifying the month and year.<br>
  
  <img src = "https://github.com/fathi129/UFOs/blob/master/Screenshot%20UFO's/month.png" width = 900><br>
  
  - There is no proper instruction given to the user that we have to press enter after entering a value in the text field to see the result.<br>
  
  ### Some of the recommendations given to this web page are
  - We can add the button to listen to the changes made by the user,instead of listening all the input field.
  - We can make the Countries,Cities and Shapes as drop down box,so that the user can select the value instead of entering it.
  - Making the input text case insensitive and adding trim function to remove the blank spaces while searching for the data inside the filter field.
  - We can make the date option to choose, by speciying the range of dates,instead of specifying the date manually,which allows the user to choose the date more easily.
  - We can make web page more live,by inserting the new updated table,latest news and articles.

 
 







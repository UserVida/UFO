# Overview of the UFO Project

## Purpose

The purpose of this project was to create a web page that would allow users to analyze and filter information on UFO sightings based on multiple search criteria. These criteria are date, city, state, country, and shape. The data on the UFO sightings was stored in a JavaScript file, labeled as data.js. The table and filter function were created through JavaScript code and stored in the JavaScript file app.js. The JavaScript files were accessed through an HTML file that presented the information through an HTML page.   

## Project Results

The process on how to use the search criteria on the web page is straightforward and simple. The default web page has the table loaded with all the available data and the filter boxes empty. 

<img width="938" alt="origUFOtable" src="https://user-images.githubusercontent.com/97644424/169741417-931722b1-cabf-436c-9263-235d8a037e07.PNG">

When an input is put in the appropriate search box, the data in the table is filtered to only show the rows with search input. 
The code used to run this function uses a for loop on each row of the data to match the value to the row. If the row does not contain the value entered in the search, the row is removed from the table. The filter function is triggered once an input is entered into the search box and either the enter key is pressed or the user clicks outside the box. 


<img width="938" alt="filteredUFOtable" src="https://user-images.githubusercontent.com/97644424/169741432-802e89de-83ce-46e5-bb35-bbd8118abf7a.PNG"> <img width="364" alt="filteredDataCode" src="https://user-images.githubusercontent.com/97644424/169741444-f3a581b0-107d-4296-bea9-32a73d7c9888.PNG">

If a search input is entered that is not found in the data or if a search input is entered in the wrong search box, the table returns empty. 

<img width="936" alt="emptyUFOTable" src="https://user-images.githubusercontent.com/97644424/169741449-958fbded-c2b6-4307-aad5-6cfc828a9865.PNG">

Once the criteria are removed and the user presses enter or clicks outside the search box, the default table is returned. 


## Project Summary 

### Drawback

The new web page design allowed for more in-depth analysis of UFO sightings through increasing the number of search criteria. One drawback of this design, however, is that if unavailable input is put in the search, instead of a message informing the user that no data matches the input, the table is simply returned empty. 

Since the original table with all the data is so long, users will not be able to see which specific criteria values have sighting data unless they attempt to search and filter it. 

### Recommendations

Two recommendations I have for further development of this web page are:

1. Include a drop-down list for the search function that filters out the search options as characters are entered.

A drop-down list that activates when you click into the search box gives the user a quick view into what data is available in the table. For example, if a user clicks into the state search box, the drop-down list will list all the states included in the table. This makes it easy for the user to determine which states has available data and which don't.

Additionally, is a user wanted to search up a certain city but the drop-down list was too long, they would start typing into the search box and the results in the drop-down menu would only return cities that match the characters being entered. 

2. Adding a total number of search results for the user to see. 

Adding a total's line (ex. Showing (n) results) right above the data table or right above the search section, users can conduct a more thorough analysis on UFO sightings. Some search inputs return a few rows of data which can easily be counted, but other searches may return a lot of rows of data which would be difficult to count. It would also give users an idea of which cities, states, shapes etc. return the most data.

Unit 14 | Assignment - JavaScript and DOM Manipulation

Skills tested: JavaScript, DOM Manipulation, some D3.js

This exercise utilizes Javascript and DOM manipulation using the D3 and Bootstrap libraries.  This project uses JS to import a file with a list of dictionaries with data on UFO sightings.  The idea is to create a filter that is manipulated by the user in order to filter the data that he or she want to search for, based on data, country, city, state, and shape of the object.  Then manipulate the HTML file with the data via scripting.  The hardest part of this project was the pagination, because there are about 30,000 data entries in the file.  The user cannot upload all of the data on one page.  Hence, the data must be sliced and shown 50 at a time, this allows for quicker load times (client-side pagination).  The data was sliced into an array, within another array, therefore allowing a separation of data (inner array) and pages (outer array).  The length of pages will dictate the number of pages.  Although most of the requirements (if not all) were met, there are some areas to improve: aesthetics could be better and maybe the filter can be tweeked just a bit (can be more efficient).  Some ideas would be to use separate functions for the filters or better pagination (such as showing only 8 pages of data at a time, with forward/reverse buttons).








______________________________________________________________________________________________________________

Unit 14 | Assignment - JavaScript and DOM Manipulation
Background
WAKE UP SHEEPLE! The extra-terrestrial menace has come to Earth and we here at www.ALIENS-R-REAL.com have collected all of the eye-witness reports we could to prove it! All we need to do now is put this information online for the world to see and then the matter will finally be put to rest.

There is just one tiny problem though... Our collection is too large to search through manually. Even our most dedicated followers are complaining that they are having trouble locating specific reports in this mess.

That's why we are hiring you. We need you to write code that will create a table dynamically based upon a dataset we provide. We also need to allow our users to search through the table for specific pieces of information. There's a catch though... We only use pure JavaScript, HTML, and CSS on our web pages. They are the only coding languages which can be trusted.

You can handle this... Right? The planet Earth needs to know what we have found!

Your Task
Level 1: Automatic Table and Date Search
Create a basic HTML web page.

Using the ufo dataset provided in the form of a JavaScript object, write code that appends a table to your web page and then adds new rows of data for each UFO sighting.

Make sure you have a column for date/time, city, state, country, shape, and comment at the very least.
Add an input tag to your HTML document and write JavaScript code that will search through the date/time column to find rows that match user input.

Level 2: Multiple Search Categories
Complete all of Level 1 criteria.

Using multiple input tags and/or select dropdowns, write JavaScript code so the user can to set multiple filters and search for UFO sightings using the following criteria based on the table columns:

date/time
city
state
country
shape
Level 3: Paginated Table
Complete all of Level 2 criteria.

Write code that will paginate the table (client-side pagination) and only display a maximum set number of results at a time (e.g. 50 results per page). Use Bootstrap's Pagination Components and write code to handle page changes and calculate the number of results which should appear on each page.

These changes should happen in the DOM using JavaScript, therefore the user should never be directed to another web page as they paginate through the results.

Dataset
UFO Sightings Data
Assessment
Your final product will be assessed on the following metrics:

Completion of all steps in chosen level

Visual attraction

Usability

Good luck!

Copyright
Coding Boot Camp (C) 2016. All Rights Reserved.
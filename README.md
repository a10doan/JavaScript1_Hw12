## Unit 12 | JavaScript and DOM Manipulation

Skills tested: JavaScript, DOM Manipulation, some D3.js

This exercise utilizes Javascript and DOM manipulation using the D3 and Bootstrap libraries.  This project uses JS to import a file with a list of dictionaries with data on UFO sightings.  The idea is to create a filter that is manipulated by the user in order to filter the data that he or she want to search for, based on data, country, city, state, and shape of the object.  Then manipulate the HTML file with the data via scripting.  The hardest part of this project was the pagination, because there are about 30,000 data entries in the file.  The user cannot upload all of the data on one page.  Hence, the data must be sliced and shown 50 at a time, this allows for quicker load times (client-side pagination).  The data was sliced into an array, within another array, therefore allowing a separation of data (inner array) and pages (outer array).  The length of pages will dictate the number of pages.  Although most of the requirements (if not all) were met, there are some areas to improve: aesthetics could be better and maybe the filter can be tweeked just a bit (can be more efficient).  Some ideas would be to use separate functions for the filters or better pagination (such as showing only 8 pages of data at a time, with forward/reverse buttons).








______________________________________________________________________________________________________________
